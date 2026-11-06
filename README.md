# HomeMap — Apple Maps-inspired, no-key build

This is a free, installable web app for saving property pins and notes.

## Features
- Apple Maps-inspired floating search, map controls, and bottom navigation
- Color-coded property pins (blue, green, yellow, red, purple, gray)
- Categories, property notes, saved-place search, and pin editing/deletion
- Street map and USGS imagery layer; neither is configured with a personal API key
- JSON export/import backups

## Install/update on GitHub Pages
1. Back up your saved pins from HomeMap first using **Backup → Export**.
2. Upload and replace `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` in the repository's published root.
3. Commit the changes and wait for GitHub Pages to publish.
4. Close the old HomeMap tab, reopen the site, and refresh once. The service-worker cache has a new version (`homemap-apple-no-key-v6`).

## Important
Property pins and notes are stored in the browser on that device. They do not automatically sync between devices; export a JSON backup regularly.

Map tiles are provided by CARTO/OpenStreetMap for the street map and USGS for imagery. This is not Apple's proprietary map service or exact Apple Maps interface, and external map providers can change their service availability.
