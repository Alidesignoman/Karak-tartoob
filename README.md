# Karak Tartoob website

Static site (HTML, CSS, JavaScript). No server, database or API keys.

## Publish on GitHub Pages
1. Upload everything in this folder to the **root** of a GitHub repository (so `index.html` is at the top level).
2. Repository **Settings -> Pages -> Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`, then Save.
3. After a minute your site is at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Fill in before sharing (not provided, so not included)
- `index.html`: replace `https://YOUR-USERNAME.github.io/YOUR-REPO/og.png` (the og:image line in `<head>`) with your real address so link previews show the image.
- Customer reviews: none were provided, so there is no reviews section.
- Opening hours: only "closes 12 AM" is known; add the full hours in the Visit section if you have them.
- WhatsApp ordering: not part of the site. Needs a confirmed WhatsApp number.
- Menu prices come from an older menu board photo (OMR). Please confirm they are current.

## Files
- `index.html`, `css/style.css`, `js/main.js`: the site
- `favicon.svg`, `apple-touch-icon.png`, `og.png`: icons and link-preview image
- `.nojekyll`: tells GitHub Pages to serve the files as they are

Fonts (Fraunces, Reem Kufi, Inter) load from Google Fonts; if offline, the page falls back to system fonts.
