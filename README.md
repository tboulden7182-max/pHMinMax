# pH Min/Max Finder (GitHub Pages)

A zero-build React single-page app (CDN React + Tailwind + PapaParse). Just upload to GitHub and enable Pages.

## Quick Deploy (Main branch → GitHub Pages)
1. Create a new GitHub repo (public or private).
2. Add these files (at repo root): `index.html` and `README.md`.
3. Commit & push.
4. In the repo: **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** (or `master`) / **root**
5. Wait for Pages to publish. Your app will be live at the URL GitHub shows.

## Using the app
- Drag & drop / select a `.txt` or `.csv` (comma, tab, pipe, semicolon, or space-delimited).
- Toggle “Header row” if the first line contains column names.
- Pick the pH column (by name or index).
- See **Min**, **Max**, **Mean**, **Count**, plus non‑numeric and out‑of‑range counts.

## Notes
- This version uses CDN links (React/Tailwind/PapaParse) which is fine for GitHub Pages.
- If you need an **all-in-one file** with no CDNs (air‑gapped), use the SharePoint build instead.
