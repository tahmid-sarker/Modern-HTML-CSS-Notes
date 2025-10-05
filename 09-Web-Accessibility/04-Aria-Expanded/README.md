# ARIA Expanded Accordion

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/09-Web-Accessibility/04-Aria-Expanded/)

## Overview

1. **Purpose**: Demonstrates using `aria-expanded` and `aria-hidden` to make an accessible accordion component.

2. **Accordion Header**:

   * `role="button"` makes the header a clickable button for assistive technologies.
   * `aria-controls="accordion-content"` associates the header with its content.
   * `aria-expanded="false"` indicates the content is initially collapsed.
   * `tabindex="0"` allows keyboard focus.

3. **Accordion Content**:

   * `role="region"` designates the content area as a landmark region.
   * `aria-labelledby="accordion-heading"` links the content to its header.
   * `aria-hidden="true"` hides content from screen readers initially.

4. **Interactive Behavior**:

   * Clicking the header toggles `aria-expanded` on the header and `aria-hidden` on the content.
   * JavaScript updates these attributes dynamically for accessibility compliance.