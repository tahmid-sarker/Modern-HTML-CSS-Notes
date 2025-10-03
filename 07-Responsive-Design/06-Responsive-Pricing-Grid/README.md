# CSS Pricing Cards

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/07-Responsive-Design/06-Responsive-Pricing-Grid/)

## Overview

1. **Layout**

   * `.pricing` uses `flex` to arrange cards horizontally with gaps.
   * `flex-wrap: wrap` ensures responsiveness on smaller screens.
   * Cards have equal width using `flex: 1`.

2. **Cards**

   * `.card` → White background, rounded corners, padding, box-shadow.
   * Headings `<h2>` have colored backgrounds; `card-pro` & `card-enterprise` use **linear gradients**.

3. **Text & Prices**

   * `.price` → Large bold numbers.
   * `.dollar` & `.month` → Smaller text positioned near price.
   * `.price-info` → Uppercase labels for plan type.

4. **Buttons**

   * `.btn` → Block buttons with border, rounded corners, hover effect.
   * `.btn-primary` → Inverted colors on hover.

5. **Lists**

   * `<ul>` → Plan features, icons colored with green checkmarks.
   * Left-aligned inside cards.

6. **Responsive**

   * `@media (max-width: 768px)` → Cards stack vertically.
   * Padding & margin adjusted for smaller screens.