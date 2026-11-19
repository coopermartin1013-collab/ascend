# ASCEND Personal — free private fitness app

This is the **personal-only** version of ASCEND. There are no Friends tabs, accounts, leaderboards, subscriptions, or cloud services.

## Use immediately
Open `index.html` in a browser to use the workout logger and offline rule-based coach. Your data is stored locally in that browser.

## Install on a phone
Host the contents of this folder on an HTTPS static website (for example GitHub Pages or Cloudflare Pages). Open the hosted URL in Safari on iPhone and use Share > Add to Home Screen, or use Chrome's Install app/Add to Home Screen on Android. Service workers generally require HTTPS or localhost; opening the HTML directly is not the same as installing the PWA.

## Data and backups
Settings > Export JSON backup periodically. Data does not sync between devices. This version retains the `iron_atlas_v1` local storage key from the earlier ASCEND browser app for continuity when used on the same website origin; moving to a new domain will not automatically migrate existing data. Import a backup on the new site to transfer records.

## Future expansion
A later version can add friends, accounts, cloud sync and leaderboards without changing your core training plan.
