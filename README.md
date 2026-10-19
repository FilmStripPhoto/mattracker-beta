# MatTracker Media beta

A browser-local coverage queue for combat-sports photographers and videographers.

Live beta: https://filmstripphoto.github.io/mattracker-beta/

Start with the sample event and use **Advance demo**. For your own event, go to **Alerts & settings → Start empty event**. Enter athletes and matches manually. Save a JSON backup before clearing browser data or switching devices.

Includes athlete identity confirmation, multiple bouts, queue ordering, estimated conflict flags, manual schedule updates, footage notes, CSV export, and JSON backups.

## Current limits

No live Smoothcomp integration, background push, SMS, accounts, or automatic cross-device sync. An event URL is a reference link only. Alerts occur inside the app when manual/demo updates are made. Data stays in your browser. This beta does not upload photos or videos.

For Saturday testing: open this link on your phone while online, try a manual event, check saving after reload, and export a backup. Verify mat assignments against the event source. Physical-device installation and offline behavior should be tested before relying on them at the event.

## Hosting

Static GitHub Pages site served from the main branch root. No build dependencies. Increase the service-worker cache version when publishing asset changes.
