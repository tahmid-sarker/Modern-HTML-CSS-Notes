# ARIA Attributes

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/09-Web-Accessibility/03-Aria-Attributes/)

## Overview

1. **Purpose**: Demonstrates different ARIA attributes to improve accessibility.
2. **ARIA Label**:

   * The menu `<a>` uses `aria-label="Open Menu"` with `role="button"` to provide a descriptive label for screen readers.
3. **ARIA Labelledby**:

   * The `<ul>` uses `role="listbox"` and `aria-labelledby="fruit-heading"` to associate the list with its heading (`<h2 id="fruit-heading">`).
   * `<li>` items use `role="option"` for selectable list items.
4. **ARIA Hidden**:

   * `<p aria-hidden="true">` hides content from assistive technologies.
   * `<p aria-hidden="false">` ensures content is accessible to screen readers.