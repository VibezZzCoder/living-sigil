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
- Stage 3 playable prototype: The Overgrown Scriptorium (3 waves, Warded Glyph Anchors, Warded Vine Glyphs, Bramble Heart boss, Verdant Sigil reward beat)
- Stage 4 complete prototype: The Celestial Loom (3 finite portal-teaching waves, Astral Weaver boss, Astral Sigil reward, and first Cosmic Ascent arc-complete clear)
- Dormant and awakened player forms
- Enemy roster: Shadow Wing, Sand Dasher, Warded Vine Glyph, Star Core, Gold Wing Warden, Guardian of the Scriptorium, Bramble Heart, Astral Weaver
- Sprite art is integrated where approved, with canvas-drawn visuals retained as automatic fallbacks or intentional Stage 4 prototype art:
  - Stage 2: state-based Sand Dasher and Guardian visuals plus the bespoke Moon-Sand Hourglass Dust Sigil
  - Stage 3: Warded Vine Glyph, Warded Glyph Anchor, Bramble Heart, Bramble Thorn projectile, and corrupted/purified Verdant Sigil
  - Stage 4: approved Diamond Sentry Star Core, Winged Spindle Astral Weaver, corrupted/purified Constellation Tablet Astral Sigil, and Octagonal Loom Gate portal sprites; lensing, shards, Constellation Sparks, Stellar Sweep, and canvas bodies/rings remain procedural effects or automatic fallbacks
- Core combat loop: bullets, contact damage, health, score, pause, game over, stage clear
- Stage 2 quicksand drag zones (0.50 speed multiplier), Stage 3 ward anchors, and stage-specific backgrounds
- Sigil pickup restores player health before stage transition
- Four distinct offline procedural WebAudio scores, expanded event SFX, balanced music/effect buses, and master dynamics control
- Sigil-convergence arc-complete finale with a responsive results presentation and reduced-motion path
- Static dark loading screen with an immediate indeterminate preparing state, decode progress, graceful art fallbacks, and bootstrap Reload recovery before title interaction

## Status

This is a browser/mobile four-stage release-candidate prototype. Stage 4 sprite/portal integration, reward correction, the four-stage procedural soundtrack, expanded effects mix, and the sigil-convergence finale are complete. The exact generated release boots cleanly, passes normal/fallback and desktop/portrait/landscape endpoint checks, and reaches the dedicated arc-complete state through the Astral reward route. Gameplay-reviewed WebP delivery art keeps the offline single-file build near 7.7 MB while the approved PNG originals remain preserved locally.

## Roadmap

- Current: four-stage playable prototype and first Cosmic Ascent arc complete.
- Future scope: to be determined.

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
