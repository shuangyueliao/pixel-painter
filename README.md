# Pixel Painter · Color by Number

A free, single-file HTML5 color-by-number game. Pick a color from the palette,
tap or drag across the numbered cells, and watch 12 cute pixel pictures come to
life — cat, house, apple tree, heart, flower, sun, mushroom, boat, crab,
cactus, rocket and snowman. No fail states, no pressure: pure coloring calm.

**Play:** https://shuangyueliao.github.io/pixel-painter/

- Mobile touch (drag to fill) + desktop mouse & keyboard (1-9 pick color, Esc back)
- Relax mode (wrong colors just bounce) or Strict mode (errors cost stars)
- Per-picture timer with best-time saving, half-finished pictures auto-resume
- Finish all 12 to earn the Collection Complete badge
- Procedural paper texture, ripple and confetti effects; WebAudio-synthesized sounds
- One `index.html`, zero external assets, no build step, no tracking

## Submitting to portals

The game is a single self-contained HTML file, ready for HTML5 game portals
(CrazyGames, GameDistribution, itch.io). The CrazyGames SDK loader is
domain-guarded and only activates on crazygames.com; the GameDistribution SDK
only on gamedistribution / gd.games. Everywhere else (including this GitHub
Pages page) no external script is loaded at all.
