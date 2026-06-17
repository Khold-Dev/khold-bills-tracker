# Khold Bills Tracker

<p align="center">
  <img src="./kholdicon.png" alt="Khold Bills Tracker icon" width="128" height="128">
</p>

<p align="center">
  A lightweight, single-file monthly bills tracker for recurring bills, income,
  one-time expenses, and leftover balance.
</p>

## What It Does

- Tracks recurring monthly bills with due-date badges.
- Marks recurring bills as original, past due, or paid.
- Tracks income entries, including hourly pay estimates.
- Tracks one-time or irregular monthly expenses.
- Calculates recurring totals, paid totals, remaining bills, income total, grand total, and leftover balance.
- Saves your current month locally in the browser with `localStorage`.
- Includes print and reset actions for quick monthly use.

## Quick Start

No build step or install is required.

1. Clone or download the repo and Open `index.html` in a browser.
2. OR visit https://khold-dev.github.io/khold-bills-tracker/
3. Edit the month, bills, income, and one-time items directly on the page.

Your changes are saved in your browser automatically.

## Files

```text
.
|-- index.html      # Full bills tracker app
|-- kholdicon.png   # Project icon used by the README
`-- README.md       # Project notes
```

## Notes

- Data is stored locally in the browser, not synced to a server.
- Clearing site data or using another browser may remove saved entries.
- Hourly income estimates use the app's built-in calculation logic from `index.html`.

## License

No license has been added yet.
