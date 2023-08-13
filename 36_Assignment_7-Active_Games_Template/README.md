# Assignment 7 - Active Games Template
---
## TASK 
- You need to complete "Active Games Template" task, and in this assignment we have learned basic CSS Properties like:
  1. **Flex Properties**: Flex properties are a set of CSS properties that allow you to create flexible and responsive layouts in HTML using the Flexible Box Layout (Flexbox) model. The task involves practicing different flex properties to control the alignment and arrangement of elements within a flex container.
  2. **Flex Direction**: This property sets the direction of the main axis along which flex items are placed within the container. It can be set to values like "row" (horizontal), "column" (vertical), "row-reverse," or "column-reverse."
  3. **Justify Content**: This property defines how flex items are distributed along the main axis. It controls the spacing between items and the container's edges. Values include "flex-start," "flex-end," "center," "space-between," and more.
  4. **Align Items**: This property determines how flex items are aligned along the cross axis (perpendicular to the main axis). It controls vertical alignment and can take values like "flex-start," "flex-end," "center," "baseline," and "stretch."
  5. **Flex Wrap**: This property specifies whether flex items should wrap onto multiple lines if they can't fit within the container. It can be set to "nowrap," "wrap," or "wrap-reverse."
  6. **Flex Grow/Shrink**: These properties control how flex items grow or shrink to fill the available space within the container. The "flex-grow" property determines the distribution of remaining space, while "flex-shrink" controls the shrinking of items when there's not enough space.
  7. **Gap**: This property sets the spacing between flex items within the container, both along the main axis and the cross axis.
  8. **Practicing Previously Taught CSS Properties**: Apart from flex properties, the task also involves practicing some commonly used CSS properties that you've likely learned before:
  9. **Margin**: This property controls the space around an element's outside edges.
  10. **Padding**: This property controls the space between an element's content and its border.
  11. **Width**: This property sets the width of an element.
  12. **Height**: This property sets the height of an element.
---
## CODE:

**1. index.html file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/e2555168-6407-4730-999d-db67b92fbe4c)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/8ef2ea72-b3b1-4fbc-863a-96f58faa8bef)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/03a6c9e7-3059-46c7-bfc4-290843523112)

**EXPLANATION:**
1. **Head Section**: The `<head>` section contains metadata about the document, including the document's title, character encoding, and viewport settings for responsive design.
2. **Linking CSS and Fonts**: The `<link>` tags link external resources. The first link connects to an external CSS file named "style.css" for styling the page. The other links are for connecting to the "Poppins" font from Google Fonts.
3. **Main Content**: The content of the page is enclosed within the `<main>` element. It contains a `<nav>` element for the navigation menu and a `<section>` element for the content.
4. **Navigation (`<nav>`)**: The navigation menu is on the left side of the page. It consists of a profile section, a list of menu items, and a "Join Pro" section.
5. **Content (`<section>`)**: The content section is on the right side of the page. It displays information about active games, including images and progress bars.

---
**2. style.css file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/866f4222-4ee7-4e48-b689-1884c4c0ca5c)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/fd700515-a242-4928-b390-776c80f5695a)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/68f4466c-0f74-4326-972d-42fff010a509)

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/854a5f8b-bc3c-4bd6-9c7b-5e23b46f003a)

**EXPLANATION:**
1. **Body Styling**: Sets background color, margin, padding, and font family for the entire body.
2. **Typography Styling**: Sets default typography styles for headings and paragraphs.
3. **Layout Styling (`<main>` and `<nav>`)**: The `<main>` element is displayed as a flex container, allowing its child elements to be arranged using flex properties. The `<nav>` element is given a fixed width of 20%, a background color, padding, and is styled as a flex container with vertical alignment.
4. **Navigation Menu (`<ul class="menu">`)**: The navigation menu items are displayed as a vertical list using flex properties. Each menu item consists of an image and text.
5. **Profile and Pro Container Styling**: The profile section and "Join Pro" section are styled as flex containers, allowing their contents to be centered and spaced evenly.
6. **Content Section (`<section>`)**: The content section is styled as a flex container with a vertical arrangement. The game containers are styled with background color, border radius, shadow, and padding.
7. **Game Container Styling**: Each game container includes an image, game details, and a progress percentage. The game details are positioned using margin-left, and the progress bars are styled with appropriate colors and dimensions.
8. **Responsive Design**: The CSS doesn't include specific media queries for responsive design, but the viewport settings in the HTML `<meta>` tag help make the page responsive by adjusting the initial scale based on the device width.
9. **Important Classes**:
   1. **`.profile-sec`**: This class is applied to the container of the profile picture, username, and user status. It is used to vertically align its contents and create a centered column layout for the profile information.
   2. **`.menu`**: This class is applied to the unordered list (`<ul>`) that contains the navigation menu items. It is used to style the list as a vertical menu, arranging each menu item in a column.
   3. **`.pro-container`**: This class is applied to the container for the "Join Pro" section. It creates a flex container for even spacing of the "Join Pro" text and the icon, and adds a background color to highlight the section.
   4. **`.game-container`**: This class is applied to each individual game container in the content section. It styles the game containers with a background color, border radius, shadow, and padding, creating a consistent and visually appealing layout for each game's information.
   5. **`.progress`**: This class is applied to the progress bar container in the navigation menu. It defines the background color and dimensions of the progress bar, creating a visual indicator for the progress.
   6. **`.title-container`**: This class is applied to the container of the "Active Games" title and progress bar in the content section. It adds spacing at the bottom of the title and aligns the progress bar underneath it.
   7. **`.game-details`**: This class is applied to the container for game details (game name and version) within each game container. It positions the game details to the right of the game image using margin-left.
   8. **`.progress-1`, `.progress-2`, `.progress-3`**: These classes are applied to the progress bars within each game container. They define the background color and dimensions of the progress bars for different games.

---
## OUTPUT:

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/4f2eebd8-eb16-4bfd-beee-1046a209749d)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/36_Assignment_7-Active_Games_Template)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/36_Assignment_7-Active_Games_Template/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/36_Assignment_7-Active_Games_Template/index.html)
