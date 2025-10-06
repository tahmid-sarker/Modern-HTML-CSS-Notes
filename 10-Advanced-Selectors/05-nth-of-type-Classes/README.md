# nth-of-type

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/05-nth-of-type-Classes/)

## Overview

1. **First & Last Items**: `li:first-of-type`, `li:last-of-type` → bold.
2. **Specific Items**: `li:nth-of-type(3)`, `li:nth-of-type(6)` → bold + green.
3. **Even/Odd Items**: `li:nth-of-type(even)` → light green; `li:nth-of-type(odd)` → light yellow.
4. **Paragraphs**: `p:nth-of-type(2)` → bold; `p:nth-child(2)` → red.
5. **Pseudo-element**: `.container > p:first-of-type::first-letter` → larger red first letter.
6. **Key Concept**: `nth-of-type()` counts elements by type; `nth-child()` counts all children.