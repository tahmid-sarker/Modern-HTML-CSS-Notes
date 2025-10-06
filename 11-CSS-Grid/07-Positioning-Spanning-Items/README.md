# Positioning Grid Items

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/11-CSS-Grid/07-Positioning-Spanning-Items/)

## Overview

1. **Purpose**: Control how grid items stretch or align across rows and columns in a CSS Grid layout.
2. **Grid Template**: Uses `grid-template` shorthand to set both rows and columns.
3. **Positioning**: Items can span multiple rows or columns for flexible, asymmetric layouts.
4. **Properties Used**:

   * `grid-column: span 2;` → Spans 2 columns
   * `grid-row: span 2;` → Spans 2 rows
   * `grid-template: repeat(3, 1fr) / repeat(3, 1fr);` → Defines a 3×3 grid.