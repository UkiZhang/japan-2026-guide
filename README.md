# Japan 2026 Family Trip — GitHub Pages Final

Build: 2026-08-09-pages-v3

Upload the **contents of this folder** to the repository root (not the containing folder itself).

Expected root:
- index.html
- day1.html ... day6.html
- sw.js
- manifest.webmanifest
- app-icon.svg
- .nojekyll

GitHub Pages:
Settings → Pages → Deploy from a branch → main → /(root)

Cache strategy:
- HTML/navigation: NETWORK FIRST, then offline cache fallback.
- Static assets: cache first.
- Old caches are deleted when this service worker activates.
