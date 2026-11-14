# Alchemy Circles Generator

A lightweight, client-side procedural transmutation circle generator built with pure HTML, CSS, and SVG. Inspired by [CiaccoDavide/Alchemy-Circles-Generator](https://github.com/CiaccoDavide/Alchemy-Circles-Generator), this modernization eliminates server-side dependencies and desktop compilation steps, running entirely in the browser with real-time parameter controls and instant vector/raster exports.

## Live Demo

**[Launch Alchemy Circles Generator](https://lexanger.github.io/alchemy-circles/)**

---

## Features

- **Deterministic Seed Engine:** Powered by `cyrb128` string hashing and a `Mulberry32` PRNG—any custom word, phrase, or seed string reproduces the exact same geometric structure.
- **Multi-Layered Procedural SVG Architecture:**
  - Outer containment rings with calibrated degree ticks and double-ruled borders.
  - Rotating alchemical, planetary, and runic glyph rings.
  - Nested geometric polygons (triangles through dodecagons) and intersecting star webs.
  - Orbital sub-circles housing bespoke planetary sigils and a central focal seal.
- **Real-Time Customization:** Dynamically adjust layer depth, polygon symmetry (`3`–`12` vertices), glyph density, orbital nodes, stroke weight, aether glow intensity, and dual-ink color presets.
- **High-Resolution Export:** Download crisp, infinitely scalable `.svg` files or `2048×2048` transparent `.png` renders directly from the browser.
- **Zero-Dependency & Offline Ready:** Packaged inside a single self-contained HTML file with no external CDNs, fonts, or runtime frameworks.

---

## Running Locally or Offline

Because all procedural geometry and file exports execute 100% client-side, you can run this tool anywhere:

1. **Direct File Execution:** Download `index.html` and double-click it to open directly in any modern browser (`file://`).
2. **Install as a PWA (Mobile & Desktop):** Open the [live link](https://lexanger.github.io/alchemy-circles/) in Chrome, Edge, or Safari and select **Install App** / **Add to Home Screen** to cache it for offline use.

---

## Credits & Attribution

- Procedural design concepts inspired by [CiaccoDavide/Alchemy-Circles-Generator](https://github.com/CiaccoDavide/Alchemy-Circles-Generator).
