# Assignment 9 - Grid Structure
---
## TASK 
- You need to complete **"Assignment 9 - Grid Structure** task, and in this assignment we have learned basic CSS Properties like:
1. **Flexbox Properties**:
    1. `display: flex;`
       - Turns the container's direct children into flex items.
       - Used for one-dimensional layouts (row or column).
    2. `justify-content`
       - Aligns flex items along the main axis (horizontally by default).
       - Values: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`.
    3. `align-items`
       - Aligns flex items along the cross-axis (vertically by default).
       - Values: `flex-start`, `flex-end`, `center`, `stretch`.
    4. `flex-direction`
       - Determines the direction of the main axis.
     - Values: `row` (default), `row-reverse`, `column`, `column-reverse`.
2. **Grid Properties**:
    1. `display: grid;`
       - Defines a container as a grid container.
       - Used for two-dimensional layouts with rows and columns.
    2. `grid-template`
       - Defines the grid structure using `grid-template-columns` and `grid-template-rows`.
       - Example: `grid-template-columns: 1fr 2fr 1fr;`
    3. `grid-area`
       - Assigns a name to a grid item.
       - Used with `grid-template-areas` to place items in specific grid cells.
    4. `grid-column`
       - Places a grid item in specific columns of the grid.
       - Example: `grid-column: 2 / 4;`
---
## CODE:
**index.html file & style.css file:**

![index html - Geekster_Assignments - Visual Studio Code 25-08-2023 09_02_44](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/9c4c1e9f-54fc-493e-a3df-640be193d807)

![index html - Geekster_Assignments - Visual Studio Code 25-08-2023 09_03_11](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/ca168700-e0eb-4312-900d-77bfb75a5076)

![index html - Geekster_Assignments - Visual Studio Code 25-08-2023 09_03_30](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/f9b41f74-4552-4bca-8916-080cb6109d05)

![Captures 25-08-2023 09_05_33](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/30b667b9-fc6a-4534-b077-9f773a9b5162)

---
## **EXPLANATION:**
1. In your HTML file (`index.html`):
   - You start with the usual HTML document structure with a `<!DOCTYPE html>` declaration and `<html>`, `<head>`, and `<body>` elements.
   - In the `<head>` section, you define the document's metadata, including the character set, viewport settings, and the title of your webpage.
   - You link an external stylesheet named "style.css" to your HTML file using the `<link>` element. This connects your HTML file to the CSS file for styling.
2. In your CSS file (`style.css`):
   - You begin by setting the `margin` property for the `body` element to 0%, which removes any default margins around the body content.
   - You define a CSS class called `.container`, which is applied to a `div` element in your HTML. This class sets up a grid layout with specific column and row properties.
   - Within the `.container` class, you use the `display: grid;` property to create a grid layout. This grid has 16 columns, each spanning 6.25% of the container's width, and 6 rows, each with a height of 6rem. The container itself has a fixed height of 36rem and a white border on a black background.
   - You define classes like `.g1`, `.g2`, `.g3`, and so on, to target specific grid items within the container. These classes are used to position and style individual grid items.
   - Each grid item has properties like `grid-area`, `grid-column`, and `grid-row` set to position them within the grid.
   - You define the `.nav` class within the `.g1` grid item to style a navigation bar inside it. This class sets up a flex container with evenly spaced buttons.
   - Buttons within the `.nav` class have specific styling, such as background color, text color, padding, and border radius.
   - The `.item` class is a general class for styling all grid items. It gives them a white background, a border, and some margin and padding.
---
## OUTPUT:

![Assignment-9_Grid_Structure - Personal - Microsoft​ Edge 25-08-2023 09_11_45](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/b0522461-2979-4e7e-9763-c28b29a992ad)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/44_Assignment-9_Grid_Structure)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/44_Assignment-9_Grid_Structure/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/44_Assignment-9_Grid_Structure/index.html)
