# Offer Hunting

A 20-second arcade game: UFOs fly in from both sides carrying SDE skills (Python, AWS, System Design, ...). Aim with your mouse/trackpad, press **Space** to throw a keyboard, and shoot down UFOs to collect skills and chain combos. Land the right combo before time's up and you get the offer.

**Play it here: [abram0102.github.io/SDE_Skills_Hunting_Game](https://abram0102.github.io/SDE_Skills_Hunting_Game/)**

## Controls

- **Mouse / Trackpad** — aim your throw
- **Space** — throw the keyboard
- **20 seconds** — one round

## Tech

Single-file, no build step, no dependencies:

- HTML5 `<canvas>` with vanilla JavaScript for the game loop, rendering, and collision detection
- CSS custom properties for theming, with layered start/HUD/end-screen overlays on top of the canvas
- Deployed as a static page via GitHub Pages
