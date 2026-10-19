# Route plan and schedule backfill: Mon 26 Oct 2026 to Fri 30 Oct 2026

## Findings

- **49 of 54 jobs scheduled** on 15 crew-day(s); **5 unassigned**, each with its reason below.
- **Total drive time 11 h 44 min**, versus 12 h 46 min if each crew member visited the same jobs in the order of your file (1 h 02 min saved, 8%).
- **15 open slot(s) of 60+ min** (61 h 13 min of free time in total).
- **75 backfill suggestion(s)**, ranked per slot, each due for service according to your list, each checked so that every later job still starts inside its window, each with a ready-to-send draft. **Nothing was sent to anyone.**
- Do-not-contact / opted-out: **20 row(s) removed before matching**; none of them appear in the suggestions.
- Note: planning period from the brief: week of 2026-10-26

## Checks against the acceptance rules

| # | Check | Result | Detail |
|---|---|---|---|
| 1 | Every job is scheduled or listed as unassigned with a reason | PASS | 54 jobs in: 49 scheduled + 5 unassigned |
| 2 | Working hours, time windows and skills respected | PASS | 49 visits checked on 15 crew-days |
| 3 | Drive times from a routing service (named in the report) | PASS | OSRM table API; see Method |
| 4 | Total drive time lower than visiting the jobs in the order given | PASS | 704 min vs 766 min in file order (-62 min) |
| 5 | Every open slot of at least 60 min is listed with crew member, time and area | PASS | 15 slots of 60+ min listed |
| 6 | Adding any suggested customer keeps every later job inside its window | PASS | 75 suggestions re-simulated one by one |
| 7 | Every suggested customer is due according to the data, with the reason | PASS | 75 suggestions, each with its due reason |
| 8 | No do-not-contact / opted-out customer in the suggestions | PASS | 20 do-not-contact/opted-out rows in the list; 0 of them suggested |
| 9 | Every suggestion has a draft; nothing is sent | PASS | 75 drafts written; this agent has no e-mail/SMS/phone integration |

## Schedule by crew member

### Mon 26 Oct 2026

**Dana Ruiz**: hours 07:30-16:00 · skills: hvac; plumbing · 5 job(s) · drive 1 h 03 min · back at the start 15:04

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:30 | | start | 8940 Research Boulevard, Austin, TX 78758 | | | |
| 1 | 07:37 | 07:37 | 09:07 | J-009 (Susan Scott) | 101 West Koenig Lane, Austin, TX 78751 | any time | plumbing | 8 min |
| 2 | 09:22 | 09:22 | 11:22 | J-004 (Kevin Ramirez) | 3300 Duval Road, Austin, TX 78759 | 08:00-12:00 | plumbing | 15 min |
| 3 | 11:27 | 12:00 (waits 32 min) | 13:15 | J-010 (Steven Anderson) | 4600 Seton Center Parkway, Austin, TX 78759 | 12:00-16:00 | plumbing | 5 min |
| 4 | 13:21 | 13:21 | 13:51 | J-016 (Carlos Brown) | 1908 Kramer Lane, Austin, TX 78758 | 12:00-16:00 | hvac | 7 min |
| 5 | 14:07 | 14:07 | 14:52 | J-006 (Wei Mitchell) | 1801 East 51st Street, Austin, TX 78723 | 14:00-16:00 | plumbing | 15 min |
| end | 15:04 | | | back at the start | 8940 Research Boulevard, Austin, TX 78758 | | | 13 min |

**Marcus Lee**: hours 08:00-17:00 · skills: hvac · 5 job(s) · drive 1 h 38 min · back at the start 15:37

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 08:00 | | start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | |
| 1 | 08:08 | 08:08 | 09:08 | J-008 (Joshua Robinson) | 4600 Teri Road, Austin, TX 78744 | 08:00-12:00 | hvac | 9 min |
| 2 | 09:27 | 09:27 | 11:27 | J-001 (Donna Baker) | 501 West Powell Lane, Austin, TX 78753 | any time | hvac | 19 min |
| 3 | 11:35 | 11:35 | 13:05 | J-013 (Lisa Sanchez) | 8015 Shoal Creek Boulevard, Austin, TX 78757 | any time | hvac | 7 min |
| 4 | 13:35 | 13:35 | 14:20 | J-015 (Elena Brown) | 7000 Hester Road, Austin, TX 78725 (street-level location) | 12:00-16:00 | hvac | 30 min |
| 5 | 14:45 | 14:45 | 15:30 | J-005 (Linda Smith) | 7000 Woodhue Drive, Austin, TX 78745 | 12:00-16:00 | hvac | 25 min |
| end | 15:37 | | | back at the start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | 7 min |

**Priya Shah**: hours 07:00-15:30 · skills: plumbing; electrical · 6 job(s) · drive 1 h 12 min · back at the start 15:21

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:00 | | start | 1138 Airport Boulevard, Austin, TX 78702 | | | |
| 1 | 07:20 | 08:00 (waits 40 min) | 08:30 | J-002 (Omar Wilson) | 8700 Menchaca Road, Austin, TX 78748 | 08:00-12:00 | electrical | 20 min |
| 2 | 08:38 | 08:38 | 10:08 | J-011 (David Lewis) | 4534 Westgate Boulevard, Austin, TX 78745 | 08:00-11:00 | plumbing | 8 min |
| 3 | 10:16 | 10:16 | 11:46 | J-014 (Betty Hall) | 401 Deep Eddy Avenue, Austin, TX 78703 | 09:00-12:00 | plumbing | 8 min |
| 4 | 12:03 | 12:03 | 12:48 | J-007 (Thomas Rivera) | 7102 Meadowood Drive, Austin, TX 78723 | 12:00-16:00 | plumbing | 17 min |
| 5 | 12:52 | 12:52 | 14:22 | J-012 (Luis Harris) | 4601 Pecan Brook Drive, Austin, TX 78724 | any time | plumbing | 5 min |
| 6 | 14:33 | 14:33 | 15:18 | J-003 (William Jackson) | 3811 East 12th Street, Austin, TX 78721 | 14:00-16:00 | plumbing | 11 min |
| end | 15:21 | | | back at the start | 1138 Airport Boulevard, Austin, TX 78702 | | | 3 min |

### Tue 27 Oct 2026

**Dana Ruiz**: hours 07:30-16:00 · skills: hvac; plumbing · 1 job(s) · drive 22 min · back at the start 11:40

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:30 | | start | 8940 Research Boulevard, Austin, TX 78758 | | | |
| 1 | 07:41 | 11:00 (waits 3 h 19 min) | 11:30 | J-017 (Elizabeth Carter) | 13000 North Lamar Boulevard, Austin, TX 78753 | 11:00-13:00 | hvac | 11 min |
| end | 11:40 | | | back at the start | 8940 Research Boulevard, Austin, TX 78758 | | | 11 min |

**Marcus Lee**: hours 08:00-17:00 · skills: hvac · 2 job(s) · drive 23 min · back at the start 10:22

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 08:00 | | start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | |
| 1 | 08:08 | 08:08 | 09:23 | J-019 (Michelle Walker) | 1845 Burton Drive, Austin, TX 78741 | any time | hvac | 8 min |
| 2 | 09:34 | 09:34 | 10:19 | J-018 (William Baker) | 4477 South Lamar Boulevard, Austin, TX 78745 | 08:00-12:00 | hvac | 11 min |
| end | 10:22 | | | back at the start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | 4 min |

**Priya Shah**: hours 07:00-15:30 · skills: plumbing; electrical · 0 job(s) · drive 0 min · back at the start 07:00

No jobs on this day (the whole shift is an open slot).

### Wed 28 Oct 2026

**Dana Ruiz**: hours 07:30-16:00 · skills: hvac; plumbing · 4 job(s) · drive 43 min · back at the start 12:55

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:30 | | start | 8940 Research Boulevard, Austin, TX 78758 | | | |
| 1 | 07:41 | 08:00 (waits 18 min) | 08:30 | J-026 (Sarah Walker) | 5914 Lost Horizon Drive, Austin, TX 78759 | 08:00-10:00 | plumbing | 12 min |
| 2 | 08:36 | 09:00 (waits 24 min) | 10:00 | J-032 (Lisa Patel) | 10902 Windridge Drive, Austin, TX 78759 (street-level location) | 09:00-11:00 | plumbing | 6 min |
| 3 | 10:13 | 10:13 | 11:43 | J-029 (Betty Hall) | 11700 Metric Boulevard, Austin, TX 78758 | 09:00-12:00 | hvac | 14 min |
| 4 | 11:49 | 11:49 | 12:49 | J-035 (Michelle White) | 3908 West Braker Lane, Austin, TX 78759 | 11:00-13:00 | hvac | 5 min |
| end | 12:55 | | | back at the start | 8940 Research Boulevard, Austin, TX 78758 | | | 6 min |

**Marcus Lee**: hours 08:00-17:00 · skills: hvac · 3 job(s) · drive 36 min · back at the start 15:03

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 08:00 | | start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | |
| 1 | 08:07 | 08:07 | 08:37 | J-033 (Michelle Scott) | 1900 East Oltorf Street, Austin, TX 78741 | 08:00-12:00 | hvac | 7 min |
| 2 | 08:52 | 08:52 | 09:37 | J-021 (Omar Walker) | 7501 Longview Road, Austin, TX 78745 | 08:00-12:00 | hvac | 16 min |
| 3 | 09:47 | 14:00 (waits 4 h 12 min) | 15:00 | J-024 (Patricia Brown) | 4006 South Lamar Boulevard, Austin, TX 78704 | 14:00-16:00 | hvac | 10 min |
| end | 15:03 | | | back at the start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | 4 min |

