# Simulateur d’achat immobilier / Home buying simulator

A home buying simulator for France, in French and English: maximum budget, PTZ (zero-interest loan), Action Logement loan, month-by-month payments, and a buy-versus-rent comparison.

**Live site:** https://alislayman.github.io/buy-or-rent-real-estate/

## How it works

The whole app is one self-contained file, [`index.html`](index.html). Fonts, styles and scripts are embedded, so the page makes no outside requests. Settings are saved in the browser’s `localStorage`.

To run it locally, open `index.html` in a browser.

## Deployment

The site is served by GitHub Pages from the root of the `main` branch. Every push to `main` republishes it. The empty `.nojekyll` file tells Pages to serve the files as they are, without a Jekyll build.
