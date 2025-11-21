# daggerfall-lite-web
Daggerfall Lite: Web Edition ⚔️🛡️

A retro-style, procedural 3D dungeon crawler inspired by The Elder Scrolls II: Daggerfall, built entirely within a single HTML file using Three.js and Vanilla JavaScript.

Playable directly in the browser. No external assets or downloads required.

📖 About

This project is a "Daggerfall-Lite" engine that replicates the atmosphere of 90s RPGs using modern web technologies. It features a robust procedural generation system that creates infinite dungeons, wilderness environments, textures, sprites, and even music in real-time.

✨ Key Features

🌍 Procedural World Generation

Infinite Dungeons: Uses recursive backtracker algorithms to generate complex, maze-like crypts.

Open Wilderness: Seamless transition from dungeons to an open-world terrain with day/night cycles (skybox).

Dynamic Towns: Procedurally generated settlements with houses, villagers, and interactive merchants.

⚔️ Action Combat System

Physics-Based Movement: Momentum, friction, and head-bobbing for realistic movement.

Active Defense: Hold Right Click to block damage.

Parry Mechanic: Timed blocks (within 400ms) trigger a "Perfect Parry," stunning enemies and negating all damage with visual/audio feedback.

Classes: Choose from Knight (Tank), Rogue (Speed), or Spellsword (Balanced) at character creation.

🎨 Asset Generation (No External Files)

Canvas Textures: All wall textures, floors, and UI elements are painted procedurally onto HTML5 Canvases.

2.5D Sprites: Enemies (Orcs, Bandits) and NPCs are generated as pixel-art billboards that always face the camera.

Dynamic Minimap: Real-time minimap with a directional arrow indicator.

🎵 Generative Audio Engine

Adaptive Music: A custom Web Audio API engine generates music in real-time based on your location.

Dungeon: Dark, atonal drifting drones with random mechanical stings.

Wilderness: Generative "wind chime" melodies using a C Major Pentatonic scale.

Spatial SFX: Procedural sound synthesis for sword swings, fleshy impacts, metallic parries, and blocking.

🎮 Controls

Move: W, A, S, D

Sprint (Uses Stamina): Shift

Look: Mouse

Attack: Left Click

Block / Parry (Timing matters!): Right Click

Interact (Ladders, NPCs, Shops): E

Pause / Release Cursor: ESC

🛠️ Tech Stack

Core: HTML5, CSS3, Vanilla JavaScript

Rendering: Three.js (r128)

Audio: Web Audio API (Oscillators & Gain Nodes)

Asset Pipeline: HTML5 Canvas API (Procedural texture generation)

🚀 How to Run

Clone the repository.

Open daggerfall_lite.html in any modern web browser (Chrome, Firefox, Edge).

Click "Begin Adventure" to initialize the audio context and start the game.

Built as a prototype to demonstrate procedural content generation in the browser.
