# Living Sigil

Living Sigil is a small browser twin-stick shooter set in a dark tomb arena. You play as a living symbol, survive waves of Shadow Wings, build the Awakening meter, and trigger a short gold-powered form when the meter is full.

Play: https://vibezzzcoder.github.io/living-sigil/

## Controls

- Move: WASD on keyboard, left joystick on touch
- Shoot: Arrow keys on keyboard, right joystick on touch
- Awaken: Space on keyboard, Awaken button on touch
- Pause: P, Enter, Escape, or the Pause button
- Restart: R

## Current Build

- 960x540 game logic with responsive desktop and mobile layouts
- Stage 1 full run: four waves ending with the Gold Wing Warden
- Stage 2 playable run: The Scriptorium of Dust (3 waves, Guardian boss, Dust Sigil reward beat)
- Dormant and awakened player forms
- Enemy roster: Shadow Wing, Sand Dasher, Gold Wing Warden, Guardian of the Scriptorium
- Stage 2 enemy sprite art integrated (state-based Sand Dasher/Guardian visuals)
- Core combat loop: bullets, contact damage, health, score, pause, game over, stage clear
- Stage 2 quicksand drag zones (0.50 speed multiplier) and Buried Observatory background
- Sigil pickup now restores player health before stage transition
- Static loading screen with asset preload progress before title interaction

## Status

This is an evolving browser/mobile prototype. The current build includes a complete Stage 1 flow plus a playable Stage 2 run with Guardian and Dust Sigil reward flow. Stage 2 remains the temporary endpoint while later stages are pending.

## Roadmap

- Current: Stage 1 complete, Stage 2 playable through Guardian + Dust Sigil reward flow.
- Next: hold at the temporary Stage 2 clear endpoint until the next explicitly requested scope.
- Scope: focused 4-stage Cosmic Ascent arc before broader expansion.

## Project Notes

The source is plain HTML, CSS, and JavaScript with no external runtime dependencies.
The upload-ready build is generated as a single file for GitHub Pages.

## License

This repository uses split licensing.

Software source code is licensed under the MIT License. See [`CODE_LICENSE.md`](CODE_LICENSE.md).

Original artwork, the central symbol, derivative symbol designs, sprites, character designs, enemy designs, visual identity, logos, icons, background art, visual effects art, reference images, generated art, processed art, and embedded image data are not licensed under MIT.

These assets are copyright © 2005-2026 E RM. All rights reserved except for limited non-commercial use as part of this game project and its non-commercial forks. See [`ASSET_LICENSE.md`](ASSET_LICENSE.md).

The central symbol and derivative visual designs are original copyrighted works dating from 2005.

Commercial use of the artwork, symbols, sprites, character designs, visual identity, logos, icons, or derivative designs is prohibited without prior written permission. This includes commercial games, apps, merchandise, advertising, branding, NFTs/tokens, asset packs, stock art, icons, logos, mascots, resale, and commercial AI training datasets.

Generated single-file releases, including `release/index.html`, may contain both MIT-licensed code and protected embedded assets. The code portions remain MIT-licensed, but embedded artwork and asset data remain under the Asset License. The complete bundled game may be played, shared, and forked for non-commercial purposes only unless separate written commercial permission is granted.

This project is public for viewing, learning, non-commercial playtesting, and non-commercial collaboration. The artwork and visual identity remain protected.
