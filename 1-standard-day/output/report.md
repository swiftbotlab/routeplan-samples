# Route plan and schedule backfill: Tue 20 Oct 2026

## Findings

- **18 of 18 jobs scheduled** on 3 crew-day(s); none unassigned.
- **Total drive time 4 h 00 min**, versus 4 h 47 min if each crew member visited the same jobs in the order of your file (47 min saved, 16%).
- **2 open slot(s) of 45+ min** (4 h 44 min of free time in total).
- **12 backfill suggestion(s)**, ranked per slot, each due for service according to your list, each checked so that every later job still starts inside its window, each with a ready-to-send draft. **Nothing was sent to anyone.**
- Do-not-contact / opted-out: **20 row(s) removed before matching**; none of them appear in the suggestions.
- Note: planning date from the brief: 2026-10-20

## Checks against the acceptance rules

| # | Check | Result | Detail |
|---|---|---|---|
| 1 | Every job is scheduled or listed as unassigned with a reason | PASS | 18 jobs in: 18 scheduled + 0 unassigned |
| 2 | Working hours, time windows and skills respected | PASS | 18 visits checked on 3 crew-days |
| 3 | Drive times from a routing service (named in the report) | PASS | OSRM table API; see Method |
| 4 | Total drive time lower than visiting the jobs in the order given | PASS | 240 min vs 287 min in file order (-47 min) |
| 5 | Every open slot of at least 45 min is listed with crew member, time and area | PASS | 2 slots of 45+ min listed |
| 6 | Adding any suggested customer keeps every later job inside its window | PASS | 12 suggestions re-simulated one by one |
| 7 | Every suggested customer is due according to the data, with the reason | PASS | 12 suggestions, each with its due reason |
| 8 | No do-not-contact / opted-out customer in the suggestions | PASS | 20 do-not-contact/opted-out rows in the list; 0 of them suggested |
| 9 | Every suggestion has a draft; nothing is sent | PASS | 12 drafts written; this agent has no e-mail/SMS/phone integration |

## Schedule by crew member

### Tue 20 Oct 2026

**Dana Ruiz**: hours 07:30-16:00 · skills: hvac; plumbing · 5 job(s) · drive 1 h 01 min · back at the start 15:52

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:30 | | start | 8940 Research Boulevard, Austin, TX 78758 | | | |
| 1 | 07:38 | 09:00 (waits 1 h 22 min) | 10:00 | J-004 (Amanda Hill) | 1205 Sheldon Cove, Austin, TX 78753 | 09:00-11:00 | plumbing | 8 min |
| 2 | 10:09 | 10:09 | 11:09 | J-013 (Betty Torres) | 2512 Wheless Lane, Austin, TX 78723 | 10:00-12:00 | hvac | 9 min |
| 3 | 11:13 | 11:13 | 12:13 | J-012 (Emily Wright) | 5701 Springdale Road, Austin, TX 78723 | any time | plumbing | 4 min |
| 4 | 12:24 | 12:24 | 14:24 | J-015 (Donna Smith) | 700 Lavaca Street, Austin, TX 78701 | 12:00-16:00 | plumbing | 11 min |
| 5 | 14:34 | 14:34 | 15:34 | J-006 (Steven Thompson) | 6100 East Riverside Drive, Austin, TX 78741 | 14:00-16:00 | plumbing | 10 min |
| end | 15:52 | | | back at the start | 8940 Research Boulevard, Austin, TX 78758 | | | 17 min |