**Priya Shah**: hours 07:00-15:30 · skills: plumbing; electrical · 6 job(s) · drive 1 h 28 min · back at the start 15:23

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:00 | | start | 1138 Airport Boulevard, Austin, TX 78702 | | | |
| 1 | 07:10 | 07:10 | 07:40 | J-027 (Anthony Chen) | 1605 East Oltorf, Austin, TX 78741 | any time | plumbing | 10 min |
| 2 | 07:48 | 09:00 (waits 1 h 11 min) | 10:15 | J-028 (Sandra Campbell) | 2821 San Jacinto Boulevard, Austin, TX 78705 | 09:00-12:00 | electrical | 9 min |
| 3 | 10:31 | 10:31 | 11:01 | J-023 (Joshua Lee) | 11150 Research Boulevard, Austin, TX 78759 | any time | electrical | 17 min |
| 4 | 11:21 | 11:21 | 12:21 | J-030 (Omar Wilson) | 2901 S Capital Of Texas Hwy Ste F4, Austin, TX 78746 | 11:00-13:00 | electrical | 19 min |
| 5 | 12:36 | 12:36 | 14:06 | J-031 (Betty Carter) | 2223 Waterloo City Lane, Austin, TX 78741 | 12:00-16:00 | plumbing | 15 min |
| 6 | 14:18 | 14:18 | 15:18 | J-020 (Omar Clark) | 4631 Airport Boulevard, Austin, TX 78751 | 12:00-16:00 | electrical | 12 min |
| end | 15:23 | | | back at the start | 1138 Airport Boulevard, Austin, TX 78702 | | | 5 min |

### Thu 29 Oct 2026

**Dana Ruiz**: hours 07:30-16:00 · skills: hvac; plumbing · 2 job(s) · drive 32 min · back at the start 14:05

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:30 | | start | 8940 Research Boulevard, Austin, TX 78758 | | | |
| 1 | 07:40 | 07:40 | 08:55 | J-038 (Anthony Green) | 1207 East Dean Keeton Street, Austin, TX 78722 | any time | hvac | 11 min |
| 2 | 09:11 | 13:00 (waits 3 h 49 min) | 14:00 | J-036 (Joshua Allen) | 10307 Morado Cove, Austin, TX 78759 | 13:00-15:00 | plumbing | 15 min |
| end | 14:05 | | | back at the start | 8940 Research Boulevard, Austin, TX 78758 | | | 6 min |

**Marcus Lee**: hours 08:00-17:00 · skills: hvac · 0 job(s) · drive 0 min · back at the start 08:00

No jobs on this day (the whole shift is an open slot).

**Priya Shah**: hours 07:00-15:30 · skills: plumbing; electrical · 1 job(s) · drive 36 min · back at the start 08:20

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:00 | | start | 1138 Airport Boulevard, Austin, TX 78702 | | | |
| 1 | 07:17 | 07:17 | 08:02 | J-037 (William Thompson) | 7612 Cooper Lane, Austin, TX 78745 | any time | electrical | 18 min |
| end | 08:20 | | | back at the start | 1138 Airport Boulevard, Austin, TX 78702 | | | 18 min |

### Fri 30 Oct 2026

**Dana Ruiz**: hours 07:30-16:00 · skills: hvac; plumbing · 5 job(s) · drive 1 h 14 min · back at the start 15:39

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:30 | | start | 8940 Research Boulevard, Austin, TX 78758 | | | |
| 1 | 07:49 | 08:00 (waits 10 min) | 10:00 | J-049 (Patricia Campbell) | 3600 Silver Dollar Circle, Austin, TX 78744 | 08:00-12:00 | plumbing | 20 min |
| 2 | 10:24 | 10:24 | 11:09 | J-054 (Joshua Young) | 10610 Morado Circle, Austin, TX 78759 | 08:00-12:00 | hvac | 25 min |
| 3 | 11:18 | 11:18 | 12:33 | J-045 (Maria Okafor) | 6517 Cascada Drive, Austin, TX 78750 | any time | plumbing | 9 min |
| 4 | 12:43 | 12:43 | 13:58 | J-051 (William Anderson) | 11701 Domain Blvd, Austin, TX 78758 | any time | hvac | 10 min |
| 5 | 14:03 | 14:03 | 15:33 | J-042 (Thomas King) | 1901 West Braker Lane, Austin, TX 78758 | any time | plumbing | 5 min |
| end | 15:39 | | | back at the start | 8940 Research Boulevard, Austin, TX 78758 | | | 5 min |

**Marcus Lee**: hours 08:00-17:00 · skills: hvac · 4 job(s) · drive 57 min · back at the start 14:16

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 08:00 | | start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | |
| 1 | 08:06 | 08:06 | 08:51 | J-050 (Joseph Martinez) | 205 East Monroe Street, Austin, TX 78704 | any time | hvac | 6 min |
| 2 | 08:58 | 08:58 | 09:43 | J-043 (Barbara Flores) | 2508 East Riverside Drive, Austin, TX 78741 | any time | hvac | 7 min |
| 3 | 09:55 | 12:00 (waits 2 h 04 min) | 12:30 | J-041 (Brian Hall) | 3604 Axel Lane, Austin, TX 78721 | 12:00-16:00 | hvac | 12 min |
| 4 | 12:46 | 12:46 | 14:01 | J-053 (Nancy Brown) | 741 Dalton Lane, Austin, TX 78742 | any time | hvac | 16 min |
| end | 14:16 | | | back at the start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | 15 min |

**Priya Shah**: hours 07:00-15:30 · skills: plumbing; electrical · 5 job(s) · drive 1 h 01 min · back at the start 14:39

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:00 | | start | 1138 Airport Boulevard, Austin, TX 78702 | | | |
| 1 | 07:06 | 08:00 (waits 54 min) | 09:15 | J-048 (Donna Mitchell) | 1001 East 52nd Street, Austin, TX 78751 | 08:00-12:00 | plumbing | 6 min |
| 2 | 09:25 | 09:25 | 11:25 | J-046 (Wei Okafor) | 1931 E Oltorf St, Austin, TX 78741 | 08:00-12:00 | electrical | 10 min |
| 3 | 11:30 | 11:30 | 12:15 | J-044 (Daniel Brown) | 3903 Warehouse Row, Austin, TX 78704 | any time | electrical | 6 min |
| 4 | 12:25 | 12:25 | 13:10 | J-052 (Robert Walker) | 6700 West Gate Boulevard, Austin, TX 78745 | any time | electrical | 10 min |
| 5 | 13:27 | 13:27 | 14:27 | J-039 (Wei Lopez) | 5608 Parkcrest Drive, Austin, TX 78731 | any time | plumbing | 17 min |
| end | 14:39 | | | back at the start | 1138 Airport Boulevard, Austin, TX 78702 | | | 12 min |

## Unassigned jobs

| Job | Address | Date | Window | Skill | Reason |
|---|---|---|---|---|---|
| J-047 | 7112 Ed Bluestein Boulevard, Austin, TX 78723 | 2026-10-30 | 08:00-12:00 | plumbing | the address could not be found on the map (no match) |
| J-022 | 6216 Ed Bluestein Boulevard, Austin, TX 78724 | 2026-10-28 | any time | electrical | the address could not be found on the map (no match) |
| J-034 | 2407 South Congress Avenue, Austin, TX 78704 | 2026-10-28 | 14:00-17:00 | plumbing | time window 14:00-17:00 is outside the working hours of every qualified crew member (latest finish 16:00 incl. the drive back) |
| J-025 | 6518 Ed Bluestein Boulevard, Austin, TX 78723 | 2026-10-28 | any time | plumbing | the address could not be found on the map (no match) |
| J-040 | 7800 South 1st Street, Austin, TX 78745 | 2026-10-30 | 09:00-11:00 | plumbing | no room: every qualified crew member's day is full around this job's window (09:00-11:00); each of the 2 qualified crew-days was tried at every position |

## Drive time: plan versus the order in your file

Baseline: each crew member visits the same jobs in the order they appear in your jobs file, leaving at the start of the shift.

| Day | Crew member | Jobs | Planned drive | File-order drive | File order on time? |
|---|---|---|---|---|---|
| Mon 26 Oct 2026 | Dana Ruiz | 5 | 1 h 03 min | 1 h 05 min | no: 2 late job(s), 4 h 54 min overtime |
| Tue 27 Oct 2026 | Dana Ruiz | 1 | 22 min | 22 min | yes |
| Wed 28 Oct 2026 | Dana Ruiz | 4 | 43 min | 42 min | no: 3 late job(s) |
| Thu 29 Oct 2026 | Dana Ruiz | 2 | 32 min | 34 min | yes |
| Fri 30 Oct 2026 | Dana Ruiz | 5 | 1 h 14 min | 1 h 20 min | no: 1 late job(s) |
| Mon 26 Oct 2026 | Marcus Lee | 5 | 1 h 38 min | 1 h 56 min | no: 2 late job(s), 39 min overtime |
| Tue 27 Oct 2026 | Marcus Lee | 2 | 23 min | 23 min | yes |
| Wed 28 Oct 2026 | Marcus Lee | 3 | 36 min | 40 min | no: 2 late job(s) |
| Fri 30 Oct 2026 | Marcus Lee | 4 | 57 min | 1 h 05 min | yes |
| Mon 26 Oct 2026 | Priya Shah | 6 | 1 h 12 min | 1 h 31 min | no: 3 late job(s), 5 h 27 min overtime |
| Wed 28 Oct 2026 | Priya Shah | 6 | 1 h 28 min | 1 h 23 min | no: 2 late job(s), 3 h 33 min overtime |
| Thu 29 Oct 2026 | Priya Shah | 1 | 36 min | 36 min | yes |
| Fri 30 Oct 2026 | Priya Shah | 5 | 1 h 01 min | 1 h 09 min | no: 1 late job(s) |
| **Total** | | 49 | **11 h 44 min** | **12 h 46 min** | |

