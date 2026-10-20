# Gogma Roll Scout — phone-friendly web app

## What this is
A local-first prototype for manually recording Gogma Artian weapon rolls and searching recorded skill combinations. It does **not** yet predict unseen rolls from the game's RNG.

## Run locally
Open `index.html` in a browser. For install-to-home-screen support, the app must be hosted over HTTPS (for example, GitHub Pages). Service worker/offline caching works only when served from a supported web origin, not directly from a local file.

## iPhone install
1. Publish these files to an HTTPS static site.
2. Open the published site in Safari.
3. Tap Share → Add to Home Screen.
4. Open it from the new Home Screen icon.

## Data note
Records are stored in browser local storage on that device. Use Export JSON for backups. Browser storage does not automatically sync across devices.
