# JS & CSS Interaction – Toggle Classes

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/12-Transition-Animation-and-JavaScript/05-JS-and-CSS/)

## Overview

1. **HTML Structure**:

   * A button with ID `button` inside a `.container`.
   * A heading `<h1>` above the button.

2. **CSS Classes**:

   * `.dark`: Changes the page background to dark and text to white.
   * `.yellow`: Changes the heading text color to yellow.

3. **JavaScript Functionality**:

   * Select the button and heading using `querySelector`.
   * Add a `click` event listener to the button.
   * On click:

     * `document.body.classList.toggle('dark')` → toggles dark mode.
     * `heading.classList.toggle('yellow')` → toggles yellow text for the heading.

4. **Outcome**:
   Clicking the button switches between normal and dark mode while changing the heading color dynamically.