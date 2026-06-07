# Neon Dash

A tiny, complete, juicy arcade game — **built end-to-end with the Hermes
[`game-development`](https://github.com/NousResearch/hermes-agent/pull/40796)
skill** as a working proof that the skill produces real, playable games, not
just documentation.

**▶ Play: https://hellgurd.github.io/neon-dash/**

Dodge the pink hazards, grab the cyan orbs, survive as long as you can. Works on
desktop (mouse / A‑D / arrows) and mobile (touch).

## Built following the skill's own methodology

The game deliberately uses the patterns the skill teaches, so the code is a
live example of the docs:

- **Fixed-timestep simulation + variable-timestep render** (`core-systems.md`)
- **Explicit game state machine** — MENU → PLAY → DEAD (`core-systems.md`)
- **Object pooling** for particles (`core-systems.md` / optimization)
- **Game feel / juice** — screen shake, hit-stop, particle bursts, eased
  player follow, difficulty ramp (`polish` stage)

Single `index.html`, no dependencies, no build step.