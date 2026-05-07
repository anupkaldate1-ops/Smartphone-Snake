🐍 Hyper Serpent

A premium, modernized, mobile-first recreation of the classic Nokia Snake game. Built entirely with vanilla web technologies (HTML5, Canvas API, JS), this project pushes the boundaries of browser gaming with next-gen mechanics, AI-powered generation, real-time leaderboards, and multiple adrenaline-pumping game modes.

Play it live here: https://github.com/anupkaldate1-ops/Smartphone-Snake.git

✨ Key Features

📱 Mobile-Optimized PWA: Play seamlessly on any device. Features intelligent 100dvh scaling, responsive swipe controls, an on-screen D-pad, and works completely offline as an installable Progressive Web App.

🎮 6 Dynamic Game Modes:

🟢 Classic (Zen): The pure, endless retro experience.

🧱 Maze Runner: Procedurally generated walls drop as your score increases.

👹 Boss Chase: An AI-controlled Glitch Serpent actively hunts you and competes for your food.

🌌 Quantum Portals: Teleport across the map with shifting portals.

☄️ Avalanche: Dodge a chaotic, incoming meteor shower.

🌑 Night Terror: Navigate in pitch-black darkness with only a shrinking spotlight.

⚡ Adrenaline Combo System: Chain food pick-ups quickly to build up to a 5x multiplier. Use the Turbo Dash mechanic to outmaneuver threats, and eat Ice Cubes (🧊) to cool down your rising speed.

🤖 AI-Powered Capabilities: Integrated with the Gemini API to dynamically generate custom color themes and emojis on the fly, alongside a "Snarky AI Announcer" that critiques your Game Overs. Includes beautiful built-in fallback themes (Cyberpunk, Matrix, Ocean, etc.) for offline play.

🏆 Global Leaderboards: Frictionless Firebase integration tracks returning players and broadcasts the Top 3 Global High Scores live to the main menu.

🌌 3D Gyroscope & Particle VFX: Interactive 3D parallax backgrounds that tilt with your mobile device's gyroscope or PC mouse. Every theme features a bespoke particle physics engine (Matrix rain, floating ocean bubbles, Cyberpunk laser streaks).

🎵 Native Retro Audio Engine: Zero external sound files. All 8-bit sound effects (eating, power-ups, deaths) are generated natively using the Web Audio API synthesizer.

🚀 How to Run Locally

Because this project is completely self-contained in a single file, running it is incredibly easy:

Clone or download this repository.

Open index.html directly in any modern web browser.

(Optional) To enable the live AI features, generate a free API key from Google AI Studio and place it in the apiKey variable inside the script. Otherwise, the game will seamlessly use the built-in offline fallbacks!

🛠️ Built With

HTML5 / Canvas API: Rendering engine & game loop.

Vanilla JavaScript: Core logic, physics, and state management.

Tailwind CSS: Responsive, utility-first UI styling.

Firebase (Firestore & Auth): Anonymous authentication and real-time database tracking.

Google Gemini API: Procedural generation of UI themes and text.
