# CSS Specificity

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/04-CSS-Basics/06-Specificity/)

## Overview

1. **Type Selector** → Targets HTML tags (e.g., `h1`).
2. **Class Selector** → Targets elements with a class (e.g., `.heading`).
3. **ID Selector** → Targets a unique element with an ID (e.g., `#heading`).
4. **Inline Style** → Style written directly in the element’s `style` attribute.
5. **!important** → Forces a style to override others.
6. **Specificity Hierarchy** → Inline style > ID > Class > Type selector.
7. **Conflict Resolution** → When multiple rules apply, the one with higher specificity wins; `!important` can override normal specificity.