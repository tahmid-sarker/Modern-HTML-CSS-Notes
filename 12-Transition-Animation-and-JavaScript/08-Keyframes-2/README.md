# CSS Keyframes Animation – Loader Bounce & Spin

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/12-Transition-Animation-and-JavaScript/08-Keyframes-2/)

## Overview

1. **Container**:

   * Full viewport height (`100vh`) and flexbox centering (`justify-content: center; align-items: center;`) for the loader.

2. **Loader**:

   * A central element (`.loader`) with `80x80px` size.
   * Rotates continuously using `@keyframes spin`:

     ```css
     @keyframes spin {
       100% { transform: rotate(360deg); }
     }
     ```

3. **Pseudo-elements**:

   * `.loader::before` and `.loader::after` create two small circles (30x30px).
   * Positioned left and right relative to the loader center.
   * Animated with `@keyframes bounce` to move vertically:

     ```css
     @keyframes bounce {
       0%, 100% { transform: translateY(0); }
       50% { transform: translateY(-30px); }
     }
     ```

4. **Colors**:

   * Left circle: red (`#e74c3c`).
   * Right circle: blue (`#3498db`).

5. **Animation Flow**:

   * Loader spins infinitely (`animation: spin 2s linear infinite`).
   * Circles bounce up and down infinitely (`animation: bounce 2s infinite ease-in-out`).