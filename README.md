# FARLANDS — Hackathon 2026

A cinematic hackathon landing page that takes visitors on a journey from the ancient era of **Vishvakarma** (the divine architect) to the blocky, infinite world of the **Farlands** (Minecraft-inspired).

## ✨ Features

### Cinematic Journey Experience
- **Vishvakarma Era Opening** — Ancient temple aesthetic with warm golden tones, Playfair Display serif typography, and sacred atmosphere
- **Scroll-Triggered Transition** — A 200vh scroll section with a Canvas-based pixelation effect that visually transforms the ancient stone world into Minecraft-style blocks
- **Farlands Reveal** — Full Minecraft-themed hero with Syne display typography, vibrant greens, and blocky UI elements

### Design Highlights
- **Dual Typography System**: Playfair Display (ancient/editorial) × Syne (modern/blocky) × Source Sans 3 (body)
- **Dual Color Palette**: Warm golds & stone browns transition to vibrant Minecraft greens & sky blues
- **Asymmetric Editorial Layouts**: 12-column grid with varying column spans, avoiding generic 3-column patterns
- **Scroll Reveal Animations**: IntersectionObserver-based progressive reveals
- **Parallax Effects**: Subtle background movement on the ancient hero

### Sections
1. **Hero** — Vishvakarma ancient temple scene
2. **Cinematic Transition** — Canvas pixelation from stone → blocks
3. **Farlands Hero** — Minecraft world reveal with hackathon meta
4. **Theme & Tracks** — 5 innovation tracks (AI/ML, Web3, AR/VR, Sustainability, Open)
5. **Prizes** — 3-tier prize cards with winner highlighted
6. **Timeline** — Alternating timeline of key dates
7. **How to Join** — 4-step numbered process
8. **Previous Edition** — Vishvakarma 2025 recap with stats
9. **CTA** — Registration call-to-action
10. **Footer** — Complete site navigation

### Technical
- **Pure vanilla HTML/CSS/JS** — No frameworks, no build step
- **Performance-optimized** — Canvas 2D transition (no heavy 3D libraries)
- **Fully responsive** — Desktop → Tablet → Mobile breakpoints
- **Single file** — `index.html` contains everything

## 🚀 Quick Start

```bash
# Just open the file in any modern browser
open index.html

# Or serve locally
python3 -m http.server 8000
# Visit http://localhost:8000
```

## 🎨 Creative Concept

> "From the Divine Forge to the Blocky Frontier"

The website tells a continuous story rather than presenting disconnected sections. As visitors scroll, they experience:
1. Standing in Vishvakarma's ancient temple
2. Watching the world dissolve and reassemble into blocks
3. Arriving in the vibrant, infinite Farlands ready to build

The transition uses a lightweight Canvas particle system where 2,400 individual blocks form progressively, creating a visually stunning but performant effect that runs smoothly on all devices.

## 📁 Project Structure

```
.
├── index.html    # Complete single-file website
└── README.md     # This file
```

---

*Built with passion. From Vishvakarma's forge to the Farlands' frontier.*
