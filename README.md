# Crew Sales Calculator — Installable PWA

Installable mobile calculator with offline caching after the first successful online visit.

## Files
- `index.html` — calculator
- `manifest.webmanifest` — install settings
- `sw.js` — offline service worker
- `icons/` — app icons

## Formulas
- Total GC = sum of up to 16 comma-separated GC values
- Sales = AC × Total GC
- Labor = ((Crew Total HR × 68.75) ÷ Sales) × 100
- GCPCH = Total GC ÷ Crew Total HR

Sales is formatted in Philippine pesos (PHP). Crew rate remains 68.75.

## Update GitHub
Upload/replace all files and the `icons` folder in the root of your `SM-Calcu` repository, then commit. Keep the icon files inside the `icons` folder.

Ensure GitHub Pages is enabled for `main` and `/(root)`. HTTPS is required for PWA installation.

## Install on Android
Open the published GitHub Pages URL in Chrome while online, then use the three-dot menu and choose **Install app** or **Add to Home screen**. Offline use is available after the first successful visit and cache setup.
