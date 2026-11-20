# Data Table `client_briefs`

All columns are strings unless noted.

| Column | Type | Filled by |
| --- | --- | --- |
| submitted_at | dateTime | Tally |
| response_id | string | Tally |
| industry | string | Tally |
| excluded | boolean | Tally (industry outside focus) |
| name, email, company, website | string | Tally |
| team_size, lead_handler, lead_sources, lead_volume | string | Tally |
| goals, systems, other_crm | string | Tally |
| task_description, process_steps, data_storage | string | Tally |
| interest_solutions, interest_package, timeline | string | Tally |
| contact_language, response_format | string | Tally |
| call_channel, call_contact, call_time | string | Tally |
| referral | string | Tally |
| consent | boolean | Tally |
| lang, page, format, package, readiness | string | Tally hidden fields |
| utm_source, utm_medium, utm_campaign, utm_content | string | Tally hidden fields |
| raw_json | string | Tally (full payload) |
| booking_start | dateTime | Cal.com |
| booking_status | string | Cal.com (`заброньовано` / `перенесено` / `скасовано`: booked / rescheduled / cancelled; edit `map` in Normalize Booking to change) |
| booking_meet_url | string | Cal.com |
| booking_uid | string | Cal.com |

The Google Sheet uses the same names as column headers in row 1. Columns are auto-mapped by name.
