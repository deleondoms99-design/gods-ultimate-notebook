# GODS — The Digital Notebook

A mobile-friendly, offline-capable personal notebook and planner.

## Features
- Daily pages, dated notes, and mood tracking
- To-do lists and task deadlines
- Calendar, habits, goals, and ideas
- Binder-style sections and custom dividers
- Local browser storage
- JSON export/import for backups
- Responsive layout for phones and tablets
- PWA manifest, app icons, and service worker for offline use

## Publish with GitHub Pages
1. Create a **Public** GitHub repository.
2. Upload the contents of this ZIP to the repository's **root** (not the ZIP file itself).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish your site.

Your site address will look like:
`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Install on Android
1. Open the published HTTPS address in Chrome.
2. Allow the page to finish loading while online.
3. Use Chrome's menu and choose **Install app** or **Add to Home screen** if offered.

## Privacy and backups
Notebook entries are stored in the browser on the device using local storage. They are not automatically synced to GitHub. Use the app's export feature to make backups, and keep exported files private.

## Project files
- `index.html` — the notebook app
- `manifest.json` — installable app metadata
- `sw.js` — offline app-shell caching
- `icons/` — app icons
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing
