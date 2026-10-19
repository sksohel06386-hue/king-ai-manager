COLOUR SIGNAL ANALYZER v2 — ANDROID SETUP

FILES
- index.html: app interface and statistics logic
- manifest.webmanifest: install metadata
- sw.js: offline cache
- icon.svg: app icon

QUICK TEST
1. Extract this ZIP on your Android phone.
2. Try opening index.html from the file manager. Some browsers restrict local-file app features.
3. For install and offline support, publish all four files together on an HTTPS static host.

GITHUB PAGES
1. Sign in to GitHub and create a public repository, e.g. colour-signal-analyzer.
2. Upload all four files to the repository root, keeping their names unchanged.
3. Open Settings > Pages. Select Deploy from a branch, choose main and /(root), then Save.
4. Wait for the published HTTPS URL. Open it in Chrome on Android.
5. Open Chrome's three-dot menu and choose Install app or Add to Home screen if shown.
6. Add some sample results and test the dashboard. Use Export CSV for a backup.

DATA AND LIMITATIONS
- Results are stored in local browser storage on this device.
- Clearing browser/site data can erase results; export CSV backups.
- This is a website/PWA starter, not a native APK.
- It does not connect to a colour-trading service, place bets, or guarantee predictions.
- Historical frequency and streaks describe past results only.
