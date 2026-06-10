# Contractor Project Tracker

A lightweight, single-file HTML project tracker for architecture and construction contractors. No backend, no signup — runs entirely in your browser with data saved to localStorage.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Features

- **KPI dashboard** — total hours, contract value, paid vs owing at a glance
- **Per-project cards** — status badge, progress bar, work log, financials
- **Drawing-level time tracking** — log each Set/drawing with hours, date and activity type
- **Inline editing** — click any hours figure to edit it directly
- **Finance tracking** — contract, deposit, paid, auto-calculated owing
- **Export data** — copy all project data to clipboard for backup or AI sync
- **Persistent** — all data saved in browser localStorage, survives refresh and restart
- **Zero dependencies** — single `index.html` file, works offline

## Usage

1. Download `index.html`
2. Open it in any browser (double-click or drag into Chrome/Safari/Firefox)
3. Replace the demo projects with your own via **Edit details** or **Add project**
4. Use **Log session** to record time spent on each drawing
5. Use **⇑ Export data** to copy your data for backup or to sync with an Excel tracker

## Project Structure

```
index.html    ← entire app in one file (HTML + CSS + JS)
README.md     ← this file
```

## Customising

All demo data lives at the top of the `<script>` block in `index.html` under `const DEMO`. Edit it to pre-populate with your own projects, or just clear it and start fresh in the browser.

## License

MIT — free to use, modify, and share.