**Marcus Lee**: hours 08:00-17:00 · skills: hvac · 5 job(s) · drive 54 min · back at the start 13:38

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 08:00 | | start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | |
| 1 | 08:06 | 08:06 | 09:21 | J-005 (Barbara Mitchell) | 2407 Berkeley Avenue, Austin, TX 78745 | any time | hvac | 6 min |
| 2 | 09:25 | 09:25 | 09:55 | J-011 (Sandra Lee) | 8700 Menchaca Road, Austin, TX 78748 | 08:00-12:00 | hvac | 4 min |
| 3 | 10:11 | 10:11 | 10:56 | J-003 (Donna Moore) | 2021 East Riverside Drive, Austin, TX 78741 | 08:00-12:00 | hvac | 16 min |
| 4 | 11:03 | 11:03 | 11:33 | J-009 (Steven Roberts) | 300 East 4th Street, Austin, TX 78701 | any time | hvac | 7 min |
| 5 | 11:46 | 12:00 (waits 14 min) | 13:30 | J-014 (Fatima Moore) | 1809 Randolph Ridge Trail, Austin, TX 78746 | 12:00-16:00 | hvac | 13 min |
| end | 13:38 | | | back at the start | 1221 West Ben White Boulevard, Austin, TX 78704 | | | 8 min |

**Priya Shah**: hours 07:00-15:30 · skills: plumbing; electrical · 8 job(s) · drive 2 h 05 min · back at the start 15:07

| # | Arrive | Start | Finish | Job | Address | Window | Skill | Drive from previous |
|---|---|---|---|---|---|---|---|---|
| 0 | | 07:00 | | start | 1138 Airport Boulevard, Austin, TX 78702 | | | |
| 1 | 07:08 | 07:08 | 08:08 | J-007 (Andrew Johnson) | 500 East Saint John's Avenue, Austin, TX 78752 | any time | plumbing | 8 min |
| 2 | 08:16 | 08:16 | 09:01 | J-016 (Joseph Carter) | 11705 North Lamar Boulevard, Austin, TX 78753 | 08:00-12:00 | plumbing | 8 min |
| 3 | 09:17 | 09:17 | 10:02 | J-001 (Kevin Anderson) | 10902 Windridge Drive, Austin, TX 78759 (street-level location) | 08:00-12:00 | plumbing | 16 min |
| 4 | 10:22 | 10:22 | 11:07 | J-002 (Omar Okafor) | 2712 Bee Caves Road, Austin, TX 78746 | any time | plumbing | 20 min |
| 5 | 11:25 | 11:25 | 12:10 | J-018 (Sandra Rivera) | 1020 Grove Boulevard, Austin, TX 78741 | any time | plumbing | 17 min |
| 6 | 12:21 | 12:21 | 12:51 | J-008 (Jorge White) | 4600 Teri Road, Austin, TX 78744 | 12:00-16:00 | electrical | 11 min |
| 7 | 12:57 | 13:00 (waits 2 min) | 14:00 | J-017 (Jorge Martinez) | 111 West William Cannon Drive, Austin, TX 78745 | 13:00-15:00 | plumbing | 7 min |
| 8 | 14:22 | 14:22 | 14:52 | J-010 (Jessica Carter) | 1005 Kramer Lane, Austin, TX 78758 | 14:00-16:00 | electrical | 23 min |
| end | 15:07 | | | back at the start | 1138 Airport Boulevard, Austin, TX 78702 | | | 15 min |

## Unassigned jobs

None: every job is in the schedule.

## Drive time: plan versus the order in your file

Baseline: each crew member visits the same jobs in the order they appear in your jobs file, leaving at the start of the shift.

| Day | Crew member | Jobs | Planned drive | File-order drive | File order on time? |
|---|---|---|---|---|---|
| Tue 20 Oct 2026 | Dana Ruiz | 5 | 1 h 01 min | 1 h 19 min | no: 3 late job(s), 5 h 02 min overtime |
| Tue 20 Oct 2026 | Marcus Lee | 5 | 54 min | 1 h 08 min | no: 2 late job(s), 30 min overtime |
| Tue 20 Oct 2026 | Priya Shah | 8 | 2 h 05 min | 2 h 20 min | no: 4 late job(s), 6 h 36 min overtime |
| **Total** | | 18 | **4 h 00 min** | **4 h 47 min** | |

## Open slots (45+ min)

