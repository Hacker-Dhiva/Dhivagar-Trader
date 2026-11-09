# Dhivagar Trader V2.0

Black-and-gold local-first trading journal and discipline PWA.

## Features
- Multi-account journal for XAUUSD, NIFTY 50, Forex and Crypto
- Trade editing/deletion, entry, exit, SL, TP, quantity, fees, setup, notes and compressed screenshot attachment
- Dashboard KPIs, cumulative equity curve, win rate, profit factor, average win/loss and best/worst trade
- Monthly P&L, market and strategy analytics; CSV export
- Trading calendar with daily P&L
- Custom habits, daily score, current/best streak and 35-day history
- Manual economic events and configurable best-effort browser reminders
- JSON backup/restore, printable report to PDF, optional convenience PIN
- Offline caching and Android PWA installation

## Deploy into the existing GitHub Pages folder
Replace these seven files inside `Dhivagar-Trader-App/`: `index.html`, `styles.css`, `app.js`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `README.md`. Keep the root-level `index.html` redirect in the repository root. Your app URL remains `https://hacker-dhiva.github.io/Dhivagar-Trader/Dhivagar-Trader-App/`.

## Important limitations
Data is stored in localStorage on this browser/device. Export backups regularly. The PIN is a convenience lock and does not encrypt stored data. Do not store broker passwords or API keys. Economic events are manual; reminders require notification permission and app/browser execution and are not guaranteed when fully closed. Cloud sync, live prices, broker integration and server push notifications require a secure backend and are not included. P&L is manual, not financial advice.
