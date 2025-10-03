# Container Queries

- [**View Live**](https://tahmid-sarker.github.io/Modern-HTML-CSS-Notes/07-Responsive-Design/08-Container-Queries/)

## Overview

1. **Purpose** → Apply CSS styles based on the size of a container instead of the viewport.
2. **Enable container** →

    ```css
    main {
    container-type: inline-size;
    container-name: main;
    }
    ```

3. **Query syntax** →

    ```css
    @container main (max-width: 992px) {
    /* styles */
    }
    ```

4. **Use cases** → Adjust child elements when the container shrinks or grows.
5. **Support multiple containers** → Each container can have its own rules.