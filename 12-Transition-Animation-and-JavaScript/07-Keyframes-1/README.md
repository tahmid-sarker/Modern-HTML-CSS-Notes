# CSS Keyframes Animation

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/12-Transition-Animation-and-JavaScript/07-Keyframes-1/)

## Overview

1. **Animated Box**

  * `.box` element transitions from a small coral square to a larger light-blue block.
  * Moves vertically from the top of the viewport to `100vh`.
  * Smooth animation with `ease-out` timing function.

2. **Animation Properties**

  * `animation-duration: 2s;` – Total time for one cycle.
  * `animation-fill-mode: forwards;` – Keeps the final state after animation.
  * `animation-iteration-count: infinite;` – Loops the animation indefinitely.
  * Optional: `animation-delay`, `animation-direction` for more control.

3. **Keyframes**

  * Defines start (`from`) and end (`to`) states.
  * Animates **width**, **background-color**, and **position** simultaneously.