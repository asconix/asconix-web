# Asconix Systems website

Static site for GitHub Pages. **No build step, no dependencies, no third-party requests** – keep it that way.

## Files
- `index.html` (English default, Norwegian toggle) · `styles.css` · `script.js` (hero contour animation, EN/NO toggle, compact header, contact form) · `404.html`
- `logo-full.svg`, `logo.svg`, `logo-dark.svg`, `favicon.svg` – copied from `../asconix-ci/logo/`
- `fonts/` – Outfit + Inter, self-hosted · `images/` – Kvile screenshots · `CNAME`, `.nojekyll`

## Corporate identity
Follows `../asconix-ci` (brand guidelines v1.0). Colors are CSS variables at the top of `styles.css`. Amber only in the logo tile. Full logo (with tagline) from 280 px wide, otherwise the plain logo.

## Conventions
- Every text change must be made in **both** languages (EN + NO).
- Don't add external fonts, CDNs, analytics or trackers.
- Updating the logo: copy files from `asconix-ci/logo/` over the local ones (see README mapping).

## Preview
Open `index.html` directly or run `python3 -m http.server` in this folder.
