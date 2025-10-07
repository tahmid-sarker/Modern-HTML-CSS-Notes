# Grid Layout with Media Queries

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/11-CSS-Grid/10-Grid-and-Media-Queries/)

## Overview

1. **Grid Layout**

  * Desktop: Two-column layout (`grid-template-columns: 2fr 1fr`) with multiple rows.
  * Header and Footer span both columns using `grid-column: span 2`.
  * `nav`, `search`, `main`, and `aside` occupy individual cells.

2. **Responsive Design**

  * For screens ≤768px, layout switches to a **single-column** grid.
  * Header and Footer adjust to `grid-column: span 1` automatically.
  * `grid-template-rows` adjusts for stacked content.

3. **Styling**

  * Header, nav, and footer have distinct background colors.
  * Main and aside sections use lighter backgrounds for contrast.
  * Padding ensures readable spacing.