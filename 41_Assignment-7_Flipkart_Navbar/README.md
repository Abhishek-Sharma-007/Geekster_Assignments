# Assignment - 7 Flipkart Navbar
---
## TASK 
- You need to complete **"Flipkart Navbar"** task, and in this assignment we have learned basic CSS Properties like:
  - **Aligning HTML Elements using Flex Properties:**
    In this task, you'll learn how to use flex properties to create flexible layouts and align HTML elements within containers. Flex properties provide a way to easily arrange and organize elements on a webpage. 
  - **Flex Direction:**
    This property determines the direction in which flex items are placed within their container. You can choose between horizontal (`row` or `row-reverse`) or vertical (`column` or `column-reverse`) arrangements.  
  - **Justify Content:**
    With this property, you control the alignment of flex items along the main axis. You can set them to align at the start, end, center, or spread out evenly with various spacing options.
  - **Align Items:**
    This property allows you to align flex items along the cross axis (perpendicular to the main axis). It lets you position items at the top, bottom, center, or stretch them to fill the container's height.  
  - **Flex Wrap:**
    Flex Wrap determines how flex items should behave when there's not enough space in the container. You can choose to make them wrap onto a new line (`wrap`) or stay on the same line (`nowrap`). 
  - **Flex Grow/Shrink:**
    Flex Grow and Flex Shrink enable dynamic resizing of flex items. Flex Grow determines how much an item can grow to occupy available space, while Flex Shrink controls how much an item can shrink to fit within limited space. 
  - **Gap:**
    This property sets the spacing between flex items within a container. It simplifies the process of adding consistent spacing between items.
  - **Previously Taught CSS Properties:** You'll also review and practice CSS properties you've learned before:
    - **Margin:** This property creates space around the outside of an element, separating it from other elements.
      
    - **Padding:** Padding creates space inside an element, between its content and its borders.
      
    - **Width:** Width defines the horizontal size of an element, allowing you to control how much space it occupies along the x-axis.
      
    - **Height:** Height sets the vertical size of an element, determining how much space it takes up along the y-axis.

---
## CODE:

**index.html file & style.css file:**

![Screenshot 16-08-2023 23_26_13](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/b21e2528-73a2-4821-b0d8-021cfadfccaf)

![index html - Geekster_Assignments - Visual Studio Code 16-08-2023 23_26_35](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/cda4c310-aaff-4509-b58b-b7475e6aa208)

![index html - Geekster_Assignments - Visual Studio Code 16-08-2023 23_26_53](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/012abe68-6d44-4f47-875a-bb54fb350dd7)

---
## **EXPLANATION:**

1. **HTML Code:**
    The HTML code defines the structure of the webpage. It includes a header section with a navigation bar and a section for displaying product categories.
    - `<header class="navbar-top">`: This is the header section containing the navigation bar. It has the class `navbar-top`.
      - `.left`: A `div` inside the header that holds the logo and a "Explore plus" text. 
      - `.search`: A `div` that contains a search input and a search icon.
      - `.loginbut`: A button for the login action.  
      - `.links`: A `div` containing an unordered list (`<ul>`) for various navigation links.  
    - `<section class="items">`: This section contains links to different product categories.
      - `.items-links`: A `div` that holds an image and a paragraph for each product category link.
  
2. **CSS Code:**
    The CSS code styles the HTML elements and controls their appearance and layout.
    - `*`: A universal selector that applies the following properties to all elements on the page. It sets margin, padding, box-sizing, and font-family.
    - `.navbar-top`: Styles for the header section.
    - `.plus-class`: Styles for the "plus" text within the header.
    - `.left p`: Styles for the text inside the `.left` div.
    - `.flip-img`: Styles for the logo image.
    - `.search`: Styles for the search bar container.
    - `.search input`: Styles for the search input field.
    - `.loginbut`: Styles for the login button.
    - `.links ul`: Styles for the unordered list within the `.links` div.
    - `.links ul li`: Styles for each list item (navigation link) within the unordered list.
    - `.items`: Styles for the product categories section.
    - `.items-links img`: Styles for the product category images within `.items-links`.
    - `.items-links p`: Styles for the text paragraphs within `.items-links`.
    - `.items-links .material-icons`: Styles for the material icons within `.items-links`.
    - `.items-links a`: Styles for the anchor links within `.items-links`.

3. **Flow & Approach:**
    The HTML code sets up the structure of the webpage, with a header containing a navigation bar and a section for displaying product categories. The CSS code styles the HTML elements for a visually appealing design.
    The classes and IDs used in the HTML code serve as hooks for styling and organizing elements. For example:
      - `.navbar-top` is used to style the header section.
      - `.left` and `.search` define styling for specific sections within the header.
      - `.links` is used to style the navigation links.
      - `.items` styles the product categories section.
      - `.items-links` contains styling for each product category link.
---
## OUTPUT:

![New File at 41_Assignment-7_Flipkart_Navbar · Abhishek-Sharma-007_Geekster_Assignments and 3 more pages - Personal - Microsoft​ Edge 16-08-2023 23_33_47](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/acfcecd4-cc75-439a-8f55-bac882943a00)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/38e76608-3b27-4dd7-8c41-8a01a81b4bb3)
---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/41_Assignment-7_Flipkart_Navbar)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/41_Assignment-7_Flipkart_Navbar/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/41_Assignment-7_Flipkart_Navbar/index.html)
