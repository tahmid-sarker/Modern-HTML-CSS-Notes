# CSS Filters

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/08-Various-CSS-Features/02-Filters/)

## Overview

1. **Purpose** → Apply visual effects to images, text, or elements.
2. **Syntax** → `filter: effect(value);`
3. **Common Filters** →

   * `grayscale(%)` → Black & white effect.
   * `blur(px)` → Blur the element.
   * `brightness(%)` → Adjust lightness.
   * `contrast(%)` → Adjust contrast.
   * `drop-shadow(x y blur color)` → Shadow effect.
   * `hue-rotate(deg)` → Change hue.
   * `invert(%)` → Invert colors.
   * `opacity(%)` → Transparency.
   * `saturate(%)` → Color saturation.
   * `sepia(%)` → Sepia tone.

4. **Multiple Filters** → Chain with spaces:

   ```css
   filter: grayscale(100%) blur(5px);
   ```

5. **Reset** → Remove effects:

   ```css
   filter: none;
   ```