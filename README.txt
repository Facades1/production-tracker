
# Production Tracker (Static HTML + DataTables)

How to use:

1. Open `index.html` in a browser to test locally.
2. Put your real data in `data/data.csv` (same headers).
3. Free hosting:
   - **GitHub Pages**: create a repo, upload files, Settings → Pages → Deploy from a branch.
   - **Netlify**: drag-and-drop the folder to Netlify dashboard.

Notes
- Top filters: Date (exact), Zone (regex), Scope (regex), PI NO (regex). Batch Qty / Actual Qty / HO Qty use ">= value" logic.
- Export buttons (copy, CSV, Excel, print) are enabled via DataTables Buttons extension CDN.