| Slot | Day | Crew member | Free | From | To | Area (between) | Suggestions |
|---|---|---|---|---|---|---|---|
| 1 | Tue 20 Oct 2026 | Dana Ruiz | 1 h 22 min | 07:30 | 08:51 | Wooten, Austin 78758 to Austin 78753 (between start (8940 Research Boulevard, Austin, TX 78758) and job J-004 (1205 Sheldon Cove, Austin, TX 78753)) | 4 |
| 2 | Tue 20 Oct 2026 | Marcus Lee | 3 h 22 min | 13:30 | 16:52 | Austin 78746 (between job J-014 (1809 Randolph Ridge Trail, Austin, TX 78746) and end of day back at the start) | 8 |

A slot is idle time in the crew member's day: from the end of one stop until they must leave for the next one (or until the end of working hours, including the drive back).

## Backfill suggestions

Ranked per slot by **score = overdue x proximity x fit** (formula under *Method*). Each one was inserted into the crew member's day on its own and the whole day re-checked: every later job still starts inside its window and the crew member still finishes inside working hours. *Fit together* lists the ranks that were also checked as one set.

### Slot 1: Tue 20 Oct 2026, Dana Ruiz, 07:30-08:51 (1 h 22 min free), Wooten, Austin 78758 to Austin 78753

Fit together: only one at a time.

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Daniel Sanchez (C-1004) | 8565 Research Boulevard, Austin, TX 78758 | next service date 2026-09-19 (from your list); due since 2026-09-19 (31 days overdue) | **High**: dated record, address located exactly | +3 min | 60 min | 07:35-07:55 | no | 1.69 |
| 2 | Kevin Nelson (C-1187) | 9602 Gray Boulevard, Austin, TX 78758 | open quote (service itself next due 2027-07-19) | **Medium**: open quote, not a scheduled service | +10 min | 60 min | 07:40-07:55 | no | 0.76 |
| 3 | Raj White (C-1195) | 9820 Neils Thompson Drive, Austin, TX 78758 | next service date 2026-10-11 (from your list); due since 2026-10-11 (9 days overdue) | **High**: dated record, address located exactly | +11 min | 60 min | 07:40-07:50 | no | 0.76 |
| 4 | Jessica Flores (C-1133) | 2207 Justin Lane, Austin, TX 78757 | last service 2025-09-18, 397 days ago; default interval, assumed for 'Plumbing inspection' = 365 days; due since 2026-09-18 (32 days overdue) | **Medium**: interval assumed from the service type | +9 min | 60 min | 07:40-07:55 | no | 0.69 |

### Slot 2: Tue 20 Oct 2026, Marcus Lee, 13:30-16:52 (3 h 22 min free), Austin 78746

Fit together: #1, #2 (checked as one set; their arrival times below assume all of them are booked).