## Open slots (60+ min)

| Slot | Day | Crew member | Free | From | To | Area (between) | Suggestions |
|---|---|---|---|---|---|---|---|
| 1 | Mon 26 Oct 2026 | Marcus Lee | 1 h 22 min | 15:30 | 16:52 | Austin 78745 (between job J-005 (7000 Woodhue Drive, Austin, TX 78745) and end of day back at the start) | 0 |
| 2 | Tue 27 Oct 2026 | Dana Ruiz | 3 h 19 min | 07:30 | 10:48 | Wooten, Austin 78758 to Park Central, Austin 78753 (between start (8940 Research Boulevard, Austin, TX 78758) and job J-017 (13000 North Lamar Boulevard, Austin, TX 78753)) | 5 |
| 3 | Tue 27 Oct 2026 | Dana Ruiz | 4 h 19 min | 11:30 | 15:49 | Park Central, Austin 78753 (between job J-017 (13000 North Lamar Boulevard, Austin, TX 78753) and end of day back at the start) | 5 |
| 4 | Tue 27 Oct 2026 | Marcus Lee | 6 h 37 min | 10:19 | 16:56 | Austin 78745 (between job J-018 (4477 South Lamar Boulevard, Austin, TX 78745) and end of day back at the start) | 5 |
| 5 | Tue 27 Oct 2026 | Priya Shah | 8 h 30 min | 07:00 | 15:30 | Austin 78702 (between start (1138 Airport Boulevard, Austin, TX 78702) and end of day back at the start) | 8 |
| 6 | Wed 28 Oct 2026 | Dana Ruiz | 3 h 05 min | 12:49 | 15:53 | Stonelake, Austin 78759 (between job J-035 (3908 West Braker Lane, Austin, TX 78759) and end of day back at the start) | 5 |
| 7 | Wed 28 Oct 2026 | Marcus Lee | 4 h 12 min | 09:37 | 13:50 | Austin 78745 to Brodie Oaks, Austin 78704 (between job J-021 (7501 Longview Road, Austin, TX 78745) and job J-024 (4006 South Lamar Boulevard, Austin, TX 78704)) | 6 |
| 8 | Wed 28 Oct 2026 | Marcus Lee | 1 h 56 min | 15:00 | 16:56 | Brodie Oaks, Austin 78704 (between job J-024 (4006 South Lamar Boulevard, Austin, TX 78704) and end of day back at the start) | 5 |
| 9 | Wed 28 Oct 2026 | Priya Shah | 1 h 11 min | 07:40 | 08:51 | Austin 78741 to College Court, Austin 78705 (between job J-027 (1605 East Oltorf, Austin, TX 78741) and job J-028 (2821 San Jacinto Boulevard, Austin, TX 78705)) | 5 |
| 10 | Thu 29 Oct 2026 | Dana Ruiz | 3 h 49 min | 08:55 | 12:44 | Blackland, Austin 78722 to Austin 78759 (between job J-038 (1207 East Dean Keeton Street, Austin, TX 78722) and job J-036 (10307 Morado Cove, Austin, TX 78759)) | 5 |
| 11 | Thu 29 Oct 2026 | Dana Ruiz | 1 h 54 min | 14:00 | 15:54 | Austin 78759 (between job J-036 (10307 Morado Cove, Austin, TX 78759) and end of day back at the start) | 5 |
| 12 | Thu 29 Oct 2026 | Marcus Lee | 9 h 00 min | 08:00 | 17:00 | Banister Heights, Austin 78704 (between start (1221 West Ben White Boulevard, Austin, TX 78704) and end of day back at the start) | 4 |
| 13 | Thu 29 Oct 2026 | Priya Shah | 7 h 09 min | 08:02 | 15:12 | Austin 78745 (between job J-037 (7612 Cooper Lane, Austin, TX 78745) and end of day back at the start) | 8 |
| 14 | Fri 30 Oct 2026 | Marcus Lee | 2 h 04 min | 09:43 | 11:47 | East Riverside - Oltorf, Austin 78741 to MLK-183, Austin 78721 (between job J-043 (2508 East Riverside Drive, Austin, TX 78741) and job J-041 (3604 Axel Lane, Austin, TX 78721)) | 5 |
| 15 | Fri 30 Oct 2026 | Marcus Lee | 2 h 44 min | 14:01 | 16:44 | Austin 78742 (between job J-053 (741 Dalton Lane, Austin, TX 78742) and end of day back at the start) | 4 |

A slot is idle time in the crew member's day: from the end of one stop until they must leave for the next one (or until the end of working hours, including the drive back).

## Backfill suggestions

Ranked per slot by **score = overdue x proximity x fit** (formula under *Method*). Each one was inserted into the crew member's day on its own and the whole day re-checked: every later job still starts inside its window and the crew member still finishes inside working hours. *Fit together* lists the ranks that were also checked as one set.

### Slot 2: Tue 27 Oct 2026, Dana Ruiz, 07:30-10:48 (3 h 19 min free), Wooten, Austin 78758 to Park Central, Austin 78753

Fit together: #1, #2, #3 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Donna Lee (C-1064) | 11104 North Lamar Boulevard, Austin, TX 78753 | last service 2026-03-05, 236 days ago; plan '90 days' = every 90 days; due since 2026-06-03 (146 days overdue) | **High**: own plan interval, address located exactly | +1 min | 60 min | 10:20-11:20 | no | 2.53 |
| 2 | Susan Kim (C-1106) | 6801 Airport Boulevard, Austin, TX 78752 | last service 2025-12-09, 322 days ago; plan 'quarterly' = every 91 days; due since 2026-03-10 (231 days overdue) | **High**: own plan interval, address located exactly | +6 min | 60 min | 09:10-10:15 | no | 2.13 |
| 3 | Brian Martinez (C-1082) | 505 E Huntland Dr, Austin, TX 78752 | next service date 2026-10-02 (from your list); due since 2026-10-02 (25 days overdue) | **High**: dated record, address located exactly | +6 min | 90 min | 07:40-08:40 | no | 1.31 |
| 4 | Jennifer Johnson (C-1153) | 8618 Research Boulevard, Austin, TX 78757 | next service date 2026-10-15 (from your list); due since 2026-10-15 (12 days overdue) | **High**: dated record, address located exactly | +1 min | 90 min | 07:35-09:35 | no | 1.31 |
| 5 | Jessica Young (C-1060) | 9013 United Drive, Austin, TX 78758 | last service 2026-04-09, 201 days ago; plan 'every 6 months' = every 182 days; due since 2026-10-08 (19 days overdue) | **High**: own plan interval, address located exactly | +1 min | 90 min | 07:35-09:35 | no | 1.03 |

### Slot 3: Tue 27 Oct 2026, Dana Ruiz, 11:30-15:49 (4 h 19 min free), Park Central, Austin 78753

Fit together: #1, #2, #3 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Michael Roberts (C-1056) | 11600 Rock Rose Avenue, Austin, TX 78758 | last service 2025-12-20, 311 days ago; plan 'quarterly' = every 91 days; due since 2026-03-21 (220 days overdue) | **High**: own plan interval, address located exactly | +4 min | 60 min | 11:40-12:05 | no | 2.37 |
| 2 | Michael Moore (C-1192) | 2700 W Anderson Ln, Austin, TX 78757 | last service 2026-02-05, 264 days ago; plan 'quarterly' = every 91 days; due since 2026-05-07 (173 days overdue) | **High**: own plan interval, address located exactly | +8 min | 90 min | 13:55-14:20 | no | 1.89 |
| 3 | Rosa Taylor (C-1133) | 2216 Rutland Drive, Austin, TX 78758 | next service date 2026-10-13 (from your list); due since 2026-10-13 (14 days overdue) | **High**: dated record, address located exactly | +2 min | 60 min | 12:45-13:10 | no | 1.30 |
| 4 | Jennifer Harris (C-1021) | 1921 Cedar Bend Drive, Austin, TX 78758 | open quote (service itself next due 2027-08-30) | **Medium**: open quote, not a scheduled service | +1 min | 60 min | 11:35-13:35 | no | 1.20 |
| 5 | Mei Patel (C-1037) | 3333 Read Granberry Trail, Austin, TX 78758 | last service 2026-04-04, 206 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due since 2026-10-03 (24 days overdue) | **Medium**: interval assumed from the service type | +5 min | 90 min | 11:45-13:45 | no | 0.84 |

### Slot 4: Tue 27 Oct 2026, Marcus Lee, 10:19-16:56 (6 h 37 min free), Austin 78745

Fit together: #1, #2, #3 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Jessica Scott (C-1117) | 4211 S Lamar Blvd, Austin, TX 78704 | last service 2026-01-24, 276 days ago; plan 'quarterly' = every 91 days; due since 2026-04-25 (185 days overdue) | **High**: own plan interval, address located exactly | +2 min | 90 min | 13:50-15:25 | no | 2.58 |
| 2 | Lisa Johnson (C-1088) | 2500 W William Cannon Dr, Austin, TX 78745 | last service 2026-01-21, 279 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due since 2026-07-22 (97 days overdue) | **Medium**: interval assumed from the service type | +10 min | 90 min | 10:30-12:00 | no | 0.93 |
| 3 | Elena Harris (C-1181) | 3636 Bee Caves Road, Austin, TX 78746 | next service date 2026-10-04 (from your list); due since 2026-10-04 (23 days overdue) | **High**: dated record, address located exactly | +17 min | 90 min | 12:10-13:45 | no | 0.84 |
| 4 | David Torres (C-1025) | 2017 Robert Dedman Drive, Austin, TX 78712 | last service 2025-12-29, 302 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-06-29 (120 days overdue) | **Medium**: interval assumed from the service type | +23 min | 90 min | 10:35-12:35 | no | 0.65 |
| 5 | Fatima Walker (C-1105) | 903 West 12th Street, Austin, TX 78703 | last service 2026-04-10, 200 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due since 2026-10-09 (18 days overdue) | **Medium**: interval assumed from the service type | +19 min | 90 min | 10:35-12:35 | no | 0.48 |

