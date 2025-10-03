# Container Units

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/07-Responsive-Design/09-Container-Units/)

## Overview

1. **Container units (`cqw`, `cqh`)** → Relative to the container’s width/height, not the viewport.
2. **`container-type`** → Define a container that can be queried:

   ```css
   main { container-type: inline-size; }
   ```
3. **Responsive sizing** → Use `width: 50cqw` or `height: 50cqh` for elements relative to the container.
4. **Media queries with container queries** → Adjust layout when container size changes:

   ```css
   @container (max-width: 600px) {
     .card { width: 95cqw; }
   }
   ```
5. **Benefits** → Better modularity and responsiveness inside components, independent of viewport.