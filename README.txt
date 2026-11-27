SCRIPTURE TRACKER — INSTALLATION

This is a small Progressive Web App (PWA) for tracking a first read through the 73-book Catholic Bible.

IMPORTANT:
- It needs to be hosted on an HTTPS website before Android Chrome can install it as an app.
- Progress is stored locally in the browser on the device. It is not synced between devices or browsers.
- Do not clear Chrome site data if you want to keep your progress.
- The included book/chapter plan is a suggested reading sequence, not a liturgical or scholarly chronology. Chapter numbering can vary slightly by edition.

EASIEST FREE HOSTING OPTION: GitHub Pages
1. Sign in to GitHub and create a new public repository, e.g. scripture-tracker.
2. Upload all files from this folder to the repository's root (index.html, manifest.webmanifest, sw.js, icon.svg, icon-192.png, icon-512.png).
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the HTTPS address it gives you in Chrome on your Android phone.
6. In Chrome, tap ⋮ > Add to Home screen (or Install app, if shown).

The app works offline after it has been opened once while online and the service worker has installed.
