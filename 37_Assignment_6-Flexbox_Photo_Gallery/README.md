# Assignment - 6: Flexbox Photo Gallery 
---
## TASK 
- You need to complete "Flexbox Photo Gallery" task, and in this assignment we have learned basic CSS Properties like:
  1. **display**: Determines how an element should be displayed. `display: flex;` turns an element into a flex container, allowing you to use flex properties.
  2. **flex-direction**: Sets the direction of flex items along the main axis. Values like `row`, `column`, etc., define the arrangement of items.  
  3. **flex-wrap**: Controls whether flex items should wrap onto multiple lines or stay on a single line. Values include `wrap` and `nowrap`. 
  4. **justify-content**: Aligns flex items along the main axis. Options like `flex-start`, `flex-end`, etc., distribute space between items. 
  5. **align-items**: Aligns flex items along the cross-axis. Values like `center`, `baseline`, etc., determine vertical alignment.
  6. **gap**: Sets spacing between flex items within a container, replacing `row-gap` and `column-gap`.
  7. **margin**: Creates space outside an element's border. You can set individual margins for each side or use shorthand properties.
  8. **padding**: Adds space between an element's content and its border. Similar to margins, you can set padding for each side or use shorthand properties. 
  9. **max-width**: Limits the maximum width an element can have, helping maintain a readable layout on larger screens. 
  10. **Additional Flex Properties**:
      1. **align-content**: Defines how multiple lines of flex items are spaced along the cross-axis within a flex container.
      2. **flex-grow**: Specifies how much a flex item can grow in relation to its siblings when extra space is available.  
      3. **flex-shrink**: Determines how much a flex item can shrink when space is limited. 
      4. **flex-basis**: Sets the initial size of a flex item along the main axis.
      5. **flex**: A shorthand property combining `flex-grow`, `flex-shrink`, and `flex-basis`.
      6. **order**: Specifies the order in which flex items appear within the flex container.
      7. **align-self**: Overrides the `align-items` property for individual flex items.
      8. **justify-self**: Overrides the `justify-content` property for individual flex items.
         
---
## CODE:

**1. index.html file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/215ee1e9-e32d-4d5a-a114-c8452492dc2a)

**2. style.css file:**

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/ec9fce32-68ff-49a7-9fcd-968c86024935)

---
## EXPLANATION:
1. **HTML Structure**:
   - The HTML code includes a `<!DOCTYPE>` declaration, opening `<html>` tag, `<head>` section, and `<body>` section.
   - In the `<head>` section, there are meta tags for character encoding and viewport settings, as well as a `<title>` tag.
   - The `<link>` tag includes a reference to an external CSS file named "style.css".
   - Inside the `<body>` section, there's a header with the class "header" and a gallery div with the class "gallery".
2. **CSS Styling**:
   - The `*` selector sets the `box-sizing` property to `border-box` for all elements, ensuring that padding and borders are included in the element's total width and height calculations.
   - The overall page styling includes a sans-serif font family and a background color. 
3. **.header Class**:
   - `.header` class styles the header element.
   - It aligns text to the center, transforms text to uppercase, adds padding, sets a background color, text color, and adds a bottom border.
4. **.gallery Class**:
   - `.gallery` class styles the gallery container.
   - `display: flex;` makes the container a flex container, enabling flex properties to control layout.
   - `flex-direction: row;` arranges items in a row (horizontal) direction.
   - `flex-wrap: wrap;` allows items to wrap onto multiple lines when necessary.
   - `justify-content: center;` centers items along the main axis.
   - `align-items: center;` centers items along the cross-axis.
   - `gap: 16px;` adds spacing between gallery images.
   - `max-width: 1400px;` sets a maximum width for the gallery container.
   - `margin: 0 auto;` centers the gallery horizontally using auto margins.
   - `padding: 20px 10px;` adds padding to the top and bottom of the gallery.
5. **.gallery img Class**:
   - `.gallery img` styles the gallery images within the container.
   - `width: 100%;` ensures the images occupy the full width of their container.
   - `max-width: 350px;` limits the maximum width of the images.
   - `height: 300px;` sets a fixed height for the images.
   - `object-fit: cover;` maintains the image's aspect ratio while covering the available space.
   - `border-radius: 10px;` adds rounded corners to the images.
6. **.gallery::after Pseudo-element**:
   - `.gallery::after` uses a pseudo-element to create additional spacing.
   - `content: "";` inserts an empty content element.
   - `width: 350px;` sets a fixed width, providing extra spacing at the end of the gallery.

---
## OUTPUT:

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/6b96040c-0ce0-4117-a3f2-98e75dc110fa)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/37_Assignment_6-Flexbox_Photo_Gallery)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/37_Assignment_6-Flexbox_Photo_Gallery/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/37_Assignment_6-Flexbox_Photo_Gallery/index.html)
- FreeCodeCamp ID Link: [Click Me](https://www.freecodecamp.org/Abhishek_77)
- FreeCodeCamp Last Step Link:[Tap On](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-flexbox-by-building-a-photo-gallery/step-21)
