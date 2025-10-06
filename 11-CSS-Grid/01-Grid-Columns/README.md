# Grid Columns

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/11-CSS-Grid/01-Grid-Columns/)

## Overview

1. **Purpose**: Demonstrates how to create a **grid layout with multiple columns** using CSS Grid.

2. **Grid Setup**:

   * Container uses `display: grid`.
   * `grid-template-columns: 600px 1fr 1fr` creates:

     * First column with a fixed width of 600px.
     * Two flexible columns that adjust to the remaining space.

3. **Gap Control**:

   * `gap: 20px` adds equal spacing between both rows and columns.

4. **Grid Items**:

   * Each item has a **coral background**, padding, and centered text.
   * Uniform sizing and spacing create a **clean grid structure**.

5. **Responsive Tip** *(Optional)*:

   * Replace fixed values with `repeat(auto-fit, minmax(...))` for **responsive behavior**.