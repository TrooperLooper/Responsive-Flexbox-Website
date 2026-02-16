# Responsive Flexbox Site

A responsive frontend project built as part of a school assignment to practice layout and responsiveness using CSS Flexbox. The site demonstrates a mobile-first, accessible layout with flexible components that adapt across common breakpoints.

---

## Project overview

This project is a small static website that showcases how to build responsive layouts using modern CSS (Flexbox). The goal was to create a clean, accessible, and responsive UI that works well on phones, tablets, and desktops without relying on CSS frameworks.

<img src="screenshot_genesis.png" alt="Screenshot of landing page" height="300">

---

## What I worked on

- Built a mobile-first responsive layout using CSS Flexbox.
- Implemented a responsive navigation bar that collapses/adjusts across breakpoints.
- Created a hero section with a flexible layout that reflows from stacked (mobile) to side-by-side (desktop).
- Implemented a card/grid section using flex-wrap and responsive flex-basis for equal-height cards.
- Styled a footer that sticks to the bottom on short pages and behaves responsively on small screens.
- Used CSS custom properties (variables) for colors, spacing, and typography to keep styles consistent.
- Ensured semantic HTML5 structure (header, main, nav, section, footer).
- Added accessibility improvements: meaningful alt attributes, visible focus states, keyboard-friendly navigation, and proper heading order.
- Performed cross-browser checks on Chromium-based browsers and Firefox, and iterated on responsive breakpoints.
- Added comments in CSS and HTML to explain key layout decisions and flexbox properties.

---

## Technologies

- HTML5 (semantic markup)
- CSS3 (Flexbox, custom properties)
- Vanilla JavaScript (optional small behaviors, e.g., mobile nav toggle)
- Optional: small build/dev server (see How to run)

---

## Key layout & flexbox techniques used

- Container model: display: flex on major layout containers (nav, hero, content grid, footer).
- Flex-direction: switched between column (mobile) and row (desktop) for reflow.
- Flex-wrap: used for card grids to allow wrapping into multiple rows.
- Flex-grow / flex-shrink / flex-basis: used to control how cards and sections distribute space.
- align-items & justify-content: used for vertical and horizontal alignment of elements.
- order: used sparingly to adjust visual order on different breakpoints without changing DOM order.
- Responsive breakpoints (suggested):
  - Mobile: up to 600px
  - Tablet: 601px — 900px
  - Desktop: 901px and up

---

## Accessibility & Best Practices

- Semantic HTML structure (header, nav, main, section, footer).
- Alt text for images and descriptive link text.
- Focus-visible/tailored focus styles so keyboard users can navigate.
- Sufficient color contrast for text and interactive elements.
- Simple, clear tab order and skip-to-content link (add if not already present).
- Reduced motion preference respected (prefers-reduced-motion media query).

---

## How to run locally

This is a static site — you can open `index.html` directly in the browser, or run a simple local server.

Option 1 — open directly:

- Double-click `index.html` or right-click → Open with your browser.

Option 2 — run a local static server (recommended for consistent resource loading):

- Python 3:
  - `python -m http.server 8000`
  - Open http://localhost:8000
- Node (if you have `live-server` installed):
  - `npx live-server` (or `live-server`)
