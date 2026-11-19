# ASCEND 7.0 — Daily Command Center

Upload `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, and `icon-512.png` into the root of your existing GitHub Pages repository.

## Before upgrading
1. Open your existing installed ASCEND app and export a JSON backup from Settings.
2. Keep the same GitHub Pages URL and installed app. Do not clear Safari/PWA website data.
3. Upload the five files with their exact filenames and commit. Wait for Pages deployment, then reopen the app.

## Dashboard
- Start Workout button opens Workouts and selects the workout chosen in the dashboard dropdown.
- Quick log: morning weight, hours slept, creatine checkbox, calories, and protein.
- Quick log writes to the same nutrition and weight records used by the Nutrition and Progress tabs, preserving other nutrition fields.
- Daily readiness check-in stays available.
- Deep dive shortcuts lead to Nutrition, Progress, Insights, Program, Coach, and PRs.
- Existing training and history features are retained.

## Storage
The existing `iron_atlas_v1` localStorage key is unchanged. Your logs stay local to the installed app/browser; this release has no cloud synchronization. Keep exported backups. No live iPhone browser testing has been performed.
