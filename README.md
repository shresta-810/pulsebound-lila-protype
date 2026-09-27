# Pulsebound — Lila Games Written Test Prototype

A tiny browser-playable survivor-like prototype built around one idea:
**the game director reads how you play and changes the next wave.**

## Play
Open `index.html` in a browser. No build step is required.

Controls:
- WASD / Arrow keys: move
- Combat: automatic
- Upgrade choice: click a card or press 1/2/3
- R after death: restart

## GitHub Pages
1. Create a public GitHub repository.
2. Upload `index.html`.
3. Settings → Pages → Deploy from branch → `main` / root.
4. Share the resulting GitHub Pages URL.

## Important
This is a prototype, not production code. The "AI" in the prototype is a transparent adaptive gameplay director: it classifies the player's recent behavior into broad styles and adjusts enemy pressure. It is deliberately explainable and deterministic.
