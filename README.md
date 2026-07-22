# DOOM - Browser Edition

A complete DOOM-style raycasting FPS game running entirely in the browser.

## Features

- **Raycasting 3D Engine** - Wolfenstein 3D style rendering with DDA algorithm
- **Player Movement** - WASD movement + mouse look (pointer lock) + arrow keys
- **Weapons** - Shotgun (5-pellet spread) and Rocket Launcher (explosive projectiles)
- **Enemies** - 3 types:
  - **Imp** - Ranged attacker, keeps distance
  - **Demon** - Melee attacker, fast and aggressive
  - **Cacodemon** - Heavy ranged attacker, high HP
- **HUD** - Health, armor, ammo display + minimap
- **Audio** - Procedural sound effects via Web Audio API (shooting, explosions, enemy deaths, damage)
- **Visual Effects** - Head bobbing, muzzle flash, hit flash, particle explosions, wall shading
- **Game Flow** - Start screen → Gameplay → Victory/Defeat screen

## Controls

| Key | Action |
|-----|--------|
| WASD | Move |
| Mouse | Look (click to lock) |
| Left Click | Shoot |
| 1 | Switch to Shotgun |
| 2 | Switch to Rocket Launcher |
| P | Pause |

## Technical

- Single HTML file, no external dependencies
- Canvas 2D rendering (320x200 internal resolution)
- Vanilla JavaScript
- Web Audio API for procedural audio
- DDA raycasting algorithm
- Sprite-based enemy rendering with z-buffer

## Map

- 20x20 grid with varied wall types
- 13 enemies total across the map
- Complex layout with corridors and rooms

## How to Play

1. Open `doom.html` in a web browser
2. Click "START GAME"
3. Click on the game to lock your mouse
4. Use WASD to move, mouse to look around
5. Click to shoot, 1/2 to switch weapons
6. Defeat all 13 enemies to win!
