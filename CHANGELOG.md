# Workday Progress – Change log

## 2026-10-15
- Added this README, change log and an MIT license.

## 2025-05-09
- Tried rolling the end time over to the next day for overnight shifts, then reverted to same-day tracking.

## 2025-05-07
- Default end time set to **4:30 PM** (was 5:30 PM).

## 2025-05-05
- **Live clock:** current date and time shown at the top, updated every second.
- Percentage shown to **3 decimal places** (tried 5 and 4 first).
- Progress bar width uses the same fine-grained percentage so it moves smoothly.

## 2025-05-03
- First version: start/end time inputs, live percentage of the workday passed, and a progress bar that turns green → yellow → red.
- Auto-starts on page load with default hours.
- Default hours changed from 9:00 AM–5:00 PM to **7:00 AM–5:30 PM**.
