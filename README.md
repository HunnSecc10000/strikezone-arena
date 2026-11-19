# StrikeZone Arena — Cloud Assets

This repository hosts StrikeZone Arena downloadable assets.

## Asset layout
- `guns/` — weapon models
- `characters/` — character models
- `maps/` — map models
- `textures/` — textures
- `manifest.json` — asset index with SHA-256 checksums

## GitHub Pages
After the binary asset folders are uploaded, enable **Settings → Pages → Deploy from a branch → main / root**.

Manifest URL: `https://HunnSecc10000.github.io/strikezone-arena/manifest.json`

## Important
The supplied Godot project does not currently contain a remote asset downloader. Hosting these files alone will not make the game download or use them; downloader integration is a separate required change.
