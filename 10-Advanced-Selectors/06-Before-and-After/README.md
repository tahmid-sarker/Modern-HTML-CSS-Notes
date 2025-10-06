# CSS `::before` and `::after`

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/06-Before-and-After/)

## Overview

1. **Purpose**: Add **content or decorative elements** before or after an element without changing the HTML structure.

2. **Syntax**:

   * `element::before { ... }` → inserts content **before** the element’s content.
   * `element::after { ... }` → inserts content **after** the element’s content.

3. **Common Uses**:

   * Adding labels, icons, or symbols.
   * Styling required form fields (`label.is-required::after { content: '*'; }`).
   * Decorative text or shapes (`h2::before { content: 'Hello'; }`).

4. **Content Property**:

   * Must be used with `content` property.
   * Can be text (`'Hello'`), empty (`''`), or symbols (`'★'`).

5. **Styling**:

   * Can apply **color, margin, font-size, position**, and other CSS properties.
   * Often combined with `position: absolute` for decorative purposes.

6. **Example in Project**:

   * `h2::before` adds "Hello" before heading text.
   * `label.is-required::after` adds a red asterisk for required fields.
   * `h2::after` can create decorative blocks with size, color, and positioning.