# Responsive Hamburger Menu

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/12-Transition-Animation-and-JavaScript/06-Hamburger-Menu/)

## Overview

1. **HTML Structure**:

   * Desktop menu in `.main-menu` with `<ul>` links.
   * Mobile menu in `.mobile-menu` with a toggle button (hamburger icon) and a hidden menu list.

2. **CSS Styling**:

   * **Desktop (`>768px`)**:

     * `.main-menu` displayed as a horizontal flex list.
     * `.mobile-menu` hidden.
   * **Mobile (`≤768px`)**:

     * `.main-menu` hidden.
     * `.mobile-menu` displayed with `.mobile-menu-toggle` (hamburger icon).
     * `.mobile-menu-items` initially offscreen (`transform: translateX(100%)`) and slides in when `.active` class is added.

3. **JavaScript Functionality**:

   * On page load, select `.mobile-menu-toggle` and `.mobile-menu-items`.
   * Add a click listener on the toggle button:

     ```js
     mobileMenu.classList.toggle('active');
     ```

     This adds/removes the `.active` class, triggering the CSS slide-in animation.

4. **Outcome**:

   * Desktop: horizontal navigation.
   * Mobile: hamburger menu toggles a full-screen vertical menu with smooth slide animation.