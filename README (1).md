# MIND/SPACE — Interactive Brain Portfolio

> A Bauhaus-inspired 3D interactive portfolio built with Three.js, where each lobe of the brain represents a creative and technical domain.

![Bauhaus Brain Portfolio](https://img.shields.io/badge/Three.js-r128-black?style=flat-square&logo=three.js)
![License](https://img.shields.io/badge/license-MIT-red?style=flat-square)
![Status](https://img.shields.io/badge/status-in%20development-yellow?style=flat-square)

---

## ✦ Concept

The brain as portfolio. Six neural zones map to six creative disciplines — each clickable, each alive. Inspired by Bauhaus design principles: primary forms (circle, square, triangle), primary colors (red, blue, yellow), and the unity of art, craft, and technology.

## ✦ Zones

| Zone | Discipline | Color |
|------|-----------|-------|
| 01 | HCI & Research | Red |
| 02 | UX / UI Design | Blue |
| 03 | 3D Modelling | Yellow |
| 04 | Development | Teal |
| 05 | Games & Apps | Coral |
| 06 | Web Experiences | Purple |

## ✦ Tech Stack

- **Three.js r128** — 3D rendering, custom geometry, lighting
- **Vanilla JS / HTML5** — zero framework dependencies
- **Web Audio API** — ambient drone synthesis
- **CSS3** — Bauhaus layout, custom cursor, panel animations

## ✦ Roadmap

- [ ] Load real `.glb` brain mesh from Blender
- [ ] Custom GLSL vertex shader for electrical pulse effect
- [ ] GSAP for smoother panel transitions
- [ ] Spatial audio per zone (distinct tones)
- [ ] Bloom / post-processing pass
- [ ] Mobile touch gestures
- [ ] Project deep-dive sub-pages per zone
- [ ] Dark/light mode toggle
- [ ] Scroll-based intro animation

## ✦ Project Structure

```
brain-portfolio/
├── index.html          # Main entry — currently self-contained
├── src/
│   ├── js/
│   │   ├── main.js     # Three.js scene setup
│   │   ├── brain.js    # Brain mesh + geometry
│   │   ├── zones.js    # Zone nodes + data
│   │   ├── audio.js    # Web Audio API
│   │   └── ui.js       # Panel, cursor, HUD
│   ├── css/
│   │   └── style.css   # Bauhaus design system
│   ├── shaders/
│   │   ├── brain.vert  # Brain vertex shader
│   │   └── brain.frag  # Brain fragment shader
│   └── assets/
│       ├── models/     # .glb brain mesh (Blender export)
│       └── audio/      # Ambient sound files
├── .gitignore
└── README.md
```

## ✦ Getting Started

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/brain-portfolio.git
cd brain-portfolio

# Open locally (no build step needed yet)
open index.html

# Or use a local server (recommended for .glb loading later)
npx serve .
# or
python3 -m http.server 8080
```

## ✦ Design System

**Typography**
- Display: `Bebas Neue` — headlines, zone numbers
- Mono: `Space Mono` — labels, tags, data
- Body: `IBM Plex Sans` — descriptions, UI text

**Colors**
```css
--bauhaus-red:    #E63329
--bauhaus-yellow: #F5C518
--bauhaus-blue:   #1B4FDB
--bauhaus-black:  #0A0A0A
--bauhaus-white:  #F2EFE4
```

**Forms** — Circle · Square · Triangle (Bauhaus primary forms)

---

Built with intention. Designed for curiosity.