### Slot 5: Tue 27 Oct 2026, Priya Shah, 07:00-15:30 (8 h 30 min free), Austin 78702

Fit together: #1, #2, #3, #4, #5, #6, #7 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Richard Hall (C-1006) | 2795 East 7th Street, Austin, TX 78702 | last service 2025-10-19, 373 days ago; plan '90 days' = every 90 days; due since 2026-01-17 (283 days overdue) | **Low**: overdue more than 3 intervals (may no longer be a customer) | +7 min | 60 min | 13:40-14:25 | no | 2.07 |
| 2 | Robert Adams (C-1099) | 313 East 12th Street, Austin, TX 78701 | next service date 2026-09-22 (from your list); due since 2026-09-22 (35 days overdue) | **High**: dated record, address located exactly | +12 min | 60 min | 09:25-10:05 | no | 1.21 |
| 3 | Jorge Hernandez (C-1132) | 1100 South Lamar Boulevard, Austin, TX 78704 | last service 2025-10-18, 374 days ago; plan 'quarterly' = every 91 days; due since 2026-01-17 (283 days overdue) | **Low**: overdue more than 3 intervals (may no longer be a customer) | +25 min | 60 min | 11:30-12:15 | no | 1.13 |
| 4 | Michael Thompson (C-1081) | 6019 I 35 Frontage Road, Austin, TX 78723 | last service 2025-12-09, 322 days ago; plan 'every 6 months' = every 182 days; due since 2026-06-09 (140 days overdue) | **High**: own plan interval, address located exactly | +14 min | 60 min | 07:10-07:50 | no | 0.90 |
| 5 | Jessica Smith (C-1017) | 517 South Lamar Boulevard, Austin, TX 78704 | last service 2026-06-08, 141 days ago; plan '90 days' = every 90 days; due since 2026-09-06 (51 days overdue) | **High**: own plan interval, address located exactly | +22 min | 60 min | 12:35-13:15 | no | 0.64 |
| 6 | Anthony Campbell (C-1051) | 2617 Speedway, Austin, TX 78705 | open quote (service itself next due 2027-01-30) | **Medium**: open quote, not a scheduled service | +15 min | 60 min | 08:15-09:00 | no | 0.63 |
| 7 | Steven Hall (C-1138) | 700 Lavaca Suite 1400, Austin, TX 78701 | last service 2025-09-09, 413 days ago; default interval, assumed for 'Water heater flush' = 365 days; due since 2026-09-09 (48 days overdue) | **Medium**: interval assumed from the service type | +15 min | 60 min | 10:25-11:10 | no | 0.57 |
| 8 | Karen Thompson (C-1049) | 215 South Lamar Boulevard, Austin, TX 78704 | last service 2026-03-18, 223 days ago; plan 'semi-annual' = every 182 days; due since 2026-09-16 (41 days overdue) | **High**: own plan interval, address located exactly | +20 min | 60 min | 07:15-09:15 | no | 0.52 |

### Slot 6: Wed 28 Oct 2026, Dana Ruiz, 12:49-15:53 (3 h 05 min free), Stonelake, Austin 78759

Fit together: #1, #2 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Joshua Brown (C-1091) | 4210 West Balcones Center Drive, Austin, TX 78759 | last service 2025-10-07, 386 days ago; plan '90 days' = every 90 days; due since 2026-01-05 (296 days overdue) | **Low**: overdue more than 3 intervals (may no longer be a customer) | +1 min | 90 min | 12:55-13:10 | no | 2.73 |
| 2 | Steven Jackson (C-1102) | 5335 Burnet Road, Austin, TX 78756 | next service date 2026-09-15 (from your list); due since 2026-09-15 (43 days overdue) | **High**: dated record, address located exactly | +12 min | 60 min | 14:35-14:50 | no | 1.35 |
| 3 | Priya Hall (C-1191) | 8809 Burnet Road, Austin, TX 78757 | last service 2026-07-01, 119 days ago; plan 'quarterly' = every 91 days; due since 2026-09-30 (28 days overdue) | **High**: own plan interval, address located exactly | +2 min | 60 min | 13:00-14:55 | no | 1.17 |
| 4 | Sarah Robinson (C-1043) | 8920 Business Park Drive, Austin, TX 78759 | last service 2026-02-24, 246 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-08-25 (64 days overdue) | **Medium**: interval assumed from the service type | +4 min | 90 min | 12:55-14:20 | no | 1.05 |
| 5 | Richard Roberts (C-1059) | 5501 Burnet Road, Austin, TX 78756 | open quote (service itself next due 2026-12-11) | **Medium**: open quote, not a scheduled service | +12 min | 60 min | 13:00-14:50 | no | 0.70 |

### Slot 7: Wed 28 Oct 2026, Marcus Lee, 09:37-13:50 (4 h 12 min free), Austin 78745 to Brodie Oaks, Austin 78704

Fit together: #1, #2, #3 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Mei Hall (C-1001) | 824 West 10th Street, Austin, TX 78701 | last service 2026-02-05, 265 days ago; plan '90 days' = every 90 days; due since 2026-05-06 (175 days overdue) | **High**: own plan interval, address located exactly | +15 min | 90 min | 13:00-13:15 | no | 1.47 |
| 2 | James Kim (C-1131) | 1715 West Cesar Chavez Street, Austin, TX 78703 | last service 2025-11-07, 355 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-05-08 (173 days overdue) | **Medium**: interval assumed from the service type | +14 min | 90 min | 09:55-10:10 | no | 1.01 |
| 3 | Linda Clark (C-1075) | 422 Congress Avenue, Austin, TX 78701 | last service 2025-12-20, 312 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-06-20 (130 days overdue) | **Medium**: interval assumed from the service type | +15 min | 90 min | 11:30-11:45 | no | 0.85 |
| 4 | Donna Anderson (C-1023) | 6317 Bee Caves Road, Austin, TX 78746 | last service 2026-01-08, 293 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-07-09 (111 days overdue) | **Medium**: interval assumed from the service type | +15 min | 90 min | 09:55-11:55 | no | 0.81 |
| 5 | Carol Hernandez (C-1053) | 406 Walsh Street, Austin, TX 78703 | last service 2026-04-28, 183 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-10-27 (1 days overdue) | **Medium**: interval assumed from the service type | +12 min | 90 min | 09:55-11:55 | no | 0.55 |
| 6 | Linda Chen (C-1003) | 2500 Guadalupe Street, Austin, TX 78705 | last service 2026-04-08, 203 days ago; plan 'every 6 months' = every 182 days; due since 2026-10-07 (21 days overdue) | **High**: own plan interval, address located exactly | +19 min | 90 min | 09:55-11:55 | no | 0.49 |

### Slot 8: Wed 28 Oct 2026, Marcus Lee, 15:00-16:56 (1 h 56 min free), Brodie Oaks, Austin 78704

Fit together: only one at a time.

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | James Scott (C-1154) | 301 Ramble Lane, Austin, TX 78758 | last service 2025-12-07, 325 days ago; plan 'semi-annual' = every 182 days; due since 2026-06-07 (143 days overdue) | **High**: own plan interval, address located exactly | +9 min | 90 min | 15:10-15:20 | no | 1.12 |
| 2 | William Jackson (C-1046) | 1220 Colorado Street, Austin, TX 78701 | last service 2025-09-21, 402 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-03-22 (220 days overdue) | **Medium**: interval assumed from the service type | +20 min | 90 min | about 15:11 | no | 0.94 |
| 3 | Luis Hernandez (C-1070) | 200 West 2nd Street, Austin, TX 78701 | last service 2025-12-31, 301 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-07-01 (119 days overdue) | **Medium**: interval assumed from the service type | +16 min | 90 min | 15:10-15:15 | no | 0.80 |
| 4 | Nancy Patel (C-1007) | 79 Rainey Street, Austin, TX 78701 | last service 2026-02-25, 245 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-08-26 (63 days overdue) | **Medium**: interval assumed from the service type | +18 min | 90 min | about 15:11 | no | 0.62 |
| 5 | Jessica Torres (C-1197) | 400 Bowie Street, Austin, TX 78703 | last service 2026-04-29, 182 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due on this date | **Medium**: interval assumed from the service type | +16 min | 90 min | 15:10-15:15 | no | 0.48 |

### Slot 9: Wed 28 Oct 2026, Priya Shah, 07:40-08:51 (1 h 11 min free), Austin 78741 to College Court, Austin 78705

