# Assignment 4 - Shoe Page
---
## TASK 
- You need to complete "Shoe Page" task, and in this assignment we have learned basic CSS Properties like:
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

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/77f905aa-0554-41e9-80a7-1a18f00f6ed4)

**EXPLANATION:**
- This is the structure of the webpage. It includes a head section with meta tags and a title, along with a link to an external CSS file (style.css). The body of the webpage contains a main container `(<div class="container">)` that holds the main content of the page. Inside the container, there is a shoe main section `(<div class="shoe-main">)` that contains both the shoe data and the shoe image.

**2. style.css file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/65bd6e39-efbe-4d25-a189-ba3de2ffc20b)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/b5010458-40c3-4fa7-aa5d-d78846965187)

**EXPLANATION:**
- The * selector resets default margins, paddings, and box-sizing for all elements.
- The body selector sets the background color of the entire body.
- The .container class styles the main container, setting its width, height, position, and overflow.
- The .container::after pseudo-element creates a gradient background with a skew effect behind the main content.
- The .shoe-main class styles the main section for the shoe, setting its background, width, height, padding, margins, and box-shadow.
- The .data class styles the section containing textual information about the shoe, setting its maximum width and text color.
- The .shoe-image class styles the shoe image, positioning it absolutely to the right with specific width and height.
- The .shoe-image:hover class defines a hover effect for the shoe image, changing its position and size when hovered.
---
## OUTPUT:

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/fe9efeef-effa-4d44-b362-3c9386abdcdf)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/29_Assignment%20_4%20-Shoe_Page)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/28_Assignment_3-Nutrition_Label/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/29_Assignment%20_4%20-Shoe_Page/index.html)
