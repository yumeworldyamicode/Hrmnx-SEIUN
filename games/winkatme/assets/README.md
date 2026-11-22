# WINK AT ME asset checklist

The game is designed around low-resolution PNG sprite assets. Keep character sprites and decorations pixel-art; do not use large smooth illustrations, or the pixel effect will not read clearly.

## Images to add

### Logo
- `assets/logo/seiun-pixel-logo.png` — SEIUN pixel logo for the top-left brand slot. Transparent PNG, about 160x48 px.

### Characters
- `assets/characters/yennie.png`
- `assets/characters/suji.png`
- `assets/characters/hyejin.png`

Recommended sprite size: 96x128 or 128x160 pixels, transparent background, full-body chibi. Brown hair and eyes, sailor outfits. These images are used in intro, character selection, story, game HUD and results. Keep the characters centered in a consistent sprite canvas.

### Floating stars / decor
- `assets/decor/star-blue.png`
- `assets/decor/star-pink.png`
- `assets/decor/star-white.png`

Transparent pixel stars, about 16x16 or 24x24 pixels. Additional decor can be added later as pixel PNGs.

### Album / story art (future slots)
Use `assets/story/` for WINK album art, album-store background, CD player, tired music-note sprites, awakened notes, and any cutscene props. Keep individual objects as separate sprites where possible.

## Audio to add

Create these folders and place files in them:
- `assets/audio/music/` — background tracks / song choices. Use descriptive names, for example `wink.mp3`, `u.mp3`, and additional release tracks.
- `assets/audio/sfx/` — short effects: `tap.wav`, `hit-perfect.wav`, `hit-good.wav`, `miss.wav`, `note-wake.wav`, `menu-select.wav`, `menu-confirm.wav`, `story-transition.wav`, `result-clear.wav`.
- `assets/audio/voice/` (optional) — short character lines, if planned.

The current rhythm prototype uses generated tones as temporary feedback. Real audio playback, song beat maps, and synchronization will be wired in after the actual audio files and timing/chart data are supplied.

## Pixel styling
- CSS uses `image-rendering: pixelated` / `crisp-edges` for sprite images.
- UI font: Press Start 2P for headings, buttons and HUD.
- Readable text font: VT323.
- Use pixel dimensions and nearest-neighbour style art; avoid smoothing/antialiasing.
