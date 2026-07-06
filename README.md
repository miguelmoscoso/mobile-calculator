# Calculator Mobile Web App

This folder contains an installable Progressive Web App (PWA).

Files:
- `index.html` — calculator
- `manifest.webmanifest` — app name, icon, and display settings
- `service-worker.js` — offline caching
- `icons/` — Home Screen icons

## Test on your Mac

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

Do not test by double-clicking `index.html`; service workers require a web server.

## Publish

Upload every file and folder to an HTTPS static website host such as GitHub Pages.

## Install on iPhone

1. Open the published HTTPS address on the iPhone.
2. Tap the Share button.
3. Tap **Add to Home Screen**.
4. Tap **Add**.
5. Open Calculator from the Home Screen.
