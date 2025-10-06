# Image Overlay with `::before`

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/07-Image-Overlay/)

## Overview

1. **Purpose**: Create a **dark overlay** on a background image to improve text readability and visual appeal.

2. **Hero Section**:

   * `background: url(...) center/cover no-repeat;` sets the hero image.
   * `position: relative` on `.hero` allows positioning of pseudo-elements inside it.

3. **Overlay**:

   * `.hero::before` adds a **semi-transparent layer** over the image.
   * Uses `position: absolute; top: 0; left: 0; width: 100%; height: 100%`.
   * `background: rgba(0, 0, 0, 0.5)` creates the dark overlay effect.

4. **Text & Button**:

   * Placed inside a `.container` with `z-index` implicitly above the overlay.
   * Centered vertically and horizontally using `flex` layout.
   * Button hover uses opacity for subtle interaction.

5. **Responsive**:

   * Media queries adjust **font sizes and button sizes** for smaller screens (`max-width: 768px`).

6. **Key Takeaways**:

   * Using `::before` allows **non-destructive overlays** without extra HTML.
   * Combines **flexbox**, **pseudo-elements**, and **RGBA colors** for elegant UI effects.