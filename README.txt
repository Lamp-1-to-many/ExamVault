ExamVault GitHub Pages + Android Installable App (PWA) Package
================================================================

Files included:
- index.html     : Main ExamVault web app
- manifest.json  : Android / Chrome Web App Manifest for "Install App"
- sw.js          : Service Worker for offline caching & PWA installability
- icon-192.png   : 192x192 green circle checkmark app icon
- icon-512.png   : 512x512 green circle checkmark app icon

How to deploy on GitHub Pages & install on Android:
1. Upload all 5 files (index.html, manifest.json, sw.js, icon-192.png, icon-512.png)
   to the root of your GitHub repository.
2. Go to Repository Settings -> Pages -> Deploy from your branch (root).
3. Open your GitHub Pages URL in Chrome on Android, tap the 3-dot menu,
   and choose "Install app" / "Add to Home screen".
