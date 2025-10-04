# Sticky Navbar with Scroll Transparency

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/08-Various-CSS-Features/04-Sticky-Navbar/)

1. **Sticky Navbar**

   * `position: sticky; top: 0;` keeps the header visible at the top while scrolling.
   * `z-index: 1000;` ensures it stays above other content.

2. **Scroll-Based Transparency**

   * A CSS class `.transparent` reduces the background opacity using `rgba` and a CSS variable `--header-transparency`.
   * JavaScript toggles this class when `window.scrollY > 0`.

3. **Navigation**

   * Flexbox layout for horizontal menu items: `display: flex; justify-content: center; gap: 3rem;`.
   * Smooth scrolling enabled via `scroll-behavior: smooth`.

4. **Responsive Layout**

   * `max-width: 700px; margin: 0 auto;` keeps the container centered.
   * Images scale with `max-width: 100%;`.

5. **Header Styling**

   * Gradient background: `linear-gradient(45deg, #f00, #00f);`.
   * Color transitions dynamically based on scroll.