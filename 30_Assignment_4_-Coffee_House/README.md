# Assignment 4 - Coffee House 
---
## TASK 
- You need to complete "Coffee House" task, and in this assignment we have learned basic CSS Properties like:
  - Pseudo-Elements:
    - Pseudo-elements are used to style a specific part of an element, like the first line or first letter.
    - Represented with double colons :: (e.g., ::before, ::after).
  - Pseudo-Classes:
    - Pseudo-classes select elements based on their state or position (e.g., :hover, :active, :nth-child()).
    - Represented with a single colon :.
  - Position:
    - Determines how an element is positioned within its containing element.
    - Values include static, relative, absolute, fixed, and sticky.
  - Inset:
    - A shorthand property to set all four sides (top, right, bottom, left) of an element's padding, border, and margin simultaneously.
  - Transform:
    - Applies transformations like rotation, scaling, skewing, or translating to an element.
    - Used to manipulate an element's appearance without affecting the flow of the document.
  - Background (Linear Gradient):
    - Creates a gradient background by transitioning colors in a linear direction.
    - Allows for smooth color transitions from one point to another.
  - z-index:
    - Determines the stacking order of positioned elements (with position: absolute, position: relative, or position: fixed).
    - Elements with higher z-index values appear on top of elements with lower values.
  - Box-Shadow:
    - Adds a shadow effect to an element's box (border box) using horizontal and vertical offsets, blur radius, and color.
  - Margin/Padding:
    - Margin is the space outside an element's border, creating separation from other elements.
    - Padding is the space inside an element's border, creating space between content and the border.
  - Width/Height:
    - Determines the width and height of an element's content box.
    - Can be set in absolute units (px) or relative units (%).
---
## CODE:

**1. index.html file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/f3b70abd-f594-457b-9697-6e8ba3adee9e)     

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/7d1758c8-fe66-4b33-939f-1a6d81a2dc59)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/9e3de444-9b42-453b-98d8-c10786b7d0de)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/5d822520-d3a1-410b-9972-f413ea5b27e5)

**2. style.css file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/3adfb753-54ce-47b3-9d7d-31f78297f5a9)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/50675e11-7688-4181-a751-3b43f5aa4eda)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/37a18e5e-2006-4406-8647-ce0f744a6b48)

---
## EXPLANATION:
1. **HTML Structure (`index.html`):** The HTML structure defines the layout and content of the webpage.
   - The `<head>` section contains meta information, the title of the webpage, and a link to the external CSS file `style.css`.
   - The `<body>` section contains the main content of the webpage.
2. **CSS Styling (`style.css`):** The CSS styling enhances the appearance and layout of the webpage.
   - `*`: Resets default styles for all elements.
   - `.navbar`: Styles the navigation bar at the top of the page with a background image and a sticky search input.
   - `.main-coffee-menu`: Arranges the coffee menu items in a flex layout with space between them.
   - `.coffee-img`: Sets the dimensions for the coffee images.
   - `img`: Styles the coffee images, including border radius and box shadow. Hover effect increases the size and shadow on hover.
   - `.description`: Styles the description sections with a background color, padding, and border radius.
   - `.description > p, .description > ol`: Sets the line height and text color for paragraph and list elements.
   - `ol > li`: Adds padding to list items.
   - `.description > h1`: Styles the headings in the description sections.
3. **HTML Structure Inside `<body>`:**
   - `.navbar`: Contains a search input within a navigation bar.
   - `.main-coffee-menu`: Contains coffee menu items, each represented by a `<div>` containing an image and a heading.
   - `.description`: Contains multiple sections with headings and paragraphs.
4. **CSS Styling Details:**
   - The `.navbar` background image creates a visually appealing header. The search input is positioned using `position: sticky` to stay visible while scrolling.
   - The `.main-coffee-menu` uses flex display for arranging menu items with space between them.
   - Images in `.coffee-img` are styled with border radius and a box shadow. Hover effect increases the size and shadow.
   - `.description` sections have a brown semi-transparent background, padding, and border radius for a neat look.
   - Typography settings (`color`, `line-height`) enhance text readability and aesthetics.

---
## OUTPUT:

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/340e44a1-ec10-4d92-a225-947201821c08)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/0da8c338-5100-4ba5-9d49-785ed234acee)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/30_Assignment_4_-Coffee_House)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/30_Assignment_4_-Coffee_House/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/30_Assignment_4_-Coffee_House/index.html)
