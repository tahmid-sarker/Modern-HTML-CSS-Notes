# repeat() & minmax()

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/11-CSS-Grid/02-Repeat-Minmax-Functions/)

## Overview

1. **Purpose**:
   Showcases the use of **`repeat()`** and **`minmax()`** functions in CSS Grid for flexible, responsive layouts.

2. **Grid Structure**:

   * Uses `display: grid` to create a grid layout.
   * `grid-template-columns: repeat(3, minmax(300px, 1fr))` automatically generates **3 columns**, each:

     * **Minimum width**: 300px
     * **Maximum width**: 1 fraction of remaining space

3. **Flexibility**:

   * Ensures each grid item **stays readable** and **adjusts smoothly** to different screen sizes.
   * Prevents items from shrinking below the minimum width.

4. **Design**:

   * Each item has a **coral background**, border, padding, and centered text for clarity.