Fit together: only one at a time.

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Omar Lee (C-1134) | 1005 Congress Avenue, Austin, TX 78701 | last service 2025-10-28, 365 days ago; plan 'quarterly' = every 91 days; due since 2026-01-27 (274 days overdue) | **Low**: overdue more than 3 intervals (may no longer be a customer) | +4 min | 60 min | 07:50-07:55 | no | 2.40 |
| 2 | Rosa Davis (C-1178) | 1300 East Riverside Drive, Austin, TX 78741 | last service 2026-03-07, 235 days ago; plan '90 days' = every 90 days; due since 2026-06-05 (145 days overdue) | **High**: own plan interval, address located exactly | +5 min | 60 min | 07:45-07:50 | no | 1.92 |
| 3 | Patricia Taylor (C-1036) | 4300 North Lamar Boulevard, Austin, TX 78756 | last service 2025-10-18, 375 days ago; plan 'semi-annual' = every 182 days; due since 2026-04-18 (193 days overdue) | **High**: own plan interval, address located exactly | +8 min | 60 min | 07:55-08:00 | no | 1.35 |
| 4 | Richard Hernandez (C-1084) | 2301 Trinity Street, Austin, TX 78712 | next service date 2026-10-14 (from your list); due since 2026-10-14 (14 days overdue) | **High**: dated record, address located exactly | +3 min | 60 min | 07:50-08:00 | no | 1.22 |
| 5 | Carol Thomas (C-1045) | 2024 South Lamar Boulevard, Austin, TX 78704 | next service date 2026-10-02 (from your list); due since 2026-10-02 (26 days overdue) | **High**: dated record, address located exactly | +8 min | 60 min | about 07:45 | no | 1.20 |

### Slot 10: Thu 29 Oct 2026, Dana Ruiz, 08:55-12:44 (3 h 49 min free), Blackland, Austin 78722 to Austin 78759

Fit together: #1, #2, #3 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Steven Rivera (C-1147) | 2113 Manor Road, Austin, TX 78722 | last service 2026-04-21, 191 days ago; plan '90 days' = every 90 days; due since 2026-07-20 (101 days overdue) | **High**: own plan interval, address located exactly | +1 min | 60 min | 09:00-09:35 | no | 1.94 |
| 2 | Susan Perez (C-1113) | 1401 Philomena Street, Austin, TX 78723 | next service date 2026-09-16 (from your list); due since 2026-09-16 (43 days overdue) | **High**: dated record, address located exactly | +6 min | 90 min | 11:35-12:10 | no | 1.78 |
| 3 | Jessica Brown (C-1063) | 1900 Simond Avenue, Austin, TX 78723 | last service 2025-09-20, 404 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-03-21 (222 days overdue) | **Medium**: interval assumed from the service type | +4 min | 90 min | 10:05-10:40 | no | 1.74 |
| 4 | Ana Johnson (C-1139) | 2405 Trinity Street, Austin, TX 78705 | last service 2025-11-06, 357 days ago; plan 'every 6 months' = every 182 days; due since 2026-05-07 (175 days overdue) | **High**: own plan interval, address located exactly | +6 min | 90 min | 09:00-11:00 | no | 1.43 |
| 5 | Linda Baker (C-1164) | 1001 East 41st Street, Austin, TX 78751 | next service date 2026-10-22 (from your list); due since 2026-10-22 (7 days overdue) | **High**: dated record, address located exactly | +3 min | 90 min | 09:00-11:00 | no | 1.06 |

### Slot 11: Thu 29 Oct 2026, Dana Ruiz, 14:00-15:54 (1 h 54 min free), Austin 78759

Fit together: only one at a time.

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Priya Sanchez (C-1195) | 11310 Domain Drive, Austin, TX 78758 | last service 2026-03-05, 238 days ago; plan '90 days' = every 90 days; due since 2026-06-03 (148 days overdue) | **High**: own plan interval, address located exactly | +6 min | 90 min | 14:10-14:20 | no | 1.93 |
| 2 | Kevin Allen (C-1089) | 10401 Research Boulevard, Austin, TX 78759 | next service date 2026-10-06 (from your list); due since 2026-10-06 (23 days overdue) | **High**: dated record, address located exactly | +4 min | 90 min | 14:05-14:20 | no | 1.40 |
| 3 | Richard Hernandez (C-1121) | 9505 Arboretum Boulevard, Austin, TX 78759 | last service 2026-02-05, 266 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-08-06 (84 days overdue) | **Medium**: interval assumed from the service type | +4 min | 90 min | 14:05-14:20 | no | 1.18 |
| 4 | Betty Wilson (C-1065) | 3220 Read Granberry Trail, Austin, TX 78758 | last service 2025-08-29, 426 days ago; default interval, assumed for 'Water heater flush' = 365 days; due since 2026-08-29 (61 days overdue) | **Medium**: interval assumed from the service type | +5 min | 60 min | 14:10-14:50 | no | 0.89 |
| 5 | Wei Thomas (C-1077) | 900 Old Koenig Lane, Austin, TX 78756 | open quote (service itself next due 2027-05-09) | **Medium**: open quote, not a scheduled service | +14 min | 60 min | 14:15-14:50 | no | 0.64 |

### Slot 12: Thu 29 Oct 2026, Marcus Lee, 08:00-17:00 (9 h 00 min free), Banister Heights, Austin 78704

Fit together: #1, #2, #3, #4 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Matthew Young (C-1182) | 522 Congress Avenue, Austin, TX 78701 | next service date 2026-09-24 (from your list); due since 2026-09-24 (35 days overdue) | **High**: dated record, address located exactly | +21 min | 90 min | 08:15-10:15 | no | 0.91 |
| 2 | James Brown (C-1071) | 2701 East Cesar Chavez Street, Austin, TX 78702 | last service 2025-10-22, 372 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-04-22 (190 days overdue) | **Medium**: interval assumed from the service type | +25 min | 90 min | 12:50-14:50 | no | 0.77 |
| 3 | Carol Roberts (C-1189) | 123 West 6th Street, Austin, TX 78701 | last service 2026-01-07, 295 days ago; plan 'every 6 months' = every 182 days; due since 2026-07-08 (113 days overdue) | **High**: own plan interval, address located exactly | +21 min | 90 min | 09:45-11:45 | no | 0.68 |
| 4 | Donna Davis (C-1168) | 110 East 9th Street, Austin, TX 78701 | last service 2026-03-02, 241 days ago; plan 'every 6 months' = every 182 days; due since 2026-08-31 (59 days overdue) | **High**: own plan interval, address located exactly | +23 min | 90 min | 11:15-13:15 | no | 0.53 |

### Slot 13: Thu 29 Oct 2026, Priya Shah, 08:02-15:12 (7 h 09 min free), Austin 78745

Fit together: #1, #2, #3, #4, #5, #6 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Raj Okafor (C-1108) | 4315 James Casey Street, Austin, TX 78745 | last service 2025-09-26, 398 days ago; plan '90 days' = every 90 days; due since 2025-12-25 (308 days overdue) | **Low**: overdue more than 3 intervals (may no longer be a customer) | +4 min | 60 min | 08:15-09:00 | no | 2.39 |
| 2 | Luis Perez (C-1014) | 1705 South Lakeshore Boulevard, Austin, TX 78741 | next service date 2026-09-26 (from your list); due since 2026-09-26 (33 days overdue) | **High**: dated record, address located exactly | +2 min | 60 min | 10:25-11:10 | no | 1.85 |
| 3 | Thomas Lee (C-1022) | 1303 South Congress Avenue, Austin, TX 78704 | next service date 2026-10-10 (from your list); due since 2026-10-10 (19 days overdue) | **High**: dated record, address located exactly | +5 min | 60 min | 09:20-10:05 | no | 1.25 |
| 4 | Anthony Garcia (C-1200) | 901 East 5th Street, Austin, TX 78702 | open quote (service itself next due 2027-07-12) | **Medium**: open quote, not a scheduled service | +1 min | 60 min | 12:35-13:20 | no | 1.19 |
| 5 | Carlos Scott (C-1039) | 607 West 3rd Street, Austin, TX 78701 | last service 2026-02-24, 247 days ago; plan 'every 6 months' = every 182 days; due since 2026-08-25 (65 days overdue) | **High**: own plan interval, address located exactly | +6 min | 60 min | 11:30-12:15 | no | 0.96 |
| 6 | Brian Sanchez (C-1029) | 301 Chicon St Unit E, Austin, TX 78702 | last service 2025-10-23, 371 days ago; default interval, assumed for 'Water heater flush' = 365 days; due since 2026-10-23 (6 days overdue) | **Medium**: interval assumed from the service type | +2 min | 60 min | 13:35-14:20 | no | 0.91 |
| 7 | Brian Carter (C-1124) | 205 West 3rd Street, Austin, TX 78701 | last service 2025-09-17, 407 days ago; default interval, assumed for 'Water heater flush' = 365 days; due since 2026-09-17 (42 days overdue) | **Medium**: interval assumed from the service type | +4 min | 60 min | 08:20-10:20 | no | 0.86 |
| 8 | Lisa Allen (C-1188) | 9220 Brodie Lane, Austin, TX 78748 | last service 2025-09-01, 423 days ago; plan 'annual' = every 365 days; due since 2026-09-01 (58 days overdue) | **High**: own plan interval, address located exactly | +14 min | 60 min | 08:15-10:15 | no | 0.60 |

### Slot 14: Fri 30 Oct 2026, Marcus Lee, 09:43-11:47 (2 h 04 min free), East Riverside - Oltorf, Austin 78741 to MLK-183, Austin 78721

