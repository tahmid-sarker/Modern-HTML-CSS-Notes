# CSS Custom Properties

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/08-Various-CSS-Features/01-Custom-Properties/)

## Overview

1. **Definition** → Variables defined in CSS using `--name` inside `:root` or selectors.

2. **Usage** → Access with `var(--name)` anywhere in CSS.

3. **Benefits** →

   * Centralized control for colors, sizes, spacing.
   * Easy theme changes (light/dark modes).
   * Consistency across elements.

4. **Example Variables** →

   ```css
   :root {
     --primary-color: lightblue;
     --secondary-color: lightcoral;
     --container-width: 600px;
   }
   ```

5. **Applying Variables** →

   ```css
   .container {
     max-width: var(--container-width);
   }
   .box-1 {
     background: var(--primary-color);
   }
   ```