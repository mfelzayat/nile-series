# Nile Series — صنّاع القيمة

Public-facing landing page for **Strike Media × Nile Developments — Micro-Drama Season 01**.

- **Live:** https://nile-series.strikestudio.net
- **Brand:** Nile Developments
- **Producer:** Strike Media
- **Series title:** صنّاع القيمة (Sonnaa' Al-Qima — "Value Makers")

## Structure

```
.
├── index.html          # single-page landing
├── nile-logo.png       # primary brand mark
├── og-image.png        # social share card (1200x630)
├── favicon*.png/ico    # full favicon set
├── apple-touch-icon.png
├── android-chrome-*.png
├── site.webmanifest
└── _redirects          # Netlify SPA fallback
```

Edit `index.html` directly — it's a single self-contained HTML file with all
styles inline. Replace `nile-logo.png` to swap the brand mark; the favicons
and OG image will need re-generation if you change it (see `scripts/regen-favicons.sh`).

## Deploy

Pushes to `main` are deployed to Netlify automatically. Manual ZIP deploys
are also supported via the Netlify dashboard.
