# CSS Attribute Selectors

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/01-Attribute-Selectors/)

## Overview

1. **Purpose**: Demonstrates how to target HTML elements using attribute selectors for precise styling.

2. **Form & Input**:

   * `[type='email']` → green border.
   * `[name='name']` → blue border.
   * `[type='text'][id='name']` → light blue background.
   * `[required]` → red border for required inputs.
   * `[type='password'][maxlength='8']` → green background.
   * `[type='submit']` → purple submit button.

3. **Links**:

   * `[href^='#']` → links starting with `#` → yellow color.
   * `[href$='.com']` → links ending with `.com` → light green color.
   * `[href*='traversy']` → links containing "traversy" → underlined text.

4. **Buttons**: All buttons get a base style with hover effect, separate attribute-based styles override where specified.

5. **Navigation**: Inline horizontal list of links styled with background, color, and hover effects.