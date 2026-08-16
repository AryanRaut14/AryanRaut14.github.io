# Terminal-Style AI / LLM Engineer Portfolio

A minimalist, high-performance developer portfolio inspired by cyberpunk terminals, CRT scanlines, and developer command-line interfaces. Built to showcase projects in autonomous agents, Model Context Protocol (MCP), and local-first LLM engineering.

---

## Features

* **Terminal Boot Sequence:** Animated CLI boot sequence simulating an autonomous agent runtime initialization.
* **Cyberpunk / CLI Aesthetic:** Custom color palette with amber/cyan neon accents, scanline overlays, and a rain background layer.
* **Zero Dependencies:** Pure semantic HTML5, modern CSS3 (custom properties, backdrop filters, CSS Grid/Flexbox), and vanilla JavaScript.
* **Fully Responsive:** Fluid typography (`clamp()`) and adaptive layouts optimized for mobile and desktop screens.
* **Accessible & Motion-Conscious:** Implements full keyboard focus styling and respects user preferences via `@media (prefers-reduced-motion: reduce)`.

---

## 📁 File Structure

```text
.
├── index.html              # Core HTML structure & semantic layout
├── style.css               # Theme tokens, scanline overlays, and responsive styling
├── script.js               # IntersectionObserver scroll animations and CLI interactions
└── assets/
    ├── images/
    │   ├── favicon.svg     # SVG favicon
    │   ├── favicon.ico     # Fallback favicon
    │   └── rainbg.gif      # Background rain overlay
    └── resume.pdf          # Downloadable resume