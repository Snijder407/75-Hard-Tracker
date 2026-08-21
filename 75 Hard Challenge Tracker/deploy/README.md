# 75 HARD Tracker

Personal tracker for the 75 Hard challenge. Static site, no backend — progress is stored in the browser's local storage on each device.

## Publish with GitHub Pages

1. Commit everything in this folder to the root of the repo's `main` branch.
2. Repo → **Settings** → **Pages**.
3. Source: **Deploy from a branch**. Branch: `main`, folder: `/ (root)`. Save.
4. Wait a minute, then open `https://<username>.github.io/75-Hard-Tracker/`.

## Install on iPhone

Open that URL in Safari → Share → **Add to Home Screen**. It launches full screen with the Spartan icon and works offline after the first load.

## Backups

Data lives per browser, so phone and desktop keep separate logs. Use **Export** to save a JSON backup and **Import** to load it on the other device.

## Files

- `index.html` — the app
- `support.js` — runtime it depends on
- `manifest.json`, `sw.js` — install metadata and offline cache
- `assets/` — icons and watermarks
- `.nojekyll` — tells Pages to serve files as-is
