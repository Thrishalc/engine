# Platformer Physics

A self-contained 2D side-scrolling platformer physics demo. Open `index.html` in a
modern browser to play; no build step or dependencies are required.

## Controls

- Move with **Left/Right** or **A/D**.
- Jump with **Space**, **Up**, or **W**. Releasing jump early shortens the jump.
- Use **Restart** to return to the start.

## Physics and level

The fixed-step game loop applies gravity, horizontal acceleration and friction,
and a limited variable-height jump. Player movement is resolved one axis at a
time against axis-aligned platform and obstacle bounds, preventing the player
from passing through the sample level's solid surfaces during normal play. The
camera follows the player through gaps, ledges, and block obstacles.