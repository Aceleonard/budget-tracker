# Ace's Route to Debt-Free — Budget Tracker

A single-file budget tracker. No build step, no npm install, no server required.

## How to open it

**Easiest:** double-click `budget-tracker.html`, it opens in your default browser and works fully.

**In VS Code:**
1. Open this folder in VS Code (`File > Open Folder...`).
2. Right-click `budget-tracker.html` in the file explorer.
3. Choose **"Open with Live Server"** (install the free "Live Server" extension by Ritwick Dey if you don't have it) — this gives you auto-reload if you ever edit the code yourself.
   - Or just click **"Reveal in File Explorer / Finder"** and double-click the file to open it directly in a browser, no extension needed.

## What it needs

- **A modern browser** (Chrome, Edge, Safari, Firefox). No installs, no dependencies to manage.
- **Internet connection**, only for two things:
  - Loading fonts and the charting library the first time (from Google Fonts / cdnjs).
  - Fetching live exchange rates if you switch currencies in Settings.
  Everything else (adding entries, editing amounts, marking things paid, etc.) works fully offline once the page has loaded.

## Where your data lives

Everything you enter is saved in your browser's local storage, tied to this specific file and browser. That means:

- Your data is **not** synced anywhere or sent to any server, it stays on your machine.
- If you open the file in a different browser (or a different browser profile), you'll see a blank slate, since local storage doesn't carry across browsers.
- Clearing your browser's site data/cache for this file will erase your tracker. Use **Settings → Export to Excel** every so often if you want a backup outside the browser.
- The file starts completely blank (income, costs, debts, everything at zero) — fill in your real numbers under the **Settings**, **Debt Tracker**, and **Monthly Log** tabs to get going.

## Tabs at a glance

- **🏠 Dashboard** — income breakdown, spending insights, and your route to debt-free.
- **📒 Monthly Log** — log each month's bills, mark them Paid/Pending, log day-to-day expenses.
- **💳 Debt Tracker** — track loans/commitments, mark monthly payments, see payoff estimates.
- **📈 Savings** — track savings vs. target, emergency fund progress.
- **🎯 Goals** — separate savings goals (trips, gadgets, anything).
- **⚙️ Settings** — income, fixed costs, currency, manage months, export, reset.

Enjoy, and good luck with the budget.
