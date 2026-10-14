# Vegetable Shop Billing (Vercel-ready)

## Deploy
1. Create a GitHub repository and upload `index.html` and `vercel.json`.
2. Import the repository into Vercel and deploy. No build command is needed.
3. Or deploy the folder with Vercel CLI: `npm i -g vercel`, then run `vercel` inside this folder.

## Features
- Add/update per-kg prices
- Product buttons and search
- Quick 100g, 250g, 500g prices and custom gram weights
- Cart and named client checkout
- CSV exports for bills and line items (opens in Excel)
- JSON backup and restore

## Important storage limitation
This version saves data in the current browser's `localStorage`. It survives normal refreshes and browser restarts, but it is not a server database and will not sync between devices or browsers. Clearing site data, losing the device, or browser storage failure can remove it. Use **Export / Reports → Download full backup (JSON)** regularly. For multi-device/shared and stronger persistence, connect a hosted database such as Supabase/Postgres.
