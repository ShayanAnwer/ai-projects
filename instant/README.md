It was generated through a sequence of prompts using Cursor.

- **Frontend:** Plain **HTML + CSS + JavaScript** in a single file: `index.html`
- **3D engine:** **Three.js** (ES module import from CDN: `unpkg.com`)
- **Rendering:** **WebGL** via Three.js `WebGLRenderer`
- **Game logic/input:** Custom JS (arrow keys + space handling, raycasting hit detection, AI movement/spawn logic)
- **UI/HUD:** Standard DOM/CSS overlays (crosshair, score, `+1` popup)
- **Build system/framework:** **None** (no React/Vue/Angular, no bundler)
- **Run setup:** Any simple static HTTP server (e.g. `npx serve`)
