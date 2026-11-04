# Snake Battle — Neon Arcade

An original, mobile-first snake arcade game with a neon arena interface.

## Included
- Responsive lobby and nickname profile (saved on this device)
- Solo Survival mode with two bot rivals
- Keyboard, swipe and on-screen touch-pad controls
- Food collection, scoring, coins and locally saved best score
- Eight selectable snake skins with coin unlocks
- Full-screen mobile game view
- Separate Supabase backend project for Snake Battle
- Database tables for private room codes and global score submissions
- Realtime room channel integration for broadcasting player snake positions
- Global leaderboard reads and score submissions

## Important
The online room and leaderboard code has been connected to the separate backend, but it still needs live multi-device testing before being described as fully verified. Realtime rooms currently synchronize player positions through Supabase Realtime; they are not a competitive authoritative game server. Solo mode remains available.

This project is intentionally separate from JALIYAAN SALES. Do not connect it to the JALIYAAN SALES database.

## Netlify deployment
This is a static site:
- Build command: leave blank
- Publish directory: `. ` (use `.` without a space)
- Production branch: `main`

Connect this GitHub repository to the Netlify project `snake-battle-fzgs` to enable automatic production deploys on every push. The repository root contains `netlify.toml`.