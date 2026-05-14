# Grading Methodology

## Assessment Overview

Each of the 20 Full Stack Developer submissions was evaluated against the original assessment brief:
> Build a full-stack app (Django + React) that takes trip details as inputs and outputs route instructions and draws ELD logs.

## HOS / ELD Rules Reference

The following FMCSA Hours-of-Service rules were used as the accuracy benchmark (Property carrier, 70 hr / 8 day cycle):

| Rule | Requirement |
|------|-------------|
| **11-Hour Driving Limit** | No more than 11 hours of driving after 10 consecutive hours off duty |
| **14-Hour Window** | Cannot drive beyond the 14th consecutive hour after coming on duty |
| **10-Hour Rest** | Must take 10 consecutive hours off duty before starting a new shift |
| **30-Minute Break** | Must take a 30-minute break after 8 cumulative hours of driving without a qualifying break |
| **70-Hour / 8-Day Cycle** | Cannot drive after accumulating 70 on-duty hours in any 8 consecutive days |
| **Fuel Stops** | At least once every 1,000 miles |
| **Pickup / Dropoff** | 1 hour on-duty (not driving) for each |
| **Multi-day Logs** | Separate daily log sheet for each calendar day of the trip |

## Daily Log Sheet Requirements (per FMCSA)

A valid ELD log must include:
- Date, carrier, driver info
- Truck/trailer numbers
- 24-hour graph grid with correct duty-status lines (Off Duty, Sleeper Berth, Driving, On Duty Not Driving)
- Remarks section with location entries at each status change
- Total hours per duty status
- 70-hr/8-day recap section

## Grading Criteria (1–5 per criterion)

| # | Criterion | What a 5 looks like |
|---|-----------|---------------------|
| 1 | **Accuracy of ELD Drawings** | Correct duty-status lines; proper 11 hr / 14 hr / 30-min break / 10 hr rest representation; correct multi-day sheets |
| 2 | **Other Assessment Criteria** | All 4 required inputs present; map with stops & rests; daily log sheets auto-generated; fuel/pickup/dropoff events reflected |
| 3 | **UI Aesthetics** | Clean, professional design; consistent color/typography; polished components |
| 4 | **UX Intuitiveness** | Form easy to use; results clearly presented; logical flow; helpful labels |
| 5 | **Bugs** | App loads and produces correct output for a sample trip; no visible JS errors; edge cases handled |

**Overall score** = arithmetic mean of the 5 criterion scores, rounded to 1 decimal place.
