# ⚔️ MobaIdle — MOBA Esports Manager

Mobile-friendly, browser-based esports manager game.

## Status: V1 Alpha 2 (not the full V1 Mega Update)

- 20 original fantasy champions with role, attack, defense and colored portrait placeholders
- Blue/Red side choice, 4 hero bans and role-constrained 5v5 picks
- Tactical observer with jungle/river, towers, role-based lane positions, kills, gold, Turtle/Lord events and match speed
- Club economy, training, scouting, roster, persistent ELO and league tiers
- Match results, seasonal ELO reset and localStorage save
- Responsive UI for phones and desktop

**Still missing for full V1:** production-quality illustrated hero portraits, true pathfinding, minion combat, real towers and objective combat, advanced contracts and transfer market, asynchronous PvP server/matchmaking, multiplayer persistence and comprehensive balancing.

## Try it

GitHub Pages (only after deployment is enabled and confirmed):
https://imjustneko.github.io/Moba-Idle/

## GitHub Pages setup

Repository **Settings → Pages → Build and deployment → Source: GitHub Actions**. The workflow at `.github/workflows/pages.yml` deploys on each push to `main`. See the **Actions** tab for run status.

## Files

- `index.html` — app shell
- `styles.css` — responsive esports interface
- `game.js` — club, draft and simulation logic
- `assets/logo.svg` — original SVG icon
- `manifest.webmanifest` — web app metadata
- `.github/workflows/pages.yml` — static site deployment

All art and characters are original placeholders, not licensed game assets.
