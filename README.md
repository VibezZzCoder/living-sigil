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

- One 960x540 tomb arena
- Stage 1 four-wave run ending with the Gold Wing Warden elite fight
- Playable Stage 2 prototype run: The Scriptorium of Dust (3 waves, Guardian boss, Dust Sigil reward beat)
- Stage 2 Phase 8 QA/tuning pass complete: mobile portrait/landscape reward readability checked, Dust Sigil presentation centered correctly on high-DPR mobile screens, and release/Pages artifacts reverified
- Dormant and awakened player forms
- Shadow Wing enemies, Sand Dasher prototype enemy, Gold Wing Warden, and Guardian of the Scriptorium boss prototype
- Player bullets, contact damage, health, score, pause, game over, and stage clear
- Stage 1 identity polish for Tomb of the First Sigil, including intro/clear presentation, ambient dust, Awakening flare, and tiny WebAudio cues
- Stage 2 Buried Observatory background, live quicksand drag zones (0.50 speed multiplier), stage intro banner, and Dust Sigil reclaimed beat before temporary prototype clear presentation
- Static loading screen with asset preload progress before the title becomes interactive
- Mobile portrait, mobile landscape, and desktop layouts

## Status

This is an evolving browser/mobile prototype. The current build includes a complete Stage 1 flow plus a playable Stage 2 Phase 8 prototype pass (3 waves + Guardian + Dust Sigil reward beat + mobile/release QA). Stage 2 remains a temporary clear endpoint while later stages are pending.

## Roadmap

- Current: Stage 1 complete prototype flow plus Stage 2 playable Guardian + Dust Sigil reward prototype with Phase 8 QA/tuning completed.
- Next planned: hold at the temporary Stage 2 clear endpoint until the next explicitly requested scope.
- Scope: focused 4-stage Cosmic Ascent arc before considering broader expansion.

## Project Notes

The source is plain HTML, CSS, and JavaScript with no external runtime dependencies. The upload-ready build is generated as a single file for GitHub Pages.


## License

This repository uses split licensing.

Software source code is licensed under the MIT License. See [`CODE_LICENSE.md`](CODE_LICENSE.md).

Original artwork, the central symbol, derivative symbol designs, sprites, character designs, enemy designs, visual identity, logos, icons, background art, visual effects art, reference images, generated art, processed art, and embedded image data are not licensed under MIT.

These assets are copyright © 2005-2026 E RM. All rights reserved except for limited non-commercial use as part of this game project and its non-commercial forks. See [`ASSET_LICENSE.md`](ASSET_LICENSE.md).

The central symbol and derivative visual designs are original copyrighted works dating from 2005.

Commercial use of the artwork, symbols, sprites, character designs, visual identity, logos, icons, or derivative designs is prohibited without prior written permission. This includes commercial games, apps, merchandise, advertising, branding, NFTs/tokens, asset packs, stock art, icons, logos, mascots, resale, and commercial AI training datasets.

Generated single-file releases, including `release/index.html`, may contain both MIT-licensed code and protected embedded assets. The code portions remain MIT-licensed, but embedded artwork and asset data remain under the Asset License. The complete bundled game may be played, shared, and forked for non-commercial purposes only unless separate written commercial permission is granted.

This project is public for viewing, learning, non-commercial playtesting, and non-commercial collaboration. The artwork and visual identity remain protected.