| Rank | Customer | Address | Why due | Certainty | Extra drive | Visit | Arrive between | Later jobs move | Score |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Carol Anderson (C-1032) | 3901 South Lamar Boulevard, Austin, TX 78704 | last service 2025-12-23, 301 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-06-23 (119 days overdue) | **Medium**: interval assumed from the service type | +3 min | 90 min | 13:40-13:45 | no | 1.41 |
| 2 | Linda Johnson (C-1067) | 3924 Woodbury Drive, Austin, TX 78704 | last service 2025-11-16, 338 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due since 2026-05-17 (156 days overdue) | **Medium**: interval assumed from the service type | +6 min | 90 min | 15:15-15:25 | no | 1.34 |
| 3 | Susan Mitchell (C-1182) | 200 West 24th Street, Austin, TX 78705 | last service 2025-11-16, 338 days ago; plan 'quarterly' = every 91 days; due since 2026-02-15 (247 days overdue) | **High**: own plan interval, address located exactly | +21 min | 90 min | 13:45-15:10 | no | 1.26 |
| 4 | Sarah Hernandez (C-1138) | 2301 Trinity Street, Austin, TX 78712 | last service 2025-09-17, 398 days ago; plan '90 days' = every 90 days; due since 2025-12-16 (308 days overdue) | **Low**: overdue more than 3 intervals (may no longer be a customer) | +22 min | 90 min | 13:50-15:10 | no | 1.21 |
| 5 | Betty Carter (C-1003) | 111 Congress Ave., Austin, TX 78701 | last service 2025-10-17, 368 days ago; default interval, assumed for 'Furnace check' = 182 days; due since 2026-04-17 (186 days overdue) | **Medium**: interval assumed from the service type | +14 min | 90 min | 13:45-15:15 | no | 1.03 |
| 6 | William Rivera (C-1163) | 205 West 24th Street, Austin, TX 78705 | next service date 2026-09-12 (from your list); due since 2026-09-12 (38 days overdue) | **High**: dated record, address located exactly | +20 min | 90 min | 13:45-15:10 | no | 0.98 |
| 7 | Robert Lewis (C-1136) | 127 East Riverside Drive, Austin, TX 78704 | last service 2025-11-29, 325 days ago; plan 'semi-annual' = every 182 days; due since 2026-05-30 (143 days overdue) | **High**: own plan interval, address located exactly | +13 min | 90 min | 13:45-15:20 | no | 0.97 |
| 8 | Amanda Roberts (C-1109) | 1607 San Jacinto Boulevard, Austin, TX 78701 | last service 2025-10-16, 369 days ago; default interval, assumed for 'HVAC maintenance' = 182 days; due since 2026-04-16 (187 days overdue) | **Medium**: interval assumed from the service type | +17 min | 90 min | 13:45-15:15 | no | 0.95 |

## Draft messages (not sent)

One draft per suggestion, for you to review and send. 

**Slot 1 #1: Daniel Sanchez** ((512) 555-0101 / daniel.sanchez3@example.com)

