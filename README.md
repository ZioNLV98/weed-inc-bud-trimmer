# Weed INC – Bud Trimmer 3.0

Mobile-friendly static game upload for GitHub Pages.

## Publish
1. Keep `index.html`, `service-worker.js`, and `.nojekyll` in the repository root.
2. In repository Settings → Pages, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then Save.
4. Open the published GitHub Pages URL over HTTPS.

The service worker caches the game shell for subsequent offline launches after the first successful online visit.
