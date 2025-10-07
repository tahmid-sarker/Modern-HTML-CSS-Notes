# CSS Transitions Example

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/12-Transition-Animation-and-JavaScript/01-Creating-Transitions/)

## Overview

1. **Purpose**: Smoothly animate changes in CSS properties when an element changes state (like `:hover`).

2. **Transition Property**:

   ```css
   transition: all 0.8s ease-in-out;
   ```

   * `all` → applies to all animatable properties
   * `0.8s` → duration of the transition
   * `ease-in-out` → acceleration/deceleration curve

3. **Hover Effect**: The button changes multiple properties when hovered:

   * `background-color` → from `#007bff` to `#0056b3`
   * `color` → from white to yellow
   * `width` → from 200px to 400px
   * `border-radius` → from 5px to 50px
   * `opacity` → becomes semi-transparent
   * `box-shadow` → adds subtle shadow

4. **Key Takeaways**:

   * Use `transition` for smooth visual feedback.
   * Animating multiple properties can create a dramatic effect.
   * Prefer animating properties like `opacity`, `transform`, `background-color` for better performance.