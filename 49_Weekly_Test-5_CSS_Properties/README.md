# Weekly Test - 5 CSS Properties.
---
## TASK 
- You need to complete **"Weekly Test 5"** task, and we have learned basic CSS Properties like:
1. **Color Properties:**
   - `color`: Sets the text color.
   - `background-color`: Sets the background color of elements.
2. **Font Properties:**
   - `font-family`: Specifies the font family for text.
   - `font-size`: Defines the font size.
   - `font-weight`: Sets the font weight (boldness).
   - `text-decoration`: Controls text decoration (e.g., underline).
   - `text-align`: Specifies text alignment.
3. **Layout Properties:**
   - `display`: Defines how an element should be displayed (e.g., `display: flex`).
   - `align-items`: Aligns items along the cross-axis in a flex container.
   - `justify-content`: Aligns items along the main axis in a flex container.
   - `max-width` and `width`: Sets the maximum and actual width of elements.
   - `height`: Sets the height of elements.
   - `padding`: Sets padding inside elements.
   - `margin`: Sets margins around elements.
   - `border-radius`: Rounds the corners of elements.
   - `overflow`: Handles overflow content.
4. **Background Properties:**
   - `background-image`: Specifies a background image.
   - `background-position`: Defines the position of the background image.
   - `background-size`: Sets the size of the background image.
5. **Transition Properties:**
   - `transition`: Specifies transitions for smooth animations (e.g., `transition: transform 0.7s ease-in-out`).
6. **Cursor Property:**
   - `cursor`: Sets the mouse cursor type when hovering over an element.
7. **Pseudo-Classes:**
   - `:hover`: Defines styles for elements when they are hovered over.
8. **Media Queries:**
   - `@media`: Defines styles for specific screen sizes and devices.
---
## CODE:

**index.html file & style.css**

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_42_12](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/fe106318-ac64-4746-8348-246ddc8fd3c8)

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_42_36](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/332b7e70-5eaa-447c-821c-f962fbe7b24d)

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_43_04](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/731d6c4e-ad9d-4f5e-8609-adbf94675a8a)

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_43_19](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/df2266d4-2206-4a18-b15c-909b969bea12)

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_43_36](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/fa05fb58-8657-46ea-9fde-5e3d059d79e2)

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_43_52](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/86a4bb99-dcf3-4bba-852c-92d80b84cbfe)

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_44_04](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/ec0ef7e2-7c1d-4e2f-a9c2-084ec66a05cf)

![index html - Geekster_Assignments - Visual Studio Code 20-08-2023 21_44_13](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/877abed7-55bf-4e96-b5c4-3184609dc41d)

---
## EXPLANATION:
This HTML and CSS code represents a simple web page layout for an Amazon-like online store. Let's break down the code and explain the purpose of each part and class.

**HTML Structure:**
1. `<!DOCTYPE html>`: This declaration specifies the document type and version of HTML being used.
2. `<html lang="en">`: The opening tag for the HTML document. `lang="en"` specifies that the language is English.
3. `<head>`: This section contains metadata about the web page, such as character encoding and viewport settings.
4. `<meta charset="UTF-8">`: Sets the character encoding to UTF-8 for proper character rendering.
5. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Defines the viewport settings for responsive design.
6. `<title>Weekly_Test-5_CSS_Properties</title>`: Sets the title of the web page that appears in the browser tab.
7. `<link rel="stylesheet" href="style.css">`: Links an external CSS file named "style.css" to style the HTML content.
8. `<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200">`: Imports a Google Font for use in the web page.
9. `<body>`: The main content of the web page begins here.
**Header Section (`<header>`):**
10. `<header>`: Contains the header section of the web page, including the navigation bar and banner.
11. `<nav class="navbar">`: Represents the navigation bar at the top of the page.
12. `.nav-logo`: Contains the website logo.
13. `.address`: Displays delivery information.
14. `.nav-search`: Contains a search bar and dropdown for searching products.
15. `.sign-in`: Represents the "Hello, sign in" section.
16. `.returns`: Represents the "Returns & Orders" section.
17. `.cart`: Displays the shopping cart icon and the text "Cart."
18. `.banner`: Contains the banner content, such as "Today's Deals" links.
**Hero Section (`<section class="hero-section">`):**
19. `.hero-section`: Represents a hero section with a background image.
**Shop Section (`<section class="shop-section">`):**
20. `.shop-section`: Contains a section for displaying product links.
21. `.shop-link`: Represents individual product links with images and descriptions.
**Footer Section (`<footer>`):**
22. `<footer>`: Contains the footer section of the web page.
23. `.footer-title`: Represents a link to go back to the top of the page.
24. `.footer-items`: Contains lists of links categorized under "Get to Know Us," "Connect with Us," "Make Money with Us," and "Let Us Help You."

**CSS Styles (`style.css`):**
- `.navbar`: Styles the navigation bar.
- `.nav-logo`: Styles the website logo.
- `.address`: Styles the delivery address section.
- `.nav-search`: Styles the search bar and dropdown.
- `.sign-in` and `.returns`: Styles the "Hello, sign in" and "Returns & Orders" sections.
- `.cart`: Styles the shopping cart icon.
- `.banner`: Styles the banner at the top.
- `.hero-section`: Styles the hero section.
- `.shop-section` and `.shop-link`: Styles the shop section and individual product links.
- `.footer-title` and `.footer-items`: Styles the footer section and its contents.
---     
## OUTPUT:

![Screenshot 20-08-2023 22_29_08](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/430fa384-74b1-4600-83bd-bd85fdb677f5)

![Weekly_Test-5_CSS_Properties - Personal - Microsoft​ Edge 20-08-2023 22_29_21](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/27c43d25-02f7-4a3c-940c-20372063c556)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/9_Weekly_Test-5_CSS_Properties)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/9_Weekly_Test-5_CSS_Properties/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/9_Weekly_Test-5_CSS_Properties/index.html)
