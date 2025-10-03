# Media Queries

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/07-Responsive-Design/05-Media-Queries/)

## Overview

1. **Purpose** → Apply CSS styles based on screen size or device characteristics.
2. **Syntax** →

    ```css
    @media (max-width: 768px) { 
    /* styles */ 
    }
    ```

3. **Common breakpoints** →

   * Widescreen: `1200px+`
   * Desktop/Normal: `992px`
   * Tablet: `768px`
   * Smartphone: `576px`
4. **Orientation** → `orientation: landscape` or `portrait`.
5. **Height-based** → `max-height` / `min-height`.
6. **Combine conditions** → e.g., `@media (min-width: 768px) and (max-width: 991px)`.