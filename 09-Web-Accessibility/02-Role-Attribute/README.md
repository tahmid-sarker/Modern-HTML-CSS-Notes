# ARIA Role Attributes

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/09-Web-Accessibility/02-Role-Attribute/)

## Overview

1. **Purpose**: Demonstrates the use of ARIA `role` attributes to enhance accessibility for screen readers.
2. **Banner**: `<header>` uses `role="banner"` to identify site-wide header content.
3. **Button Roles**:

   * Anchor `<a>` uses `role="button"` to behave as a button.
   * Image `<img>` uses `role="button"` with `aria-label` and `tabindex="0"` for keyboard accessibility.
4. **Listbox & Options**:

   * `<ul>` uses `role="listbox"` with `aria-label`.
   * `<li>` items use `role="option"` for accessible selection.
5. **Region**: `<div>` uses `role="region"` with `aria-label` to mark a landmark section (FAQ).
6. **Alert**: `<div>` with `role="alert"` notifies users of dynamic changes (e.g., “Post Saved”).
7. **Interactivity**: JavaScript click listener on the image triggers an alert, demonstrating interactive ARIA usage.