# Dunamis Bible v4.2 — Final Launch Package

## Files
- `index.html` — production application
- `.nojekyll` — prevents GitHub Pages Jekyll processing

## Deployment
This package is intended for static hosting such as GitHub Pages, Cloudflare Pages, or Netlify.

For GitHub Pages project sites, publish the repository from the Pages settings and use the generated public URL.

## Notes
- The application is primarily self-contained in `index.html`.
- The PWA service-worker registration was adjusted to use the current deployment path instead of assuming the site is hosted at `/`.
- The canonical URL was made relative so it does not claim `https://dunamisbible.app/` before a custom domain is configured.
