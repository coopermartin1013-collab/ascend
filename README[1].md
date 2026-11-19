# ASCEND v4 — Personal edition

## Upgrade your existing GitHub Pages app

1. In ASCEND on your iPhone, open Settings and export a JSON backup first.
2. In your GitHub `ascend` repository, upload the **five files inside this folder**, directly to the repository root. Replace existing files when asked. The names must be exactly `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` (no `[1]` suffix).
3. Commit the changes to `main` and wait for the green Pages deployment checkmark.
4. Reopen your installed ASCEND app on iPhone. If the old version remains, close and reopen it; if necessary, open the site in Safari and refresh.
5. Check the **Insights** tab and the rest timer in **Workouts**.

## Data safety

This version uses the same `iron_atlas_v1` localStorage key as the previous personal app. Updating files at the same GitHub Pages origin should preserve logs. Do not clear Safari website data, and export JSON backups regularly. The app is still local-only, with no accounts, cloud synchronization, or paid AI.

## New in v4

- Rest timer with 90-second, 2-minute and 3-minute presets; timer deadline survives page refresh.
- Insights tab: 7-day workout frequency, volume, nutrition averages, coaching suggestions.
- Exercise-specific estimated strength trend charts.
- Copyable coaching report for detailed review in ChatGPT.
- Mobile-friendly navigation and input sizing.
- Real PWA manifest and service worker included.
