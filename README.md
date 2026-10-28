# OJEC — Sales Consultant Tracker

A macOS-styled, single-file web app to track your Sales Consultants' **OJEC** completion and scores, month by month.

Designed & Created by **Kevin Lim Fung Yen**.

## Features

- **SC Roster** — add, edit and remove your sales consultants, assigning each to an outlet (**BYD EV Supreme Batu Pahat** or **BYD EV Supreme Kluang**) and a WhatsApp number.
- **WhatsApp reminders** — any consultant who has **not** completed OJEC this month shows a WhatsApp button that opens a pre-filled reminder message; completed consultants have no WhatsApp option.
- **Monthly Log** — for any month, mark each consultant **completed** with a toggle and enter their **OJEC score**.
- **Dashboard** — see who completed OJEC this month, the completion rate, average score, and a scoreboard ranked by score (pending consultants shown below).
- **Data & Backup** — export all records to `records.csv`, restore from a backup, or reset everything.
- **Light / dark mode** toggle.
- Fully responsive — works on desktop and mobile.

## How it works

- All data lives in your browser's `localStorage` — it never leaves the device and needs no account or server.
- Use **Export CSV** regularly to back up your records, and **Import CSV** to restore them on another device/browser.

## Run locally

Open `ojec-sc-tracker.html` in any modern browser. No build step, no dependencies.

## Stack

- Pure HTML + CSS + vanilla JavaScript — one self-contained file.
- Fonts served self-hosted via the Feishu font mirror (Plus Jakarta Sans).

## Privacy

Everything is stored locally on your own device. Export a CSV backup if you want to keep your data elsewhere.
