# Changelog

## v1.1

Coin overhaul — bigger, rounder, spinning, and more plentiful.

- Increased coin size from 10x10 to 14x14
- Round coins drawn with `arc()` instead of square pixel art
- 3D spinning animation: front face, edge, and darker back face via horizontal scale
- Spawn rate increased ~35% (every 18-33 frames vs 25-45)
- Higher chance of coin patterns (60% vs 50%) and double-spawns (55% vs 40%)
- New 6th coin pattern: arc/rainbow of 7 coins in a semicircle
- Wider pattern spacing (22px) to fit larger coins

## v1.0

A retro pixel-art endless runner built as a single HTML file with zero dependencies. Flip gravity to dodge obstacles, collect coins, fight bosses, and chase high scores.

- Gravity-flipping mechanic with floor/ceiling traversal
- 4 obstacle types: blocks, spikes, saw blades, lasers
- Boss fights every 2,000m with scaling difficulty
- 5 power-ups: Shield, Magnet, Slow-Mo, Double Score, Invincible
- 6 unlockable character skins
- 16 achievements
- Local leaderboard with 3-character name entry
- Procedural music and sound effects (Web Audio API)
- Parallax pixel-art cityscape with CRT scanline overlay
- Mobile support with touch controls and haptic feedback
