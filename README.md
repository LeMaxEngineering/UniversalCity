# 🛸 Universal City — Planetary Defense
<img width="956" height="554" alt="image" src="https://github.com/user-attachments/assets/71156e09-6423-4fbc-8a8b-bcb5a95f3c7a" />


A single-file, zero-dependency browser game built with vanilla HTML5 Canvas and JavaScript. Protect the city dome from incoming missile waves by firing laser turrets and managing your heat gauge. When things get overwhelming, unleash the Nova Blast — but watch out for Armored Missiles that can only be taken down by direct laser fire.

## Gameplay
<img width="1266" height="878" alt="sshot02" src="https://github.com/user-attachments/assets/6722f92c-7385-430f-9f8a-e01a57df6083" />

Two laser turrets sit on the rim of a city bowl, projecting a red energy shield across the valley. Missiles rain from above and must be destroyed before they breach the shield. Every impact damages the grid — let it fall to zero and the city is lost.

- **Left click (hold)** — fire continuous laser beams. Overheat shuts both turrets down temporarily.
- **Right click** — Nova Blast, a massive radial explosion. 5-second cooldown.
- **Armored Missiles** (purple/teal) — immune to the Nova Blast. Direct laser hit only.
- **F key** — toggle fullscreen.

## Features

- Smooth 60fps HTML5 Canvas rendering with screen shake, particle explosions, and glow effects
- Procedurally generated sci-fi city skyline with animated window lights
- Two missile types with distinct behaviors and visuals
- Heat management mechanic that punishes spray-firing
- Persistent top-10 leaderboard stored in localStorage
- Fully responsive — scales to any screen size and supports fullscreen mode
- Touch support for mobile and tablet play
- Single `.html` file — no build tools, no dependencies, no install

## How to run

Just open `UniversalCity.html` in any modern browser. No server needed.
```bash
# Clone and open
git clone https://github.com/yourname/universal-city.git
open universal-city/UniversalCity.html
```

## Tech

Pure vanilla JavaScript and HTML5 Canvas API. No frameworks, no libraries, no bundler.

## License

MIT
