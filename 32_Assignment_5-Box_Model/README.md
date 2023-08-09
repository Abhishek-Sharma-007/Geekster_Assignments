# Assignment 5 - Box Model
---
## TASK 
- You need to complete "Box Model" task, and in this assignment we have learned basic CSS Properties like:
  - Background-Color: This property sets the background color of an element. It can take various values, such as color names, hexadecimal color codes, RGB values, etc. For example, background-color: #FF0000; would set the background color of an element to red.
  - Height / Width: Height sets the height of an element, while width sets the width. These properties can be set using different units like pixels (px), percentages (%), or other units like em or rem. For example, height: 200px; and width: 300px; would set the dimensions of an element to 200 pixels in height and 300 pixels in width.
  - Color: The color property sets the text color within an element. It also accepts color values like color names, hexadecimal codes, or RGB values. For example, color: #000000; would set the text color to black.
  - Text-Decoration: This property is used to add visual effects to text. Common values include:
    - none: No decoration (default).
    - underline: Adds an underline to the text.
    - overline: Adds a line above the text.
    - line-through: Adds a line through the text (strikethrough).
    - blink: Makes the text blink (not widely supported).
  - Margin / Padding:
    - Margin is the space outside an element's border, creating separation between elements. It can have values for top, right, bottom, and left margins, set in a clock-wise order (e.g., margin: 10px 20px 10px 20px;).
    - Padding is the space between an element's content and its border. Like margin, it can have values for top, right, bottom, and left padding.
  - box-model:
    - The term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element.
    - It consists of: margins, borders, padding, and the actual content.
    - Box model also helps you to think how to design something in terms of boxes.
---
## CODE:

**1. index.html file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/715e40dc-ae63-4f4b-b668-73e17de9d0f1)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/82173424-e7d0-4064-89f0-6b592086c45a)

**2. style.css file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/00649315-8ab9-454d-92ae-0cbcbb8f9e5a)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/c9c74c4d-b6e3-47f5-968a-ab78c3924ab3)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/f5b9e884-9486-4bbb-9da5-93454ec2133a)

---
## EXPLANATION:
1. **HTML Code**:
   - Inside the `<body>`:
     - There's a `<div>` element with the class "container" that contains various other elements.
     - Two `<div>` elements with the class "desc" represent boxes with different content.
     - An `<ul>` (unordered list) element contains two list items, each with a `<div>` having the class "list".
     - A `<p>` element with the class "para" contains text along with a `<button>` and an `<a>` (anchor) element.
2. **CSS Code**:
   - `*`: Applies styles to all elements on the page.
   - `margin`, `padding`, `box-sizing`: Resets default margin and padding to 0 for all elements and ensures the box-sizing model is set to "border-box."
   - `.container`: Styles the main container with a border, font family, width, margin, and padding.
   - `.desc`: Styles for the description boxes, including border, padding, and margin.
   - `ul .desc`: Specific styling for `.desc` elements within an unordered list (`<ul>`).
   - `.list`: Styles for list items (boxes) within the unordered list.
   - `.para`: Styles for paragraphs, including margin and alignment.
   - `button` and `a`: Styles for buttons and links, including border, padding, font size, and color.
   - `ul`: Styles for unordered lists, adjusting the margin to remove default indentation.
3. **Classes**:
   - `.container`: Applied to the main container `<div>`, styling it with a border, font, width, margin, and padding.
   - `.desc`: Applied to description boxes, setting their border, padding, and margin.
   - `.list`: Applied to list items (boxes) within the unordered list.
   - `.para`: Applied to paragraphs, adjusting their margin and alignment.
   - Other classes like `button` and `a` are used to style buttons and links, respectively.

---     
## OUTPUT:

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/c3a19049-bf7b-473b-ae17-722fe7068a99)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/32_Assignment_5-Box_Model)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/32_Assignment_5-Box_Model/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/32_Assignment_5-Box_Model/index.html)
