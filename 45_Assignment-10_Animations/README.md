# Assignment 10 - Animations
---
## TASK 
- You need to complete **"Animations** task, and in this assignment we have learned basic CSS Properties like:
Certainly, here's a concise explanation in bullet points:
1. **Grid:**
    - CSS layout system for creating complex two-dimensional layouts.
    - Uses rows and columns to align elements both horizontally and vertically.
    - Key components include grid containers, grid items, grid lines, and grid rows/columns.
    - Grid gap defines the spacing between grid items.
2. **Flexbox:**
    - CSS layout system for simpler one-dimensional layouts.
    - Typically used for arranging elements in a single row or column.
    - Key components include flex containers and flex items.
    - It operates along a main axis and a cross axis.
    - Flex properties control how items expand and contract within the container.
3.  **Enhancing UI with Animations:**
    - Animations make UI more engaging and visually appealing.
    - CSS properties like `box-reflect`, `transform`, `opacity`, `flex`, `height`, and `border-radius` can be used.
    - `box-reflect` creates reflections for elements.
    - `transform` allows rotations, translations, and scaling for animated effects.
    - `opacity` controls transparency for smooth fade-in and fade-out effects.
    - `flex` properties can be animated for dynamic layout changes.
    - `height` can be animated for expanding or collapsing sections.
    - `border-radius` animations create transitions between square and rounded shapes.
    - Animations amplify the beauty and user experience of the UI, making it more interactive.
---
## CODE:
**index.html file & style.css file:**

![index html - Geekster_Assignments - Visual Studio Code 25-08-2023 22_59_20](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/d076c73c-732a-4ad5-ab8f-4430f7fb711b)

---
## **EXPLANATION:**

**HTML Code:**
1. HTML5 structure with basic meta tags and a link to an external CSS file.
2. Contains a `<div>` element with the class "container" to group multiple images.

**CSS Code:**
1. The universal selector (*) is used to reset margins, padding, and box-sizing for all elements.
2. The `body` element is styled:
   - Set to flex display to horizontally and vertically center its children.
   - Background color set to black (#000).
   - Minimum height of 100vh ensures it covers the viewport height.
3. The `.container` class:
   - Displayed as flex, making its children align horizontally.
   - Width set to 1100, but it should have a unit like `px` or `%` (e.g., `width: 1100px;`).
   - Uses `-webkit-box-reflect` to create a reflection effect below the container.
4. The `.container img` class:
   - Sets a maximum width of 350px for all images within the container.
   - Applies a 3D transform effect with a perspective, giving images a 3D appearance.
   - Adds a smooth transition effect of 0.5 seconds for transforms.
   - Applies a box shadow and rounded corners to images.
5. On hover, the `.container:hover img` class:
   - Reduces the opacity of images to 0.3 when hovering over the container.
6. Additionally, the `.container img:hover` class:
   - Resets the transform to make images appear flat.
   - Restores full opacity when an image is hovered.
---
## OUTPUT:

![Document - Personal - Microsoft​ Edge 25-08-2023 23_01_11](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/ce0ce628-8f20-423c-82bb-b0fc5dfd3514)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/45_Assignment-10_Animations)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/45_Assignment-10_Animations/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/45_Assignment-10_Animations/index.html)
