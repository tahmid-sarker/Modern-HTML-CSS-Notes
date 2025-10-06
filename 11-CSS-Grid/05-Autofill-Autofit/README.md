# autofill & autofit

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/11-CSS-Grid/05-Autofill-Autofit/)

## Overview

1. **Purpose**:
   Shows how `auto-fit` and `auto-fill` make grid layouts **responsive** by automatically adjusting the number of columns based on available space.

2. **Key Properties**:

   * `repeat(auto-fit, minmax(100px, 1fr))`: Expands items to fill extra space and adapts to different screen widths.
   * `minmax(100px, 1fr)`: Ensures each grid item is at least 100px wide but can grow to fill remaining space.

3. **auto-fit vs auto-fill**:

   * **auto-fit**: Collapses empty tracks, letting existing items stretch.
   * **auto-fill**: Keeps empty tracks, preserving the grid structure.

4. **Responsive Design**:
   
   * Items wrap automatically, creating flexible layouts ideal for **galleries**, **cards**, and **product grids**.