# FATHOM STRAIT RUN

A browser-based maritime navigation micro-simulator for Fathom Marine Consultants.

## Current prototype

- Third-person 2.5D Singapore-Strait-inspired scene
- Moving LNG carriers, tankers, bulkers, container ships, ferries, tugs/tows, pilot boats, fishing vessels and car carriers
- Dynamic weather, cloud cover, visibility and sea state
- CPA / TCPA monitoring
- Simplified COLREG coaching and scoring
- TSS-style navigation lane and buoys
- Radar display
- Helm, engine, assess, horn and pause controls
- After-action report

## Play locally

Open `index.html` in a modern browser.

## GitHub Pages deployment

This repository includes a GitHub Pages workflow in `.github/workflows/pages.yml`. Once GitHub Pages is configured to use **GitHub Actions**, pushes to `main` will deploy automatically.

Expected site URL after deployment:

`https://nipunchatrath.github.io/Fathommarineconsultants-Fathom-Strait-Run/`

## Sigma embed

After the Pages site is live, embed it in Sigma using an iframe/custom embed that permits JavaScript:

```html
<iframe
  src="https://nipunchatrath.github.io/Fathommarineconsultants-Fathom-Strait-Run/"
  width="100%"
  height="900"
  style="border:0;border-radius:16px;overflow:hidden"
  allow="fullscreen"
></iframe>
```

## Important

This is a training/game prototype only. COLREG classification, vessel behaviour, CPA logic and environmental effects are simplified and must not be used for actual navigation, passage planning or collision avoidance.
