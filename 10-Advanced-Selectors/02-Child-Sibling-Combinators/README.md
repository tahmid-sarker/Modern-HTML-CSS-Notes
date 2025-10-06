# CSS Child & Sibling Combinators

* [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/10-Advanced-Selectors/02-Child-Sibling-Combinators/)

## Overview

1. **Purpose**: Demonstrates using CSS combinators to style elements based on hierarchy and sibling relationships.

2. **Child Combinator (`>`)**:

   * `.container > p` → styles only `<p>` elements that are **direct children** of `.container`.
   * `.container > ul` → styles only `<ul>` that are **direct children**.
   * `.container > a` → styles only `<a>` that are **direct children**.

3. **Adjacent Sibling Combinator (`+`)**:

   * `.container h1 + a` → styles the `<a>` **immediately after** an `<h1>`.

4. **General Sibling Combinator (`~`)**:

   * `.container h1 ~ a` → styles **all `<a>` siblings that follow** an `<h1>`.
   * `.container > ul ~ div` → styles all `<div>` siblings that follow a **direct child `<ul>`**.

5. **Usage**: Useful for applying styles dynamically based on element relationships without adding extra classes or IDs.