# 🐍 Snake — Arcade Edition

A modern, polished take on the classic Snake game, built from scratch with vanilla HTML, CSS, and JavaScript. No frameworks, no libraries — just clean front-end code.

**[▶ Play Live Demo](https://spontaneous-cuchufli-63e82f.netlify.app/)**

---

## Features

- Smooth snake movement with animated eyes that follow direction
- Progressive difficulty — speed increases every 5 points
- Bonus golden pickups that appear randomly for 3× score
- Particle burst effects on eating
- Persistent high score tracking across sessions
- Pause / resume with `P`
- Mobile-friendly d-pad controls
- Retro terminal aesthetic with custom fonts and a glowing grid

---

## Tech Stack

- HTML5 Canvas for rendering
- Vanilla JavaScript — game loop, collision detection, state management
- CSS3 — animations, responsive layout
- Google Fonts — Orbitron + Share Tech Mono

---

## Getting Started

No build step needed. Just open the file:

```bash
git clone https://github.com/your-username/snake-arcade.git
cd snake-arcade
open index.html
```

Or deploy instantly to Netlify / Vercel by connecting this repo — it's a single static `index.html` file.

---

## How to Play

| Key | Action |
|-----|--------|
| `↑ ↓ ← →` or `W A S D` | Move |
| `P` | Pause / Resume |
| Mobile | On-screen d-pad appears automatically |

- Eat the **red apple** to grow and score points
- Catch the **golden bonus** before it disappears for 3× points
- Speed increases every 5 points — how far can you go?

---

## Project Structure

```
snake-arcade/
└── index.html    # entire game — HTML, CSS, and JS in one file
```

---

## What I Learned

- Canvas 2D rendering and game loop architecture with `setInterval`
- Collision detection and grid-based movement logic
- Particle systems using basic vector math
- Responsive design for both desktop and mobile inputs
- Deploying static projects to Netlify and Vercel

---

## License

MIT — feel free to fork and build on it.
