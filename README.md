# Workday Progress

A tiny single-page tracker that shows how much of your workday has passed, live, down to the second.

**Live:** https://vmannusa.github.io/workday-progress/

## What it does

- Shows the current date and time, updated every second.
- Takes a **Start Time** and **End Time** (defaults: 7:00 AM to 4:30 PM).
- Shows the percentage of the workday that has passed (to 3 decimal places) and a progress bar.
- The bar changes color as the day goes on:

| Day passed | Bar color |
| --- | --- |
| 0–25% | Green |
| 25–75% | Yellow |
| 75–100% | Red |

- Starts tracking automatically when the page loads. Change the times and press **Start** to restart with new hours.
- Before the start time it shows 0%; after the end time it stays at 100%.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole app: HTML, CSS and JavaScript in one file, no build step or dependencies. |
| `CHANGELOG.md` | What changed and when. |

## Run it

- **Online:** open the live link above.
- **Locally:** download `index.html` and open it in any browser.
- **Host your own copy:** fork the repo, then **Settings > Pages**, source "Deploy from a branch", branch `main`, folder `/ (root)`.

## Change the default hours

Edit the `value` on the two time inputs in `index.html`:

```html
<input type="time" id="start" value="07:00">
<input type="time" id="end" value="16:30">
```

## Limitations

- Start and end must be on the same day (overnight shifts aren't supported yet).
- Times you type aren't saved; a page refresh goes back to the defaults.

See the [change log](CHANGELOG.md) for history.
