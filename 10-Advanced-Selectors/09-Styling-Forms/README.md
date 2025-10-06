# Styling Forms

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/09-Styling-Forms/)

## Overview

1. **Purpose**: Demonstrates clean, modern styling for HTML forms using CSS with **focus, validation, and placeholder effects**.

2. **Container**:

   * Centered with **flexbox**, white background, rounded corners, and subtle shadow.
   * Max width set for compact, readable layout.

3. **Form Fields**:

   * `input[type='text']`, `input[type='email']`, and `textarea` are styled uniformly.
   * **Focus state**: changes outline and background for visual feedback.
   * `placeholder` styling with color and height adjustments.

4. **Validation States**:

   * `:invalid` inputs get **red borders**, `:valid` get **green borders**.
   * Provides immediate **user feedback** while filling out the form.

5. **Submit Button**:

   * Styled with primary color, rounded corners, and hover effect.
   * Maintains consistent **font and padding** with the rest of the form.

6. **Form Interaction**:

   * `form:focus-within` changes background slightly when any field is focused, enhancing UX.

7. **Responsive & Accessibility**:

   * Uses **inherit font**, clear labels, and placeholder text.
   * Form adapts well to compact container widths.