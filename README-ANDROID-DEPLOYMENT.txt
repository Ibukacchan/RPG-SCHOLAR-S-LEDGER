THE SCHOLAR'S LEDGER — ARCANE ACADEMY PWA
Complete GitHub Pages package
======================================

FILES
- index.html: upgraded single-player RPG application; retains the existing dashboard, Field Study, and Mock Board Prep code.
- academy-character-selection.png: matching fantasy academy character-selection/interface illustration used in Arcane Academy.
- manifest.json, sw.js, icon.svg: installable PWA metadata, offline cache, and app icon.
- data.json: compatibility file for the existing Field Study episode loader. IMPORTANT: the original data.json was not included with the uploaded index.html, so this is an empty compatible placeholder. If you have your original data.json, replace this placeholder with it to restore your episode checklist. Course data and the rest of the planner are retained in index.html.
- index-original-backup.html: backup of the original uploaded HTML. Do not rename this to index.html unless you want to revert.

ANDROID DEPLOYMENT
1. Download and extract this ZIP on your phone (Files app > Downloads > ZIP > Extract).
2. Open your GitHub repository in Chrome. If needed, tap ⋮ > Desktop site.
3. Upload the package files to the repository root (same folder as index.html), replacing the old index.html. Upload all files listed above; keep their filenames exact.
4. Commit changes to the branch/folder configured in Settings > Pages.
5. Wait for the Pages deployment to finish, then open the published URL in Chrome.
6. Test Dashboard, Field Study, Mock Board Prep, and Arcane Academy. In Chrome, use ⋮ > Add to Home screen / Install app.

SAVE SYSTEM
This is a single-player local-browser-save app. No accounts, multiplayer, or leaderboard. Saves remain in the browser storage for this site on this device. They do not automatically sync to other devices or browser profiles. Export a save backup before clearing site data or changing browsers.

PWA NOTE
Service workers and installability require HTTPS; GitHub Pages provides HTTPS. If you have previously installed an older version, reopen the site online and refresh. If it looks stale, uninstall the home-screen shortcut, clear the site's cached data, then revisit and install again.