Fit together: #1, #2, #3 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Jessica Clark (C-1062) | 5000 Springdale Road, Austin, TX 78723 | last service 2025-11-02, 362 days ago; plan '90 days' = every 90 days; due since 2026-01-31 (272 days overdue) | **Low**: overdue more than 3 intervals (may no longer be a customer) | +5 min | 90 min | 13:00-13:05 | no | 2.24 |
| 2 | Thomas King (C-1137) | 2403 East 16th Street, Austin, TX 78702 | next service date 2026-09-22 (from your list); due since 2026-09-22 (38 days overdue) | **High**: dated record, address located exactly | +4 min | 90 min | about 09:51 | no | 1.83 |
| 3 | Elena Brown (C-1163) | 1925 Airport Boulevard, Austin, TX 78722 | last service 2025-11-04, 360 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due since 2026-05-05 (178 days overdue) | **Medium**: interval assumed from the service type | +3 min | 90 min | 11:25-11:30 | no | 1.65 |
| 4 | Priya Taylor (C-1055) | 1201 Webberville Road, Austin, TX 78721 | last service 2026-04-05, 208 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due since 2026-10-04 (26 days overdue) | **Medium**: interval assumed from the service type | +0 min | 90 min | 09:55-11:55 | no | 1.12 |
| 5 | Karen Lewis (C-1198) | 910 Duncan Lane, Austin, TX 78705 | next service date 2026-10-25 (from your list); due since 2026-10-25 (5 days overdue) | **High**: dated record, address located exactly | +9 min | 90 min | 09:55-11:55 | no | 0.72 |

### Slot 15: Fri 30 Oct 2026, Marcus Lee, 14:01-16:44 (2 h 44 min free), Austin 78742

Fit together: only one at a time.

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Sandra Adams (C-1054) | 1600 State Highway 71, Austin, TX 78742 | last service 2025-10-18, 377 days ago; default interval, assumed for 'AC tune-up' = 182 days; due since 2026-04-18 (195 days overdue) | **Low**: interval assumed from the service type; address matched at street level only | +6 min | 90 min | 14:15-15:15 | no | 1.51 |
| 2 | Robert Smith (C-1090) | 2427 Webberville Road, Austin, TX 78702 | last service 2025-12-10, 324 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-06-10 (142 days overdue) | **Medium**: interval assumed from the service type | +10 min | 90 min | 14:15-15:15 | no | 1.08 |
| 3 | Carol Carter (C-1162) | 722 Congress Avenue, Austin, TX 78701 | last service 2026-02-17, 255 days ago; plan 'semi-annual' = every 182 days; due since 2026-08-18 (73 days overdue) | **High**: own plan interval, address located exactly | +11 min | 90 min | 14:20-15:15 | no | 0.80 |
| 4 | Betty Harris (C-1086) | 721 Congress Avenue, Austin, TX 78701 | last service 2025-10-13, 382 days ago; plan 'annual' = every 365 days; due since 2026-10-13 (17 days overdue) | **High**: own plan interval, address located exactly | +11 min | 90 min | 14:20-15:15 | no | 0.60 |

## Draft messages (not sent)

One draft per suggestion, for you to review and send. 

**Slot 2 #1: Donna Lee** ((512) 555-0134 / donna.lee63@example.com)

