# Thornvyr Simulator

Minimal training page for the **Thornvyr the Wise** pillar mechanic (Eternal Hero).

**Play:** https://thornvyr-simulator.pages (GitHub Pages URL added after deploy)

## How it works

Thornvyr spawns 4 pillars (phase 1) or 5 (phase 2). Each pillar has three traits:

- **Shape:** 🥬 leaf or 🍀 clover
- **Color:** empty or filled
- **Border:** with or without

Exactly one pillar differs on exactly one trait. Tap it before the cast bar empties.

## Controls

- `1` — 4 pillars, 3.0s cast
- `2` — 5 pillars, 2.5s cast
- `↻` — reset
- Keyboard: `1`, `2`, `R`

Stats (streak / correct / wrong / best) are kept in `localStorage` per phase.

## Tech

Single `index.html`, vanilla JS, inline SVG. No dependencies, no build step.
