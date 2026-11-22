# WINK AT ME

A responsive SEIUN mini rhythm game in `games/winkatme/`.

## Current prototype
- Story cutscene: album-shopping day, silent CD, sleepy notes, rescue mission
- Three original inline-SVG chibi member illustrations: Hyejin (long straight hair), Yennie (long pigtails), Suji (short hair); brown hair and brown eyes, sailor-inspired outfits
- Member selection and demo soundtrack selection
- Rhythm notes, touch buttons, keyboard 1–4, timing feedback, score and combo
- Responsive layout for mobile, tablet and desktop
- English, Korean, Japanese and Chinese story copy
- Scores saved locally in the browser

## Run
Open `index.html` on the SEIUN site or serve this folder as a static page. No build step or framework.

## Asset drop-in plan
When the audio and decoration assets are supplied, put them here:
- `assets/songs/` for background song files
- `assets/sfx/` for click / note wake-up sound effects
- `assets/decor/` for SVG stars, album shop decor and UI ornament

The selected-song button, song chart and music/audio playback should be connected to real song files and beat maps in the next phase.

## KiKi account / promo ranking
The current prototype intentionally does not pretend to authenticate. Scores are browser-local. KiKi sign-in and server-side promotional ranking need the KiKi sign-in/session integration details and a score endpoint/table with server-side validation before public leaderboard submissions can be enabled.
