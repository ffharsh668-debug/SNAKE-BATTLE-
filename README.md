# Snake Battle — Neon Arcade

An original, mobile-first snake arcade game with a neon arena interface.

## Included in this first build
- Responsive game lobby and nickname profile (saved on this device)
- Playable Solo Survival mode with two bot rivals
- Keyboard, swipe and on-screen touch-pad controls
- Food collection, scoring, coins and locally saved best score
- Eight selectable snake skins with coin unlocks
- Mobile-friendly full-screen game view

## Current limitations — clearly disclosed
Private-room online multiplayer, cross-device accounts, and a global leaderboard are **not live yet**. They need a separate online backend (room signaling, player identity, synchronized game state and persistent ranking). The room UI does not pretend to create working online rooms until that backend is configured. This repository is intentionally separate from JALIYAAN SALES.

## Deploy
This is a static site. Connect this repository to Netlify with:
- Build command: leave blank
- Publish directory: `.`
- Production branch: `main`

No build step or environment variables are needed for the solo game.
