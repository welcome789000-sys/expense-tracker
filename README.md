# Expense Tracker

A dashboard for tracking personal expenses, built with vanilla JavaScript.

## Features

- Add expenses with a name, amount, category and date
- Summary cards: total spent this month, number of expenses, biggest expense
- Bar chart of spending per category, drawn by hand on a `<canvas>` (no chart library)
- Filter the list by category, delete entries
- Data is saved in the browser with `localStorage`
- Form validation (name required, amount must be positive, date required)

## What I practiced

- Drawing a bar chart on a `<canvas>` with plain math (no libraries)
- Keeping app state in an array and re-rendering the UI from it
- Form validation and friendly error messages
- Safe DOM building (`textContent` for user input, to avoid injecting HTML)
- `localStorage` persistence with a corrupted-data fallback

## How to run it

Open `index.html` in a browser.

## Notes

A learning project: there is no backend, so data stays in the browser where it was entered. Amounts are shown in Egyptian pounds (EGP).
