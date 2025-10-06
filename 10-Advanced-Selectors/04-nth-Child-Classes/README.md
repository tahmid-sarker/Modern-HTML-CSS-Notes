# CSS Child Selectors (`:first-child`, `:last-child`, `:nth-child`)

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/04-nth-Child-Classes/)

## Overview

1. **Purpose**: Targets elements based on their position within a parent, allowing precise styling of specific children.

2. **First & Last Child**:

   * `:first-child` → styles the **first element** in its parent.
   * `:last-child` → styles the **last element** in its parent.

3. **Nth-Child**:

   * `:nth-child(n)` → targets the **nth element**.
   * `:nth-child(odd)` → styles **odd-numbered children**.
   * `:nth-child(even)` → styles **even-numbered children**.
   * `:nth-child(4n)` → styles **every 4th child**.

4. **Only Child**:

   * `:only-child` → styles an element if it is the **only child** of its parent.

5. **Usage**: Useful for lists, grids, and tables where styling depends on position rather than class names.