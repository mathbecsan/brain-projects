# MIND/SPACE — Interactive Brain Portfolio

> A Bauhaus-inspired 3D interactive portfolio built with Three.js, where each lobe of the brain represents a creative and technical domain.

![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=flat-square&logo=three.js)
![License](https://img.shields.io/badge/license-MIT-red?style=flat-square)
![Status](https://img.shields.io/badge/status-active-green?style=flat-square)

---

## 🌟 Concept

The brain as portfolio. Six neural zones map to six creative disciplines — each clickable, each alive. Inspired by Bauhaus design principles: primary forms (circle, square, triangle), primary colors (red, blue, yellow), and the unity of art, craft, and technology.

**Live Demo:** [mindspace.dev](https://mindspace.dev) *(coming soon)*

---

## 🧠 Zones

| Zone | Discipline | Color | Status |
|------|-----------|-------|--------|
| 01 | [HCI & Research](src/zones/hci/) | 🔴 Red | Placeholder |
| 02 | [UX / UI Design](src/zones/ux-ui/) | 🔵 Blue | Placeholder |
| 03 | [3D Modelling](src/zones/3d-modelling/) | 🟡 Yellow | Placeholder |
| 04 | [Development](src/zones/development/) | 🟢 Teal | Placeholder |
| 05 | [Games & Apps](src/zones/games/) | 🟠 Coral | Placeholder |
| 06 | [Web Experiences](src/zones/web-experiences/) | 🟣 Purple | Placeholder |
| **07** | **[Linguistics](src/zones/linguistics/)** | **⚪ White** | **✅ Live** |

### GLYPH/SPACE — Linguistics Zone
The first implemented zone: an interactive Unicode 3D explorer featuring:
- **600+ glyphs** across multiple scripts (Latin, Greek, Cyrillic, Arabic, CJK, Devanagari, Symbols, Math)
- **Galaxy & Grid views** with smooth transitions
- **Real-time search** and script filtering
- **3D spatial navigation** (drag to rotate, scroll to zoom)
- **Glyph detail panels** with Unicode metadata

---

## 🛠 Tech Stack

- **Three.js r128** — 3D rendering, custom geometry, lighting
- **Vanilla JS / HTML5** — zero framework dependencies
- **Web Audio API** — ambient drone synthesis
- **CSS3** — Bauhaus layout, custom cursor, panel animations
- **WebGL Shaders** — procedural brain geometry, particle systems

### Key Features
- **Custom 3D Brain Model** — Procedurally generated organic mesh
- **Interactive Zones** — Clickable geometric nodes on brain surface
- **Neural Connections** — Animated lines between zones
- **Particle Systems** — Ambient neural signals
- **Responsive Design** — Works on desktop and mobile
- **Audio Integration** — Optional ambient soundscape

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser with WebGL support
- Local web server (for proper file loading)

### Installation
```bash
# Clone the repository
git clone https://github.com/mathbecsan/brain-projects.git
cd brain-projects

# Start a local server
python -m http.server 8000
# or
npx serve .

# Open in browser
# http://localhost:8000
```

### Development
```bash
# The project is self-contained with no build process
# Edit HTML/CSS/JS files directly
# Refresh browser to see changes
```

---

## 📁 Project Structure

```
brain-projects/
├── index.html                    # Main brain interface
├── README.md                     # This file
├── src/
│   ├── js/                       # JavaScript modules (future)
│   ├── css/                      # Stylesheets (future)
│   ├── shaders/                  # GLSL shaders (future)
│   └── zones/                    # Individual zone experiences
│       ├── linguistics/          # GLYPH/SPACE - Unicode explorer
│       │   └── index.html
│       ├── hci/                  # Human-Computer Interaction
│       │   └── index.html
│       ├── ux-ui/                # UX/UI Design
│       │   └── index.html
│       ├── 3d-modelling/         # 3D Modelling
│       │   └── index.html
│       ├── development/          # Development
│       │   └── index.html
│       ├── games/                # Games & Apps
│       │   └── index.html
│       └── web-experiences/      # Web Experiences
│           └── index.html
```

---

## 🎨 Design Philosophy

### Bauhaus Principles
- **Form follows function** — Every element serves a purpose
- **Primary colors** — Red, blue, yellow as zone identifiers
- **Primary shapes** — Circle, square, triangle as geometric nodes
- **Unity of arts** — Design, art, and technology as one

### Interaction Design
- **Spatial navigation** — 3D brain as information architecture
- **Progressive disclosure** — Click zones to reveal details
- **Ambient interfaces** — Subtle animations and audio
- **Inclusive design** — Works without JavaScript (graceful degradation)

---

## 🔮 Roadmap

### Phase 1: Core Brain Interface ✅
- [x] 3D brain model with procedural geometry
- [x] Interactive zones with hover/click states
- [x] Sliding panel with zone details
- [x] Audio toggle with ambient synthesis
- [x] Mobile touch support

### Phase 2: Zone Development 🚧
- [x] Linguistics zone (GLYPH/SPACE)
- [ ] HCI Research zone
- [ ] UX/UI Design zone
- [ ] 3D Modelling zone
- [ ] Development zone
- [ ] Games & Apps zone
- [ ] Web Experiences zone

### Phase 3: Enhancements 📋
- [ ] Custom GLSL shaders for brain surface
- [ ] GSAP animations for smoother transitions
- [ ] Spatial audio per zone
- [ ] Bloom/post-processing effects
- [ ] Scroll-based intro animation
- [ ] Dark/light mode toggle
- [ ] Project deep-dive sub-pages
- [ ] Performance optimizations

---

## 🤝 Contributing

This is a personal portfolio project, but feel free to:
- Report bugs or suggest improvements
- Fork and experiment with the code
- Share ideas for zone implementations

---

## 📄 License

MIT License — see [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Three.js** community for the amazing WebGL framework
- **Bauhaus** movement for timeless design principles
- **Unicode Consortium** for the GLYPH/SPACE dataset
- **Web Audio API** for enabling browser-based audio synthesis

---

*Built with ❤️ and WebGL*
