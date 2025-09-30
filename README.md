# Tsushima Duel - 3D Action Game

A 3D action game inspired by Ghost of Tsushima's dueling scenes, built with Three.js and Rapier.js physics.

## Features

- **3D Scene Rendering**: Sunset lighting atmosphere with simple buildings
- **Character Control**: WASD movement, mouse camera control, attack/block actions
- **Physics Integration**: Collision detection and character physics using Rapier.js
- **Combat System**: Basic attack and blocking mechanics with hit detection

## Controls

- **WASD**: Move character
- **Mouse**: Control camera view
- **Space**: Attack
- **Shift**: Block/Defend

## Setup

1. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```
   Or with Node.js:
   ```bash
   npx http-server -p 8000
   ```

2. Open browser and navigate to `http://localhost:8000`

## Game Elements

- **Player**: Blue samurai with sword
- **Enemy**: Red opponent with weapon
- **Environment**: Ancient buildings with sunset lighting
- **Physics**: Real-time collision detection and movement

## Technical Stack

- **Three.js**: 3D rendering and scene management
- **Rapier.js**: Physics simulation and collision detection
- **Vanilla JavaScript**: Game logic and controls

## Future Enhancements

- Load external 3D models (GLTF/FBX)
- Skeletal animation system
- Advanced combat mechanics
- Sound effects and music
- Multiple enemy AI
- Environmental interactions
