# Pixel Painter — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Relaxing color-by-number pixel art. Pick a color, paint the numbered cells,
and watch 12 cute pictures come to life — cat, rocket, crab and more. No
fail states, just coloring calm. (181 chars)

## Details

- Genre: Puzzle / Casual / Coloring / Pixel Art
- Controls: Mouse or touch — pick a color from the palette, then tap or drag
  across the matching numbered cells. Keyboard: 1-9 to pick a color, Esc to
  return to the gallery.
- Features: 12 handcrafted pixel pictures (16x16 and 24x24), per-picture
  timer with best-time saving, auto-saved progress (half-finished paintings
  resume where you left off), Relax mode (wrong colors just bounce off) or
  Strict mode (errors cost stars), completion framing with confetti and
  shareable text, Collection Complete badge for finishing all 12.
- Tech: Vanilla JavaScript, Canvas, WebAudio (procedural paper texture,
  ripple/pop effects, synthesized sounds). Single-file HTML5, no external
  assets, no CDN, no tracking, works offline once loaded.
- Platforms: Desktop browsers, mobile browsers (portrait-friendly, touch
  first with drag-to-fill).

## Tags
color by number, coloring, pixel art, puzzle, casual, relaxing, zen, paint, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas adapts to viewport, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover image 16:9 (1280x720) — screenshot the gallery or a finished painting
- [ ] Screenshots (1280x800): gallery view, painting in progress, completion panel

## GameDistribution
- Upload pixel-painter-gd.zip (contains index.html only)
- The GameDistribution SDK is injected automatically on gamedistribution /
  gd.games domains; gameplay events are handled by the SDK wrapper

## itch.io
- Upload pixel-painter-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport: 480x700 (auto-scaling), kind: html
- Pricing: $0 (donations optional)
- Suggested description: the Short description above plus the Details list
