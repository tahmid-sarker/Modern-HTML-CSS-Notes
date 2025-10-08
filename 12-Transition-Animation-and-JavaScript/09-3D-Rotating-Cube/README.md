# 3D Rotating Cube – CSS Animation

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/12-Transition-Animation-and-JavaScript/09-3D-Rotating-Cube/)

## Overview

* **Container**: `200px` square, centered, with `perspective: 1000px` for 3D.
* **Cube**: `.cube` uses `transform-style: preserve-3d` and rotates infinitely with `@keyframes rotateCube`.
* **Faces**: Six `.face` divs positioned in 3D using `translateZ(100px)` and rotations (front, back, right, left, top, bottom).
* **Styling**: Each face has a unique background and centered text.