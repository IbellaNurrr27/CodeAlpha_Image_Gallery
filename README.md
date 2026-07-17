# EXPOSÉ — An Exhibition (Interactive Image Gallery)

A minimalist, high-fidelity filmstrip image gallery built using vanilla web technologies. The project simulates a high-end photography exhibition layout focusing on 35mm film aesthetics, smooth interactive transitions, and real-time visual post-processing presets.

**Live Demo:** [https://ibellanurrr27.github.io/CodeAlpha_Image_Gallery/](https://ibellanurrr27.github.io/CodeAlpha_Image_Gallery/)

## Features

- **Dynamic Interactive Filmstrip:** Horizontal scrollable layout with smooth drag-to-explore mechanics built into the gallery wrapper.
- **Categorized Reels (Filtering):** Instant, seamless gallery filtering by theme (Nature, Urban, Portrait, Architecture) with automated asset counter updates and a fallback empty state layout.
- **Advanced Lightbox Modal:** 
  - Dynamic cache-busting image loading to prevent visual lag or stale browser caching on asset swapping.
  - Full looping keyboard navigation (`Left Arrow`, `Right Arrow`, `Escape` to close).
  - Screen-width smart filtering integration—next and previous switches automatically bypass items hidden by active category filters.
- **Aesthetic Post-Processing Presets:** Real-time CSS-driven visual filters allowing users to swap themes instantly (Default Chrome, Noir High-Contrast B&W, Vintage Sepia, Chromium Shift).
- **Immersive Details:** Custom reactive cursor tracking with variable sizing states, animated grain overlay texture, and a synchronized real-time local clock display.

## Tech Stack

- **HTML5:** Semantic architecture with dynamic inline-SVG noise filtering layers.
- **CSS3:** Component variables for real-time asset post-processing, custom scroll-snapping architectures, and smooth acceleration curves (`cubic-bezier`).
- **JavaScript (ES6+):** Pure vanilla DOM manipulation, pointer tracking variables for desktop mouse physics, and linear loop array processing algorithms.

## Getting Started

To view the project locally:

1. Clone this repository:
   ```bash
   git clone [https://github.com/IbellaNurrr27/CodeAlpha_Image_Gallery.git](https://github.com/IbellaNurrr27/CodeAlpha_Image_Gallery.git)
