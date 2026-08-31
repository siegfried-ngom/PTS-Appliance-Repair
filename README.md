# PTS Appliance Repair static site

Pure HTML5, CSS3 and Vanilla JavaScript. No package install is required.

## Build

```bash
node build.js
```

The script generates 174 localized pages (170 home/SEO pages, 2 contact pages and 2 privacy pages), `sitemap.xml`, `robots.txt`, and the shared files under `assets/`.

## Preview

Serve this directory from its root so absolute asset links work:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/en/` or `http://localhost:8000/fr/`.

## Before production

Set the `SITE_URL` environment variable to the final production origin (for example `https://ptsappliancerepair.ca`) and rebuild. If it is omitted, the generator uses `https://domain.com`. Replace sample testimonials with verified customer reviews and confirm the exact warranty/licensing claims with the business.
