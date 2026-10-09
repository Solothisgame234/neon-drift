# Neon Drift

A fast neon endless runner that runs in any browser. Jump, double-jump and dash through a glowing synthwave city.

**Play:** https://solothisgame234.github.io/neon-drift/ (or download `index.html` and open it)

## Controls

| Action | Keyboard | Touch | Gamepad |
|---|---|---|---|
| Jump / double jump | Space, ↑, W | tap left side | A |
| Dash | Shift, →, D | tap right side | B / X / RB |
| Pause | P, Esc | ❚❚ button | Start |
| CRT filter / mute | C / M | menu buttons | |

Red hazards always hurt. Amber gates and drones break when you dash through them. Chain orbs to build your multiplier up to x8.

## Features

- Procedural levels tuned to the jump physics, so every gap can be cleared
- Particles, screen shake, a lagging camera and colours that shift as your score rises
- Synthesized sound effects and music (Web Audio, no audio files)
- Neon Crystals currency, a shop (5 ships, Head Start, Second Chance, Remove Ads), daily challenge and login streak
- Ready for ads, purchases and analytics: search `index.html` for `>>> ADS`, `>>> IAP` and `>>> ANALYTICS`

One file, no libraries, no external assets.

## Before release

- Set `IAP.SANDBOX` to `false` (purchases are simulated while it is `true`).
- Plug your ad network into the `Ads` module and your analytics into `Analytics.track`.
- Add `?debug` to the URL to log analytics events in the console.

© Solothisgame234. All rights reserved.
