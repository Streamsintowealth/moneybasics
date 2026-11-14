# Road to a Million — Ultimate Edition (Integrated Preview)

This package restores **all six game modes** in one website:
- Adventure Quest (V4 animated 2D mode)
- Money Battle (actual 3D WebGL arena)
- Partnership (V4 mode; room code depends on external peer service)
- Scavenger Hunt (V4 illustrated interactive mode)
- Build an Empire (V4 animated 2D mode)
- Millionaire Race (V4 animated 2D mode)

**Important:** This is an integrated preview, NOT a finished commercial-grade six-mode 3D game. Only Money Battle uses a true 3D renderer. Other modes remain at their previous development level. Online multiplayer is not guaranteed on school networks.

## Installation
Upload BOTH `index.html` and `battle3d.html` to the root of a new GitHub Pages repository. Set Settings → Pages → Deploy from a branch → main → /(root).

## Battle controls
A/D move, W/Space jump, J strike (with auto-lunge), K block, L ranged special, Q financial question. Touch controls provided. Starts with 80 energy; attacks use 10 energy; answering correctly recharges it. The 3D renderer loads Three.js over the internet.

## Testing
Source checked for JavaScript syntax and archive integrity. Full cross-device classroom QA is still required.
