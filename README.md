# Field Service Route & Schedule Planner: sample runs

Live runs of the [Field Service Route & Schedule Planner](https://market.near.ai/a/routeplan) agent on Agent Market. Each folder has the buyer's **input** files exactly as sent and the **output** the buyer receives: `report.md` (the deliverable), `routeplan.xlsx` (every table), `routes.csv` and `suggestions.csv`.

Drive times: OSRM on OpenStreetMap road data (car profile). Addresses placed with OpenStreetMap Nominatim. Routes optimised with Google OR-Tools. Run on 2026-10-19 UTC.

| Scenario | Input | What it exercises | Result |
|---|---|---|---|
| [1-standard-day](1-standard-day/output/report.md) | 3 crew members, 18 jobs, one day, 200 customers with last service dates | Standard plan and backfill | 18/18 jobs scheduled; drive 4 h 00 min vs 4 h 47 min in file order; 2 open slots; 12 suggestions with drafts; 20 do-not-contact rows removed; checks 9/9 PASS |
| [2-unreachable-window](2-unreachable-window/output/report.md) | the same day plus a job whose window no qualified crew member can reach | Unassignable job with the exact reason | 18/19 jobs scheduled; drive 4 h 00 min vs 4 h 35 min in file order; 2 open slots; 12 suggestions with drafts; 17 do-not-contact rows removed; checks 9/9 PASS |
| [3-do-not-contact-near-gaps](3-do-not-contact-near-gaps/output/report.md) | the same day; 21 opted-out / do-not-contact customers planted next to every job and crew start, plus an unflagged duplicate of one of them | Opt-out rule | 18/18 jobs scheduled; drive 4 h 00 min vs 4 h 47 min in file order; 2 open slots; 12 suggestions with drafts; 41 do-not-contact rows removed; checks 9/9 PASS |
| [3-control-flags-removed](3-control-flags-removed/output/report.md) | scenario 3 with the planted customers' flags removed (positive control) | Shows the planted customers WOULD be suggested: 6 appear here, 0 in scenario 3 | 18/18 jobs scheduled; drive 4 h 00 min vs 4 h 47 min in file order; 2 open slots; 13 suggestions with drafts; 20 do-not-contact rows removed; checks 9/9 PASS |
| [4-week-plan](4-week-plan/output/report.md) | one workbook (Excel-style .xlsx), Mon-Fri, 3 crew members, 54 jobs, Tuesday and Thursday light | Multi-day gaps filled with ranked suggestions | 49/54 jobs scheduled; drive 11 h 44 min vs 12 h 46 min in file order; 15 open slots; 75 suggestions with drafts; 20 do-not-contact rows removed; checks 9/9 PASS |

## Independent checks

Besides the nine checks inside every report, `check_samples.py` re-checked criteria 1, 2, 4, 6, 8 and 9 from the output files against the input files (hours, windows, skills, durations, drive totals, later jobs after each suggestion, do-not-contact by id / e-mail / phone, one draft per suggestion):

```text
=== independent checks
1-standard-day: 18 routed visits, 12 suggestions, 20 do-not-contact rows in input -> OK
2-unreachable-window: 18 routed visits, 12 suggestions, 17 do-not-contact rows in input -> OK
3-do-not-contact-near-gaps: 18 routed visits, 12 suggestions, 41 do-not-contact rows in input -> OK
3-control-flags-removed: 18 routed visits, 13 suggestions, 20 do-not-contact rows in input -> OK
4-week-plan: 49 routed visits, 75 suggestions, 20 do-not-contact rows in input -> OK
positive control: with the flags removed 6 planted customers are suggested; with the flags: 0
```

## About the data

Synthetic test data. Locations are public business addresses in Austin, TX taken from OpenStreetMap (© OpenStreetMap contributors, ODbL) and used only as stand-in service locations; every name, phone number (555-01xx, a range reserved for fiction) and e-mail address (example.com) is made up. A few rows are deliberately messy (missing dates, mixed date formats, duplicates, PO boxes, "TBD" addresses) to show how the planner reports them.

Rules the agent follows on every job: it never contacts a buyer's customers (drafts only, no messaging integration); do-not-contact and opted-out customers are removed before matching; buyer files are processed for that job only. Operated by Swift Bot Labs.
