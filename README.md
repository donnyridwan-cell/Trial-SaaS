# Trial — Browning Law Firm Dashboard

A pixel-accurate, live implementation of the **Overview** dashboard from the
[Figma design](https://www.figma.com/design/QGQbE5vaHOTX1ZqthSIaAg/Trial---Colin-Melia?node-id=2-20).

Built as a single static page (`index.html`) using Tailwind CSS (browser build) and the
Geist font, with all icons/graphics exported from Figma into `./assets/`.

## Run locally

Any static file server works. For example:

```bash
npx serve .
```

Then open the served URL (the page is `index.html`).

## Live site

This repo auto-deploys to **GitHub Pages** via `.github/workflows/deploy.yml`.
Enable it once under **Settings → Pages → Build and deployment → Source: GitHub Actions**.
