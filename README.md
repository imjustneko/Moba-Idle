# ⚔️ MobaIdle — MOBA Esports Manager

A browser-based esports manager game, playable on mobile and desktop.

## Play

**GitHub Pages:** https://imjustneko.github.io/Moba-Idle/

## Current build: v1 playable alpha

- Persistent club economy and ELO rating, saved locally
- Train your roster and scout
- Ban/pick draft for Blue and Red teams
- 5v5 animated match observer with lanes, kills and objectives
- Ranked rewards, match history counters and replayable matches

> This is a playable alpha, **not** the full planned V1 Mega Update. Advanced player contracts, scouting market, complete AI pathfinding, original hero portrait assets, realistic jungle and multi-season progression are not yet implemented.

## Deploy

GitHub Actions workflow `.github/workflows/pages.yml` deploys the repository root to GitHub Pages on every push to `main`.

**One-time setup:** GitHub repository → Settings → Pages → Build and deployment → Source: **GitHub Actions**.

## Structure

- `index.html` — browser game
- `.github/workflows/pages.yml` — deployment
- `manifest.webmanifest` — app metadata
- `assets/logo.svg` — project icon

## Note

This is an original prototype inspired by competitive MOBA gameplay. It does not include copyrighted Mobile Legends artwork or branding.
