# Foot Live — Progressive Web App

## Contents
- `index.html`: responsive trilingual app (Arabic, Italian, English)
- `manifest.webmanifest`: install metadata
- `sw.js`: basic offline cache
- `icon.svg`: app icon

## Run locally
Open `index.html` in a browser. Language switching and category filters work locally.

## Install as an app
For PWA installation and offline caching, serve this folder over HTTPS (or localhost). Service workers do not work from a `file://` URL. Upload the folder contents to a static HTTPS host, then open the URL in Chrome/Edge or Safari and use the browser's Add to Home Screen / Install option.

## Important data note
The match dates and rights descriptions are carried over from the conversation's November 2, 2026 report. They are marked as preliminary and are not live-verified by this app. The app does not fetch or automatically update rights, fixtures, or availability. Verify all details with the linked official broadcasters before relying on them. Official links only; no stream is hosted.
