# Assignment 8 - Grid Template
---
## TASK 
- You need to complete **"Assignment 8 - Grid Template"** task, and in this assignment we have learned basic CSS Properties like:
1. **Flexbox Properties:**
- Flexbox, or the Flexible Box Layout, is designed to distribute space along a single axis (either horizontally or vertically) while allowing items to grow or shrink to accommodate the available space.
- Key Flexbox properties include:
  - `display: flex;`: This property is applied to a container element and establishes a flex context for its children.  
  - `flex-direction`: Determines the direction in which flex items are placed within the container. It can be set to `row` (default), `row-reverse`, `column`, or `column-reverse`.
  - `justify-content`: Controls the alignment of items along the main axis. Common values include `flex-start`, `flex-end`, `center`, `space-between`, and `space-around`.
  - `align-items`: Controls the alignment of items along the cross-axis. Common values include `flex-start`, `flex-end`, `center`, `baseline`, and `stretch`.
  - `flex-grow` and `flex-shrink`: These properties determine how items grow or shrink relative to each other when there's extra or insufficient space in the container.
2. **Grid Properties:**
- CSS Grid Layout is a two-dimensional layout system that allows you to create complex grid-based layouts with rows and columns.
- Key Grid properties include:
  - `display: grid;`: This property is applied to a container element to define it as a grid container.
  - `grid-template-columns` and `grid-template-rows`: These properties allow you to specify the size of grid tracks (rows and columns) in the grid. You can use fixed values (e.g., `100px`) or flexible values (e.g., `1fr`, which represents one fraction of the available space).
  - `grid-template-areas`: This property defines named grid areas within the grid container. You can assign elements to these areas using the `grid-area` property on child elements.
  - `grid-area`: Applied to child elements, this property assigns them to specific grid areas defined in `grid-template-areas`.
  - `grid-column` and `grid-row`: These properties allow you to explicitly specify which column and row a grid item occupies.
3. **Grid Template:**
- The grid template defines the structure of the grid, including the number and size of rows and columns, and optionally, named grid areas. It's set using `grid-template-columns`, `grid-template-rows`, and `grid-template-areas`.
4. **Grid Area:**
- A grid area is a named region within the grid container. These regions can be defined using the `grid-template-areas` property and assigned to grid items using the `grid-area` property. This approach simplifies layout management by giving meaningful names to areas of the grid.
5. **Grid Column:**
- The `grid-column` property allows you to explicitly specify which column a grid item occupies. You can set it using values like `grid-column-start`, `grid-column-end`, and shorthand `grid-column`. This is useful for precise control over item placement within the grid.

---
## CODE:

**index.html file & style.css file:**

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_28_37](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/3cd495d7-1130-4603-a833-d92714831b24)

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_28_58](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/df7bd464-8f44-421e-bb1d-aecdc5a2dc86)

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_29_28](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/836b5d63-3006-4a35-b7d1-8c53204eaf13)

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_29_47](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/c0f5ae8c-0f8a-423f-9916-a3932b439283)

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_30_03](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/0e508f92-a78c-4b2e-9ce1-46763eca5ba3)

---
## **EXPLANATION:**
1. The HTML file sets up the basic structure of the webpage, including meta tags for character encoding and viewport settings, as well as links to external stylesheets and a title for the page.
2. Inside the `<body>` element, there's a `<section>` element with the class `main-grid`. This section contains five `<article>` elements, each representing a testimonial or piece of content.
3. In the CSS file (`style.css`), a CSS reset is applied to remove default margin and padding from all elements and set `box-sizing` to `border-box` to ensure consistent box models.
4. The `body` element is styled to create a centered layout with a background color and a minimum height of 100 viewport heights. It also specifies a font-family using Google Fonts.
5. The `.same1` and `.same2` classes are used for common styles for text elements with different colors and padding.
6. Each `.item-X` class corresponds to a different article and defines their background colors. The first article (`item-1`) also has a background image and positioning.
7. The `.main-grid` class styles the main container for the articles. It creates a grid layout with specified gaps, grid areas, and adjusts the width and margins for responsiveness.
8. Individual `.article` elements are styled with padding, border-radius, and a box-shadow to create a card-like appearance.
9. The `nth-child` pseudo-class is used to assign specific grid areas (`grid-area`) to each article based on their order.
10. Media queries are used to adjust the grid layout for different screen widths, providing responsive design.
---
## OUTPUT:

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/603f5767-ac7d-485d-bd67-ace66ae3da77)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/43_Assignment-8_Grid_Template)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/43_Assignment-8_Grid_Template/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/43_Assignment-8_Grid_Template/index.html)
