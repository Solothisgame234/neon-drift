# Neon Drift

A fast neon endless runner that runs in any browser. Jump, double-jump and dash through a glowing synthwave city.

**Play:** https://solothisgame234.github.io/neon-drift/ · on itch.io: https://stgojo123.itch.io/neon-drift (or download `index.html` and open it)

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
- Neon Crystals currency and a shop: Head Start, Second Chance and 5 ships, each with its own power:

  | Ship | Price | Power |
  |---|---|---|
  | Drifter | free | Combo Keeper: combo timer lasts 3.2 s instead of 2.2 s |
  | Viper | 300 | Long Dash: dashes last 40% longer and recharge in 0.6 s |
  | Solar | 600 | Super Magnet: pulls in orbs from almost twice as far |
  | Phantom | 900 | Shield: survives one crash per run (not falls) |
  | Prism | 1,500 | Triple Jump: a third jump in mid-air |
- Supporter Pack: gold badge, 1,000 crystals and +25% crystals per run for people who support the game on itch.io
- Daily challenge, login streak, share-your-score link, optional CRT filter, music and SFX volume

One file, no libraries, no external assets, no ads and no payment code.

## Supporter Pack

Nothing is bought inside the game. "Support the dev" opens the itch.io page (`SUPPORT.URL`). The pack unlocks either with a redeem code you give supporters, or automatically in a build with `SUPPORT.EDITION = true` (for a paid itch.io file). To change the code, open the game with `?debug`, run `Supporter.hashCode('YOUR-CODE')` in the console and paste the result into `SUPPORT.CODE_HASH`.

## Expanding later

- More ships: add an entry to `SKINS` (name, price, colour, shape points, power). Power tuning is in `POWERS`.
- Real payments or ads: start from `Supporter.open()` (marked `>>> PAYMENTS LATER`).
- Analytics: fill in `Analytics.track` (marked `>>> ANALYTICS`); add `?debug` to the URL to log events.
- Balance: crystal rewards and prices live in `ECON` and `SUPPORT`.

© Solothisgame234. All rights reserved.