> Hi Donna, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 27 and has an opening between 10:20 and 11:20. Your water heater flush is due (last visit Mar 5, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #2: Susan Kim** (susan.kim105@example.com)

> Hi Susan, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 27 and has an opening between 09:10 and 10:15. Your water heater flush is due (last visit Dec 9, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #3: Brian Martinez** (brian.martinez81@example.com)

> Hi Brian, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 27 and has an opening between 07:40 and 08:40. Your hvac maintenance is due (last visit Jan 30, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #4: Jennifer Johnson** (jennifer.johnson152@example.com)

> Hi Jennifer, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 27 and has an opening between 07:35 and 09:35. Your ac tune-up is due (last visit May 25, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #5: Jessica Young** (jessica.young59@example.com)

> Hi Jessica, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 27 and has an opening between 07:35 and 09:35. Your furnace check is due (last visit Apr 9, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 3 #1: Michael Roberts** ((512) 555-0129 / michael.roberts55@example.com)

> Hi Michael, this is Lone Star Home Services. One of our technicians will be near Park Central on Tuesday, October 27 and has an opening between 11:40 and 12:05. Your water heater flush is due (last visit Dec 20, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 3 #2: Michael Moore** (michael.moore191@example.com)

> Hi Michael, this is Lone Star Home Services. One of our technicians will be near Park Central on Tuesday, October 27 and has an opening between 13:55 and 14:20. Your ac tune-up is due (last visit Feb 5, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 3 #3: Rosa Taylor** ((512) 555-0169 / rosa.taylor132@example.com)

> Hi Rosa, this is Lone Star Home Services. One of our technicians will be near Park Central on Tuesday, October 27 and has an opening between 12:45 and 13:10. Your water heater flush is due (last visit Sep 15, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 3 #4: Jennifer Harris** (jennifer.harris20@example.com)

> Hi Jennifer, this is Lone Star Home Services. One of our technicians will be near Park Central on Tuesday, October 27 and has an opening between 11:35 and 13:35. We'd be glad to take care of the work from your open quote then. Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 3 #5: Mei Patel** ((512) 555-0118 / mei.patel36@example.com)

> Hi Mei, this is Lone Star Home Services. One of our technicians will be near Park Central on Tuesday, October 27 and has an opening between 11:45 and 13:45. Your hvac maintenance is due (last visit Apr 4, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 4 #1: Jessica Scott** (jessica.scott116@example.com)

> Hi Jessica, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Tuesday, October 27 and has an opening between 13:50 and 15:25. Your furnace check is due (last visit Jan 24, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 4 #2: Lisa Johnson** ((512) 555-0145 / lisa.johnson87@example.com)

> Hi Lisa, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Tuesday, October 27 and has an opening between 10:30 and 12:00. Your hvac maintenance is due (last visit Jan 21, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 4 #3: Elena Harris** (elena.harris180@example.com)

> Hi Elena, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Tuesday, October 27 and has an opening between 12:10 and 13:45. Your hvac maintenance is due (last visit Feb 7, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 4 #4: David Torres** (david.torres24@example.com)

> Hi David, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Tuesday, October 27 and has an opening between 10:35 and 12:35. Your furnace check is due (last visit Dec 29, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 4 #5: Fatima Walker** ((512) 555-0155 / fatima.walker104@example.com)

> Hi Fatima, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Tuesday, October 27 and has an opening between 10:35 and 12:35. Your hvac maintenance is due (last visit Apr 10, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #1: Richard Hall** ((512) 555-0103 / richard.hall5@example.com)

> Hi Richard, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 13:40 and 14:25. Your water heater flush is due (last visit Oct 19, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #2: Robert Adams** (robert.adams98@example.com)

> Hi Robert, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 09:25 and 10:05. Your water heater flush is due (last visit Mar 21, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #3: Jorge Hernandez** ((512) 555-0168 / jorge.hernandez131@example.com)

> Hi Jorge, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 11:30 and 12:15. Your plumbing inspection is due (last visit Oct 18, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #4: Michael Thompson** ((512) 555-0144 / michael.thompson80@example.com)

> Hi Michael, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 07:10 and 07:50. Your electrical safety check is due (last visit Dec 9, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #5: Jessica Smith** (jessica.smith16@example.com)

> Hi Jessica, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 12:35 and 13:15. Your electrical safety check is due (last visit Jun 8, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #6: Anthony Campbell** ((512) 555-0126 / anthony.campbell50@example.com)

> Hi Anthony, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 08:15 and 09:00. We'd be glad to take care of the work from your open quote then. Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #7: Steven Hall** (steven.hall137@example.com)

> Hi Steven, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 10:25 and 11:10. Your water heater flush is due (last visit Sep 9, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 5 #8: Karen Thompson** ((512) 555-0125 / karen.thompson48@example.com)

> Hi Karen, this is Lone Star Home Services. One of our technicians will be near Austin 78702 on Tuesday, October 27 and has an opening between 07:15 and 09:15. Your plumbing inspection is due (last visit Mar 18, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 6 #1: Joshua Brown** (joshua.brown90@example.com)

> Hi Joshua, this is Lone Star Home Services. One of our technicians will be near Stonelake on Wednesday, October 28 and has an opening between 12:55 and 13:10. Your hvac maintenance is due (last visit Oct 7, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 6 #2: Steven Jackson** ((512) 555-0153 / steven.jackson101@example.com)

> Hi Steven, this is Lone Star Home Services. One of our technicians will be near Stonelake on Wednesday, October 28 and has an opening between 14:35 and 14:50. Your water heater flush is due (last visit Jun 17, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 6 #3: Priya Hall** (priya.hall190@example.com)

> Hi Priya, this is Lone Star Home Services. One of our technicians will be near Stonelake on Wednesday, October 28 and has an opening between 13:00 and 14:55. Your water heater flush is due (last visit Jul 1, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 6 #4: Sarah Robinson** ((512) 555-0121 / sarah.robinson42@example.com)

> Hi Sarah, this is Lone Star Home Services. One of our technicians will be near Stonelake on Wednesday, October 28 and has an opening between 12:55 and 14:20. Your ac tune-up is due (last visit Feb 24, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 6 #5: Richard Roberts** ((512) 555-0130 / richard.roberts58@example.com)

> Hi Richard, this is Lone Star Home Services. One of our technicians will be near Stonelake on Wednesday, October 28 and has an opening between 13:00 and 14:50. We'd be glad to take care of the work from your open quote then. Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 7 #1: Mei Hall** (mei.hall0@example.com)

> Hi Mei, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Wednesday, October 28 and has an opening between 13:00 and 13:15. Your furnace check is due (last visit Feb 5, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 7 #2: James Kim** ((512) 555-0167 / james.kim130@example.com)

> Hi James, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Wednesday, October 28 and has an opening between 09:55 and 10:10. Your ac tune-up is due (last visit Nov 7, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 7 #3: Linda Clark** ((512) 555-0141 / linda.clark74@example.com)

> Hi Linda, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Wednesday, October 28 and has an opening between 11:30 and 11:45. Your furnace check is due (last visit Dec 20, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 7 #4: Donna Anderson** (donna.anderson22@example.com)

> Hi Donna, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Wednesday, October 28 and has an opening between 09:55 and 11:55. Your ac tune-up is due (last visit Jan 8, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 7 #5: Carol Hernandez** ((512) 555-0127 / carol.hernandez52@example.com)

> Hi Carol, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Wednesday, October 28 and has an opening between 09:55 and 11:55. Your ac tune-up is due (last visit Apr 28, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 7 #6: Linda Chen** ((512) 555-0100 / linda.chen2@example.com)

> Hi Linda, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Wednesday, October 28 and has an opening between 09:55 and 11:55. Your furnace check is due (last visit Apr 8, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 8 #1: James Scott** ((512) 555-0181 / james.scott153@example.com)

> Hi James, this is Lone Star Home Services. One of our technicians will be near Brodie Oaks on Wednesday, October 28 and has an opening between 15:10 and 15:20. Your ac tune-up is due (last visit Dec 7, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 8 #2: William Jackson** ((512) 555-0123 / william.jackson45@example.com)

> Hi William, this is Lone Star Home Services. One of our technicians will be near Brodie Oaks on Wednesday, October 28 and has an opening at about 15:11. Your ac tune-up is due (last visit Sep 21, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 8 #3: Luis Hernandez** (luis.hernandez69@example.com)

> Hi Luis, this is Lone Star Home Services. One of our technicians will be near Brodie Oaks on Wednesday, October 28 and has an opening between 15:10 and 15:15. Your furnace check is due (last visit Dec 31, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 8 #4: Nancy Patel** ((512) 555-0104 / nancy.patel6@example.com)

> Hi Nancy, this is Lone Star Home Services. One of our technicians will be near Brodie Oaks on Wednesday, October 28 and has an opening at about 15:11. Your ac tune-up is due (last visit Feb 25, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 8 #5: Jessica Torres** (jessica.torres196@example.com)

> Hi Jessica, this is Lone Star Home Services. One of our technicians will be near Brodie Oaks on Wednesday, October 28 and has an opening between 15:10 and 15:15. Your hvac maintenance is due (last visit Apr 29, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 9 #1: Omar Lee** (omar.lee133@example.com)

> Hi Omar, this is Lone Star Home Services. One of our technicians will be near Austin 78741 on Wednesday, October 28 and has an opening between 07:50 and 07:55. Your water heater flush is due (last visit Oct 28, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 9 #2: Rosa Davis** (rosa.davis177@example.com)

> Hi Rosa, this is Lone Star Home Services. One of our technicians will be near Austin 78741 on Wednesday, October 28 and has an opening between 07:45 and 07:50. Your plumbing inspection is due (last visit Mar 7, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 9 #3: Patricia Taylor** ((512) 555-0117 / patricia.taylor35@example.com)

> Hi Patricia, this is Lone Star Home Services. One of our technicians will be near Austin 78741 on Wednesday, October 28 and has an opening between 07:55 and 08:00. Your electrical safety check is due (last visit Oct 18, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 9 #4: Richard Hernandez** (richard.hernandez83@example.com)

> Hi Richard, this is Lone Star Home Services. One of our technicians will be near Austin 78741 on Wednesday, October 28 and has an opening between 07:50 and 08:00. Your electrical safety check is due (last visit Oct 3, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 9 #5: Carol Thomas** (carol.thomas44@example.com)

> Hi Carol, this is Lone Star Home Services. One of our technicians will be near Austin 78741 on Wednesday, October 28 and has an opening at about 07:45. Your plumbing inspection is due (last visit Jan 26, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 10 #1: Steven Rivera** ((512) 555-0177 / steven.rivera146@example.com)

> Hi Steven, this is Lone Star Home Services. One of our technicians will be near Blackland on Thursday, October 29 and has an opening between 09:00 and 09:35. Your plumbing inspection is due (last visit Apr 21, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 10 #2: Susan Perez** ((512) 555-0160 / susan.perez112@example.com)

> Hi Susan, this is Lone Star Home Services. One of our technicians will be near Blackland on Thursday, October 29 and has an opening between 11:35 and 12:10. Your hvac maintenance is due (last visit Oct 12, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 10 #3: Jessica Brown** ((512) 555-0133 / jessica.brown62@example.com)

> Hi Jessica, this is Lone Star Home Services. One of our technicians will be near Blackland on Thursday, October 29 and has an opening between 10:05 and 10:40. Your furnace check is due (last visit Sep 20, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 10 #4: Ana Johnson** (ana.johnson138@example.com)

> Hi Ana, this is Lone Star Home Services. One of our technicians will be near Blackland on Thursday, October 29 and has an opening between 09:00 and 11:00. Your hvac maintenance is due (last visit Nov 6, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 10 #5: Linda Baker** (linda.baker163@example.com)

> Hi Linda, this is Lone Star Home Services. One of our technicians will be near Blackland on Thursday, October 29 and has an opening between 09:00 and 11:00. Your ac tune-up is due (last visit May 2, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 11 #1: Priya Sanchez** (priya.sanchez194@example.com)

> Hi Priya, this is Lone Star Home Services. One of our technicians will be near Austin 78759 on Thursday, October 29 and has an opening between 14:10 and 14:20. Your ac tune-up is due (last visit Mar 5, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 11 #2: Kevin Allen** ((512) 555-0146 / kevin.allen88@example.com)

> Hi Kevin, this is Lone Star Home Services. One of our technicians will be near Austin 78759 on Thursday, October 29 and has an opening between 14:05 and 14:20. Your furnace check is due (last visit Oct 15, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 11 #3: Richard Hernandez** ((512) 555-0162 / richard.hernandez120@example.com)

> Hi Richard, this is Lone Star Home Services. One of our technicians will be near Austin 78759 on Thursday, October 29 and has an opening between 14:05 and 14:20. Your ac tune-up is due (last visit Feb 5, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 11 #4: Betty Wilson** (betty.wilson64@example.com)

> Hi Betty, this is Lone Star Home Services. One of our technicians will be near Austin 78759 on Thursday, October 29 and has an opening between 14:10 and 14:50. Your water heater flush is due (last visit Aug 29, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 11 #5: Wei Thomas** ((512) 555-0142 / wei.thomas76@example.com)

> Hi Wei, this is Lone Star Home Services. One of our technicians will be near Austin 78759 on Thursday, October 29 and has an opening between 14:15 and 14:50. We'd be glad to take care of the work from your open quote then. Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 12 #1: Matthew Young** (matthew.young181@example.com)

> Hi Matthew, this is Lone Star Home Services. One of our technicians will be near Banister Heights on Thursday, October 29 and has an opening between 08:15 and 10:15. Your hvac maintenance is due (last visit Mar 24, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 12 #2: James Brown** ((512) 555-0137 / james.brown70@example.com)

> Hi James, this is Lone Star Home Services. One of our technicians will be near Banister Heights on Thursday, October 29 and has an opening between 12:50 and 14:50. Your furnace check is due (last visit Oct 22, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 12 #3: Carol Roberts** (carol.roberts188@example.com)

> Hi Carol, this is Lone Star Home Services. One of our technicians will be near Banister Heights on Thursday, October 29 and has an opening between 09:45 and 11:45. Your ac tune-up is due (last visit Jan 7, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 12 #4: Donna Davis** (donna.davis167@example.com)

> Hi Donna, this is Lone Star Home Services. One of our technicians will be near Banister Heights on Thursday, October 29 and has an opening between 11:15 and 13:15. Your ac tune-up is due (last visit Mar 2, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #1: Raj Okafor** ((512) 555-0156 / raj.okafor107@example.com)

> Hi Raj, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 08:15 and 09:00. Your plumbing inspection is due (last visit Sep 26, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #2: Luis Perez** (luis.perez13@example.com)

> Hi Luis, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 10:25 and 11:10. Your water heater flush is due (last visit Apr 12, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #3: Thomas Lee** ((512) 555-0110 / thomas.lee21@example.com)

> Hi Thomas, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 09:20 and 10:05. Your plumbing inspection is due (last visit Sep 6, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #4: Anthony Garcia** (anthony.garcia199@example.com)

> Hi Anthony, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 12:35 and 13:20. We'd be glad to take care of the work from your open quote then. Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #5: Carlos Scott** (carlos.scott38@example.com)

> Hi Carlos, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 11:30 and 12:15. Your water heater flush is due (last visit Feb 24, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #6: Brian Sanchez** ((512) 555-0114 / brian.sanchez28@example.com)

> Hi Brian, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 13:35 and 14:20. Your water heater flush is due (last visit Oct 23, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #7: Brian Carter** ((512) 555-0164 / brian.carter123@example.com)

> Hi Brian, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 08:20 and 10:20. Your water heater flush is due (last visit Sep 17, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 13 #8: Lisa Allen** (lisa.allen187@example.com)

> Hi Lisa, this is Lone Star Home Services. One of our technicians will be near Austin 78745 on Thursday, October 29 and has an opening between 08:15 and 10:15. Your water heater flush is due (last visit Sep 1, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 14 #1: Jessica Clark** ((512) 555-0132 / jessica.clark61@example.com)

> Hi Jessica, this is Lone Star Home Services. One of our technicians will be near East Riverside - Oltorf on Friday, October 30 and has an opening between 13:00 and 13:05. Your ac tune-up is due (last visit Nov 2, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 14 #2: Thomas King** (thomas.king136@example.com)

> Hi Thomas, this is Lone Star Home Services. One of our technicians will be near East Riverside - Oltorf on Friday, October 30 and has an opening at about 09:51. Your ac tune-up is due (last visit Sep 12, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 14 #3: Elena Brown** (elena.brown162@example.com)

> Hi Elena, this is Lone Star Home Services. One of our technicians will be near East Riverside - Oltorf on Friday, October 30 and has an opening between 11:25 and 11:30. Your hvac maintenance is due (last visit Nov 4, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 14 #4: Priya Taylor** ((512) 555-0128 / priya.taylor54@example.com)

> Hi Priya, this is Lone Star Home Services. One of our technicians will be near East Riverside - Oltorf on Friday, October 30 and has an opening between 09:55 and 11:55. Your hvac maintenance is due (last visit Apr 5, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 14 #5: Karen Lewis** (karen.lewis197@example.com)

> Hi Karen, this is Lone Star Home Services. One of our technicians will be near East Riverside - Oltorf on Friday, October 30 and has an opening between 09:55 and 11:55. Your hvac maintenance is due (last visit Sep 10, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 15 #1: Sandra Adams** (sandra.adams53@example.com)

> Hi Sandra, this is Lone Star Home Services. One of our technicians will be near Austin 78742 on Friday, October 30 and has an opening between 14:15 and 15:15. Your ac tune-up is due (last visit Oct 18, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 15 #2: Robert Smith** ((512) 555-0147 / robert.smith89@example.com)

> Hi Robert, this is Lone Star Home Services. One of our technicians will be near Austin 78742 on Friday, October 30 and has an opening between 14:15 and 15:15. Your furnace check is due (last visit Dec 10, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 15 #3: Carol Carter** ((512) 555-0189 / carol.carter161@example.com)

> Hi Carol, this is Lone Star Home Services. One of our technicians will be near Austin 78742 on Friday, October 30 and has an opening between 14:20 and 15:15. Your ac tune-up is due (last visit Feb 17, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 15 #4: Betty Harris** (betty.harris85@example.com)

> Hi Betty, this is Lone Star Home Services. One of our technicians will be near Austin 78742 on Friday, October 30 and has an opening between 14:20 and 15:15. Your furnace check is due (last visit Oct 13, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

## Customers not suggested

| Group | Customers | What it means |
|---|---|---|
| Do-not-contact / opted out | 20 row(s) | Removed before anything else; a duplicate of such a customer is removed too (0 row(s)). |
| Not due by 2026-10-30 | 61 | Due date after the plan (next due dates in the spreadsheet export). |
| Due, but no open slot nearby | 9 | Within 15 km of no slot, more than 30 min detour, or the visit does not fit. |
| Due, no crew member with the matching skill | 12 | Service type does not match any crew skill on that day. |
| Location uncertain | 5 | Address not found or matched only to an area: never used for nearby suggestions. Listed below to fix. |
| Unknown: no date, no plan | 19 | Never assumed due. Listed below; add a last service date or plan to include them. |
| Duplicates merged | 3 group(s) | Listed below. |

**Location uncertain (fix these addresses)**

| Customer | Id | Address | Why |
|---|---|---|---|
| Richard Nelson | C-1116 | 6711 Manchaca Road, Austin, TX 78745 | street matched in another postcode (78748, not 78745) |
| Donna Okafor | C-1040 | TBD | no address |
| Jennifer Rivera | C-1130 | Austin TX | matched only an area (Austin) |
| Linda Moore | C-1068 | 4501 Manchaca Road, Austin, TX 78745 | street matched in another postcode (78748, not 78745) |
| Omar Hall | C-1119 | 6300 East US 290 Frontage Road, Austin, TX 78752 | not found on the map |

**Unknown: no service date or plan (consider, not suggested)**

| Customer | Id | Address | Why |
|---|---|---|---|
| Lisa Hernandez | C-1155 | 1221 South MoPac Expressway, Austin, TX 78746 | no last service date, next date, plan or open quote |
| Richard Flores | C-1048 | 1405 East 7th Street, Austin, TX 78702 | no last service date, next date, plan or open quote |
| Amanda Wright | C-1072 | 6105 East US Highway 290, Austin, TX 78723 | no last service date, next date, plan or open quote |
| Linda Perez | C-1184 | 221 West North Loop Boulevard, Austin, TX 78751 | no last service date, next date, plan or open quote |
| Carol Allen | C-1160 | 7800 North Interstate 35, Austin, TX 78752 | no last service date, next date, plan or open quote |
| James King | C-1073 | 1308 West Anderson Lane, Austin, TX 78757 | no last service date, next date, plan or open quote |
| Omar Torres | C-1042 | 2712 Bee Caves Road, Austin, TX 78746 | no last service date, next date, plan or open quote |
| Steven Young | C-1170 | 1320 East 51st Street, Austin, TX 78723 | no last service date, next date, plan or open quote |
| Jorge Green | C-1094 | 9029 Research Boulevard, Austin, TX 78758 | no last service date, next date, plan or open quote |
| Luis Singh | C-1127 | 301 Brazos Street, Austin, TX 78701 | no last service date, next date, plan or open quote |
| Sarah Flores | C-1026 | 805 Nueces Street, Austin, TX 78701 | no last service date, next date, plan or open quote |
| Michael Sanchez | C-1080 | 500 East Saint John's Avenue, Austin, TX 78752 | no last service date, next date, plan or open quote |
| Andrew Flores | C-1151 | 301 West 2nd Street, Austin, TX 78701 | no last service date, next date, plan or open quote |
| Betty Carter | C-1079 | 5204 Ranch to Market Road 2222, Austin, TX 78731 | no last service date, next date, plan or open quote |
| Priya Lewis | C-1145 | 1007 S Congress Ave, Austin, TX 78704 | no last service date, next date, plan or open quote |
| Wei Nelson | C-1183 | 2003 Rutland Drive, Austin, TX 78758 | no last service date, next date, plan or open quote |
| Hiro Campbell | C-1144 | 12062 North Lamar Boulevard, Austin, TX 78753 | no last service date, next date, plan or open quote |
| Michael Singh | C-1179 | 2300 Lake Austin Boulevard, Austin, TX 78703 | no last service date, next date, plan or open quote |
| Hiro Mitchell | C-1129 | 3901 South Lamar Boulevard, Austin, TX 78704 | no last service date, next date, plan or open quote |

**Duplicates merged** (the latest service date is kept; a do-not-contact flag on any row applies to the merged customer)

| Customer | Ids merged | Rows | Why | Service date kept | Do-not-contact |
|---|---|---|---|---|---|
| MATTHEW WHITE | C-1203, C-1013 | 52, 182 | same e-mail | 2026-05-19 | yes (excluded) |
| MICHAEL CARTER | C-1202, C-1012 | 68, 112 | same e-mail | 2026-02-01 | no |
| Jennifer Ramirez | C-1011, C-1201 | 101, 137 | same e-mail | 2026-06-05 | no |

Same address, different names (not merged; check whether they are one household): C-1130 + C-1114 + C-1149; C-1175 + C-1040; C-1187 + C-1192; C-1166 + C-1029; C-1008 + C-1021.

## Data issues

No problems found in the rows that were read.

## Method (what ran)

- **Inputs read**: jobs = week\_plan.xlsx / Jobs; crew = week\_plan.xlsx / Crew; customers = week\_plan.xlsx / Customers.
- **Geocoding**: OpenStreetMap Nominatim (nominatim.openstreetmap.org); 0 lookups this run (results are cached). Addresses matched exactly or to the street are used; area-only or not-found addresses are never used for drive times or suggestions.
- **Drive times**: OSRM (Open Source Routing Machine) public server router.project-osrm.org, car profile, OpenStreetMap road data, matrix fetched 2026-10-19 12:47 UTC to 2026-10-19 13:06 UTC. Free-flow road times without live traffic.
- **Scheduling**: Google OR-Tools vehicle routing (one vehicle per crew member per day) with time windows, skills and working hours, minimising total drive time; every route was then re-simulated independently (earliest start at each stop) and only verified routes are reported.
- **Time windows**: the whole visit must fit inside the window. Working hours: the crew member starts at the start location at the start of the shift and is back by the end.
- **Open slots**: idle blocks of at least 60 min (set 'minimum gap N min' in the brief).
- **Due rule** (in this order): next service date in your list; else last service date + the customer's plan interval; else last service date + the default interval for the service type (assumed, lowers certainty); else an open quote. Due means on or before the slot's date. Customers with no date and no plan are never assumed due.
- **Default intervals used**: ac tune-up 182 days, furnace check 182 days, hvac maintenance 182 days, water heater flush 365 days (change with 'interval: <service type> = N days').
- **Ranking**: score = overdue x proximity x fit. Overdue = 1 + days overdue / interval (credit stops at two intervals or 365 days; open quote 1.25 + age/180). Proximity = 1 / (1 + extra drive minutes / 15). Fit = 1.0 when nothing later moves, 0.85 when later jobs move but stay on time. Candidates: due customers within 15 km (straight line) of the slot's neighbouring stops, nearest 20 per slot, extra drive at most 30 min, at most 5 suggestions per slot (8 for slots of 3 h or more, 10 for 6 h or more), each customer suggested once in the whole plan: slots take turns picking their best remaining candidate, the slot with the fewest candidates first.
- **Certainty**: High = dated next service or the customer's own plan interval and an exact address. Medium = one soft point (interval assumed from the service type, open quote, street-level address, merged duplicates with different dates, skill inferred from the service type). Low = two or more, or more than three intervals overdue.
- **Duplicates**: rows with the same e-mail, the same phone number, the same customer id, or the same name and address are merged.

## Limits and rules

- Drive times are estimates; traffic and delays on the day change them. Same-day changes need a new run.
- Suggestions are only as good as the customer data: missing addresses or service dates limit what can be found.
- Nothing was sent to any customer. This agent has no e-mail, SMS or phone integration; the drafts are for you to review and send.
- Your files were used only for this job and are not kept after delivery (see the listing).
