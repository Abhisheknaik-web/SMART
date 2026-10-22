# Receipt Ledger

Smart receipt-to-expense tracker with anomaly detection. No build step, no dependencies.

## Run
Unzip, then open `index.html` in any browser.

## Files
- `index.html` – the full standalone app
- `embed-snippet.html` – drop-in version for an existing website (styles scoped to `#rl-app`)

## Features
- Paste receipt text: merchant, total, date and category are extracted (editable before saving)
- Anomaly detection: unusually high amounts for a category (median/MAD outliers) and possible duplicate charges (same merchant and amount within 3 days)
- Spending totals by category
- Data is stored in the browser's localStorage (per device, not synced)

## Publish on GitHub Pages
1. Create a new GitHub repo and upload these files.
2. Settings > Pages > deploy from the main branch, root folder.
3. Your app will be live at https://YOUR-USERNAME.github.io/REPO-NAME/
