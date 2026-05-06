# Toronto Marathon Plan — iPhone Home Screen App

This package turns your marathon plan into an iPhone-friendly Home Screen web app.

## Files
- `index.html` — your app
- `manifest.webmanifest` — app metadata
- `service-worker.js` — offline/app-shell caching
- `icons/` — iPhone and PWA icons

## Deploy with GitHub Pages
1. Put all files at the root of your GitHub Pages repository.
2. Make sure the live URL opens `index.html` directly, not GitHub's file preview page.
3. On your iPhone, open the live GitHub Pages URL in Safari.
4. Tap Share.
5. Tap Add to Home Screen.
6. Name it `Marathon`.
7. Launch it from the new Home Screen icon.

Important: iPhone only launches fullscreen/no-address-bar from the Home Screen icon. If you open the same URL inside Safari, GitHub, Chrome, or the GitHub app, it will still look like a webpage.