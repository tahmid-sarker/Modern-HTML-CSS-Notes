# CSS Pseudo Elements & Pseudo Classes

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/03-Pseudo-Elements/)

## Overview

1. **Purpose**: Demonstrates pseudo-elements and pseudo-classes for styling parts of elements or element states.

2. **Paragraph Styling**:

   * `p::first-letter` → styles the **first letter** of a paragraph.
   * `p::first-line` → styles the **first line** of a paragraph.
   * `p::selection` → styles text when it is **selected**.

3. **Form Inputs**:

   * `input:required` → styles inputs with the **required** attribute.
   * `input::placeholder` → styles the **placeholder text**.
   * `input::file-selector-button` → styles the **file input button**.

4. **List Items**:

   * `li::marker` → customizes the **list marker**, e.g., replaces the bullet with `👉`.

5. **Usage**: Allows fine-grained styling without adding extra HTML elements, improving UX and visual hierarchy.