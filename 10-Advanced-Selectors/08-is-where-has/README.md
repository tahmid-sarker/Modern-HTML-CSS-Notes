# CSS `:is()`, `:where()`, and `:has()`

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/08-is-where-has/)

## Overview

1. **Purpose**: Demonstrate **modern CSS relational and grouping pseudo-classes** for concise and powerful styling.

2. **`:is()`**:

   * Acts like a shorthand for multiple selectors.
   * Example:

     ```css
     .container :is(h1, h2, p) { 
        color: blue; 
        }
     ```

     applies `color: blue` to all `h1`, `h2`, and `p` inside `.container`.

3. **`:where()`**:

   * Similar to `:is()` but **zero specificity**, so it won’t override other styles unintentionally.
   * Example:

     ```css
     .container :where(h1, h2, p) { 
        color: green; 
        }
     ```

4. **`:has()`**:

   * Selects elements **based on their descendants or siblings**.
   * Example:

     ```css
     .container:has(h1 span) { 
        color: red; 
        }
     h1:has(+ h2) { 
        color: blue; 
        }
     ```

     * `.container:has(h1 span)` targets any `.container` containing an `h1` with a `span`.
     * `h1:has(+ h2)` targets an `h1` **directly followed** by an `h2`.

5. **Key Takeaways**:

   * `:is()` and `:where()` simplify **grouping multiple selectors**.
   * `:has()` enables **parent or relational selection**, opening new possibilities previously only possible with JavaScript.
   * These modern selectors improve **readability, maintainability, and reduce repetitive CSS**.