> Hi Daniel, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 20 and has an opening between 07:35 and 07:55. Your water heater flush is due (last visit Nov 14, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 1 #2: Kevin Nelson** (kevin.nelson186@example.com)

> Hi Kevin, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 20 and has an opening between 07:40 and 07:55. We'd be glad to take care of the work from your open quote then. Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 1 #3: Raj White** (raj.white194@example.com)

> Hi Raj, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 20 and has an opening between 07:40 and 07:50. Your water heater flush is due (last visit Nov 22, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 1 #4: Jessica Flores** (jessica.flores132@example.com)

> Hi Jessica, this is Lone Star Home Services. One of our technicians will be near Wooten on Tuesday, October 20 and has an opening between 07:40 and 07:55. Your plumbing inspection is due (last visit Sep 18, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #1: Carol Anderson** (carol.anderson31@example.com)

> Hi Carol, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 13:40 and 13:45. Your furnace check is due (last visit Dec 23, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #2: Linda Johnson** (linda.johnson66@example.com)

> Hi Linda, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 15:15 and 15:25. Your hvac maintenance is due (last visit Nov 16, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #3: Susan Mitchell** (susan.mitchell181@example.com)

> Hi Susan, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 13:45 and 15:10. Your hvac maintenance is due (last visit Nov 16, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #4: Sarah Hernandez** (sarah.hernandez137@example.com)

> Hi Sarah, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 13:50 and 15:10. Your ac tune-up is due (last visit Sep 17, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #5: Betty Carter** ((512) 555-0100 / betty.carter2@example.com)

> Hi Betty, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 13:45 and 15:15. Your furnace check is due (last visit Oct 17, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #6: William Rivera** ((512) 555-0189 / william.rivera162@example.com)

> Hi William, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 13:45 and 15:10. Your ac tune-up is due (last visit Aug 14, 2026). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #7: Robert Lewis** ((512) 555-0174 / robert.lewis135@example.com)

> Hi Robert, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 13:45 and 15:20. Your hvac maintenance is due (last visit Nov 29, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

**Slot 2 #8: Amanda Roberts** (amanda.roberts108@example.com)

> Hi Amanda, this is Lone Star Home Services. One of our technicians will be near Austin 78746 on Tuesday, October 20 and has an opening between 13:45 and 15:15. Your hvac maintenance is due (last visit Oct 16, 2025). Would you like us to stop by? Just reply YES to book or call (512) 555-0199, or let us know a better time. Reply STOP to opt out.

## Customers not suggested

| Group | Customers | What it means |
|---|---|---|
| Do-not-contact / opted out | 20 row(s) | Removed before anything else; a duplicate of such a customer is removed too (0 row(s)). |
| Not due by 2026-10-20 | 67 | Due date after the plan (next due dates in the spreadsheet export). |
| Due, but no open slot nearby | 58 | Within 15 km of no slot, more than 30 min detour, or the visit does not fit. |
| Due, no crew member with the matching skill | 19 | Service type does not match any crew skill on that day. |
| Location uncertain | 7 | Address not found or matched only to an area: never used for nearby suggestions. Listed below to fix. |
| Unknown: no date, no plan | 19 | Never assumed due. Listed below; add a last service date or plan to include them. |
| Duplicates merged | 3 group(s) | Listed below. |

**Location uncertain (fix these addresses)**

| Customer | Id | Address | Why |
|---|---|---|---|
| Kevin Davis | C-1076 | 6300 East US 290 Frontage Road, Austin, TX 78752 | not found on the map |
| Jorge Scott | C-1191 | PO Box 233 | placed 1415 km away (Sherwood Forest, Maryville 37802) |
| Anthony Lee | C-1188 | 2501 West Parmer Lane, Austin, TX 78727 | not found on the map |
| Mark Lopez | C-1125 | Austin TX | matched only an area (Austin) |
| Rosa Carter | C-1143 | 2514 West Parmer Lane, Austin, TX 78727 | not found on the map |
| Jorge Green | C-1025 | TBD | no address |
| Richard Rivera | C-1121 | 6711 Manchaca Road, Austin, TX 78745 | street matched in another postcode (78748, not 78745) |

**Unknown: no service date or plan (consider, not suggested)**

| Customer | Id | Address | Why |
|---|---|---|---|
| Emily Baker | C-1017 | 900 West 38th Street, Austin, TX 78705 | no last service date, next date, plan or open quote |
| Carlos Allen | C-1031 | 1023 Springdale Road, Austin, TX 78721 | no last service date, next date, plan or open quote |
| Jennifer Adams | C-1123 | 2208 Energy Drive, Austin, TX 78758 | no last service date, next date, plan or open quote |
| Rosa Torres | C-1157 | 4601 North Lamar Boulevard, Austin, TX 78751 | no last service date, next date, plan or open quote |
| Priya Chen | C-1114 | PO Box 808 | no last service date, next date, plan or open quote |
| Barbara Hall | C-1007 | 7201 Wood Hollow Drive, Austin, TX 78731 | no last service date, next date, plan or open quote |
| Emily Nguyen | C-1184 | 507 Pressler Street, Austin, TX 78703 | no last service date, next date, plan or open quote |
| Rosa Roberts | C-1120 | PO Box 893 | no last service date, next date, plan or open quote |
| Jorge Anderson | C-1146 | 12419 Metric Boulevard, Austin, TX 78758 | no last service date, next date, plan or open quote |
| William Young | C-1075 | 4225 Guadalupe Street, Austin, TX 78751 | no last service date, next date, plan or open quote |
| Thomas Carter | C-1094 | 642 Calles Street, Austin, TX 78702 | no last service date, next date, plan or open quote |
| Betty Clark | C-1096 | 9709 Brown Lane, Austin, TX 78754 | no last service date, next date, plan or open quote |
| Jorge Garcia | C-1181 | 3120 Kramer Lane, Austin, TX 78758 | no last service date, next date, plan or open quote |
| Nancy Smith | C-1166 | 500 West Canyon Ridge Drive, Austin, TX 78753 | no last service date, next date, plan or open quote |
| Brian Sanchez | C-1139 | 1901 East Martin Luther King Jr Boulevard, Austin, TX 78702 | no last service date, next date, plan or open quote |
| Hiro Walker | C-1099 | 2700 South Lamar Boulevard, Austin, TX 78704 | no last service date, next date, plan or open quote |
| Karen Singh | C-1002 | 522 Congress Avenue, Austin, TX 78701 | no last service date, next date, plan or open quote |
| Joseph Adams | C-1038 | 9705 Burnet Road, Austin, TX 78758 | no last service date, next date, plan or open quote |
| Hiro Thomas | C-1124 | 901 West Braker Lane, Austin, TX 78753 | no last service date, next date, plan or open quote |

**Duplicates merged** (the latest service date is kept; a do-not-contact flag on any row applies to the merged customer)

| Customer | Ids merged | Rows | Why | Service date kept | Do-not-contact |
|---|---|---|---|---|---|
| Anthony Allen | C-1011, C-1201 | 5, 108 | same e-mail | 2025-10-18 | yes (excluded) |
| Priya Kim | C-1012, C-1202 | 85, 159 | same e-mail | 2026-08-12 | yes (excluded) |
| JORGE WILSON | C-1203, C-1013 | 98, 191 | same e-mail | 2025-10-27 | no |

Same address, different names (not merged; check whether they are one household): C-1005 + C-1039 + C-1025 + C-1172; C-1197 + C-1125 + C-1158.

## Data issues

No problems found in the rows that were read.

## Method (what ran)

- **Inputs read**: jobs = jobs.csv; crew = crew.csv; customers = customers.csv.
- **Geocoding**: OpenStreetMap Nominatim (nominatim.openstreetmap.org); 0 lookups this run (results are cached). Addresses matched exactly or to the street are used; area-only or not-found addresses are never used for drive times or suggestions.
- **Drive times**: OSRM (Open Source Routing Machine) public server router.project-osrm.org, car profile, OpenStreetMap road data, matrix fetched 2026-10-19 12:40 UTC to 2026-10-19 13:07 UTC. Free-flow road times without live traffic.
- **Scheduling**: Google OR-Tools vehicle routing (one vehicle per crew member per day) with time windows, skills and working hours, minimising total drive time; every route was then re-simulated independently (earliest start at each stop) and only verified routes are reported.
- **Time windows**: the whole visit must fit inside the window. Working hours: the crew member starts at the start location at the start of the shift and is back by the end.
- **Open slots**: idle blocks of at least 45 min (set 'minimum gap N min' in the brief).
- **Due rule** (in this order): next service date in your list; else last service date + the customer's plan interval; else last service date + the default interval for the service type (assumed, lowers certainty); else an open quote. Due means on or before the slot's date. Customers with no date and no plan are never assumed due.
- **Default intervals used**: furnace check 182 days, hvac maintenance 182 days, plumbing inspection 365 days (change with 'interval: <service type> = N days').
- **Ranking**: score = overdue x proximity x fit. Overdue = 1 + days overdue / interval (credit stops at two intervals or 365 days; open quote 1.25 + age/180). Proximity = 1 / (1 + extra drive minutes / 15). Fit = 1.0 when nothing later moves, 0.85 when later jobs move but stay on time. Candidates: due customers within 15 km (straight line) of the slot's neighbouring stops, nearest 20 per slot, extra drive at most 30 min, at most 5 suggestions per slot (8 for slots of 3 h or more, 10 for 6 h or more), each customer suggested once in the whole plan: slots take turns picking their best remaining candidate, the slot with the fewest candidates first.
- **Certainty**: High = dated next service or the customer's own plan interval and an exact address. Medium = one soft point (interval assumed from the service type, open quote, street-level address, merged duplicates with different dates, skill inferred from the service type). Low = two or more, or more than three intervals overdue.
- **Duplicates**: rows with the same e-mail, the same phone number, the same customer id, or the same name and address are merged.

## Limits and rules

- Drive times are estimates; traffic and delays on the day change them. Same-day changes need a new run.
- Suggestions are only as good as the customer data: missing addresses or service dates limit what can be found.
- Nothing was sent to any customer. This agent has no e-mail, SMS or phone integration; the drafts are for you to review and send.
- Your files were used only for this job and are not kept after delivery (see the listing).
