# सिरियल किलर – शतक महोत्सवी (१०० वा) प्रयोग · Invitation

Live site: https://serial-killer-invite.vercel.app

## Editing
- Show details (date, time, venue, cast, links): `index.html`, inside `const INVITE = { ... }` near the bottom.
- Auto-advance timings per page: the `AUTO = [...]` line (milliseconds).
- `img/` – logo, emblem, gun poster cut-out, family banner, posters.
- `img/og-v4.jpg` – WhatsApp link-preview picture. WhatsApp caches pictures by file name,
  so if you change it, save it under a NEW name (og-v5.jpg…) and update the 3 `og-v4.jpg` lines in index.html.
- `audio/title-song.mp3` – natak title song, plays from the title page to the end.

Every change committed to `main` is deployed to Vercel automatically.
