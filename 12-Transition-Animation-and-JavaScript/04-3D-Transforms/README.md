# CSS 3D Transforms (Card Flip)

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/12-Transition-Animation-and-JavaScript/04-3D-Transforms/)

## Overview

1. **Perspective**: The `.card-container` sets `perspective: 1000px` to give a 3D effect.
2. **3D Transform Style**: `.card` uses `transform-style: preserve-3d` so its children are positioned in 3D space.
3. **Front & Back Faces**:

   * `.front` is the front side of the card.
   * `.back` is rotated `180deg` along the Y-axis.
4. **Card Flip**: On hover, `.card` rotates `rotateY(180deg)` to reveal the back side.
5. **Backface Visibility**: `backface-visibility: hidden` hides the reverse side of each face while flipping.