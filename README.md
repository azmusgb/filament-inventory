# Filament Inventory

Mobile-first, local-first 3D printer filament inventory dashboard.

## Features

- Photo-audited 21-spool starter inventory
- Brand, material/type, color, confidence, location and spool-format tracking
- Conservative visual estimates: unknown levels remain unknown
- Gross/tare weighing workflow that supersedes visual estimates
- Automatic remaining grams, percentage and stock status
- Search and filters
- Add, edit and delete spools
- JSON backup/import
- CSV export for Google Sheets, Excel and future Spoolman migration
- Browser-local persistence
- Installable PWA/offline cache
- Zero-build static deployment for Netlify

## Run locally

Serve the repository with any static web server. For example:

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Storage

Inventory edits are stored in the browser's `localStorage`. Use **Data → Export JSON** for portable backups. Clearing browser/site data will remove local inventory unless it has been exported.

## Deployment

The project is a zero-build static site. `netlify.toml` publishes the repository root.
