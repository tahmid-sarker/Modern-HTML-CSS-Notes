# Progress & Meter

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/03-More-HTML-Elements/09-Progress-and-Meter)

1. **`<progress>`** → Shows task progress (e.g., file upload/download).
   * `max` → Total work (default 1 if not set).
   * `value` → Current progress.
   * Text inside acts as fallback for browsers that don’t support `<progress>`.

2. **`<meter>`** → Represents a scalar measurement (like fuel, battery, score).
   * `min` → Minimum value.
   * `max` → Maximum value.
   * `value` → Current measurement.
   * `low`, `high`, `optimum` → Indicate ranges (good, bad, warning).

3. **Styling** → Both `<progress>` and `<meter>` can be styled with CSS (browser support may vary, e.g., `::-webkit-meter-optimum-value`).