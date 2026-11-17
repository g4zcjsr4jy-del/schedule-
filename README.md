# LIFE.OS — Personal Life Management System

A static personal life-management dashboard. Built with HTML, CSS and vanilla JavaScript; no build step or backend is required.

## Features

- Dashboard with time balance, tasks, goals and upcoming events
- Calendar views and schedule matrix / Excel-style view
- Categories, event status, repeat rules and income estimates
- Accounts, transactions, financial goals and built-in calculator
- Analytics and charts
- Themes, typography, scale, currency and timezone settings
- JSON backup/restore, XLSX and CSV exports

## Run locally

Open `index.html` in a modern browser. For best compatibility, use a local static server (for example VS Code Live Server).

## Publish with GitHub Pages

1. Create a GitHub repository and upload the contents of this folder (not the parent folder).
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Wait for the deployment URL to appear in the Pages section.

## Data and privacy

All user data is stored in the current browser using `localStorage`. It is not synchronized between devices and is not sent to a server by this app. Export a JSON backup regularly. Do not commit personal JSON backups to a public repository. Clearing browser site data can erase locally stored records.

## Dependencies

Tailwind CDN, Lucide, Chart.js and SheetJS are loaded from public CDNs. An internet connection is required for these libraries and Google Fonts.

## Notes

This is a client-side personal organizer, not a secure financial service. Do not store bank credentials, card numbers, passwords or other secrets in it.

## License

No license has been selected in this project. Before allowing reuse by others, choose and add a license that matches your intentions.
