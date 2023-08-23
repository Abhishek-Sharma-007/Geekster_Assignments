# Assignment- 9 Media Queries
---
## TASK 
- You need to complete **Assignment- 9 Media queries** task, and in this assignment we have learned basic CSS Properties like:
1. **What Are Media Queries?**
   - Media queries are CSS techniques that allow you to apply different styles based on the user's device characteristics, such as screen size, resolution, and orientation.
2. **Basic Syntax:**
   - Media queries use the `@media` rule with a specified `media-type` and `media-feature`.
   - `media-type` specifies the type of media (e.g., `screen` for screens).
   - `media-feature` sets the condition for applying styles (e.g., `max-width: 768px` for screens narrower than 768px).
3. **Using Media Queries for Responsiveness:**
   - Adjust layout, such as changing column arrangements or element widths for different screen sizes.
   - Modify font sizes to ensure readability on various devices.
   - Hide or show elements like menus based on screen size.
   - Make images responsive by setting `max-width: 100%`.
   - Customize colors and styles for better user experience.
4. **Common Media Query Breakpoints:**
   - Small screens: < 600px (e.g., mobile devices).
   - Medium screens: 600px - 1024px (e.g., tablets and small laptops).
   - Large screens: 1025px - 1440px (e.g., larger laptops and desktops).
   - Extra-large screens: > 1440px (e.g., very large displays).
5. **Testing and Debugging:**
   - Thoroughly test your responsive design on various devices and screen sizes.
   - Use browser developer tools to simulate different screens.
   - Debug by adjusting styles within media queries as needed to ensure proper behavior.
---
## CODE:

**index.html file & style.css file:**

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_48_13](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/bbcc4c90-ddf1-46fc-8853-e3ca7c45cd7f)

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_49_01](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/146005d9-f66b-4f99-9da0-246681231d1e)

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_49_10](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/3624ed38-6bf1-44b2-bce4-428a75086fe1)

![style css - Geekster_Assignments - Visual Studio Code 23-08-2023 23_49_17](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/5a610d7c-57a3-440b-9523-37743947dffe)

---
## **EXPLANATION:**

1. **HTML Code:**
  1. `<!DOCTYPE html>`: This is the document type declaration and specifies that the document is an HTML5 document.
  2. `<html lang="en">`: The opening `<html>` tag defines the root of the HTML document and includes the `lang` attribute to specify the document's language as English.
  3. `<head>`: This section contains metadata about the HTML document, such as character encoding and the document's title.
  4. `<meta charset="UTF-8">`: This meta tag defines the character encoding of the document as UTF-8, which is a widely used encoding for handling various characters and symbols.
  5. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: This meta tag is used for responsive web design. It sets the initial viewport scale to 1.0, ensuring that the web page is displayed properly on various devices and screen sizes.
  6. `<title>MediaQueries</title>`: This is the title of the web page that appears in the browser's title bar or tab.
  7. `<link rel="stylesheet" href="style.css">`: This line links an external CSS file named "style.css" to the HTML document. This CSS file is used to style the HTML elements.
  8. `<body>`: This is the opening `<body>` tag, where the content of the web page is placed.
  9. Inside the `<body>`, there are two `<div>` elements:
     - `<div class="above-main">`: This is an empty `<div>` element with the class "above-main." It doesn't contain any visible content and is often used for spacing or layout purposes.
     - `<div class="main-container">`: This `<div>` element contains the main content of the web page. It consists of an image, text, and a button.
  10. `<img src="coffee.jpg">`: This `<img>` tag embeds an image named "coffee.jpg" in the web page. It doesn't specify dimensions, so the image will display at its natural size.
  11. `<div class="text">`: This `<div>` element contains the text content of the page, including an `<h1>` heading, a `<p>` paragraph, and a `<button>`.
  12. There's a nested `<span>` with the class "imp" used to style a specific portion of text within the paragraph.
  13. Finally, there's a `<button>` element that serves as a call-to-action button.

2. **CSS Code:**
  1. The CSS code starts with some general styles for the entire page, setting padding and margin to zero for the `<body>` element and defining font families for various HTML elements.
  2. Styles for the `.main-container` class define the background color, minimum height, and layout properties. It uses flexbox to create a flexible layout for the main content area.
  3. Styles for the `<img>` element set its width, height, padding, and positioning to achieve a specific layout effect.
  4. Styles for the text within the `.text` class define font sizes, line height, and other properties to format the text content.
  5. Styles for the `.underline` class apply text-decoration to underline specific text.
  6. Styles for the `.imp` class set font size for a specific paragraph.
  7. Styles for the `<button>` element define its appearance, including background color, text color, padding, and hover effects.
  8. The CSS code also includes three media queries to make the page responsive:
     - The first media query adjusts the padding of the `.main-container` class when the screen width is between 800px and 1000px.
     - The second media query further adjusts padding and the image width for screens between 450px and 800px.
     - The third media query modifies the layout for screens with a maximum width of 450px, making the image full-width and changing the text layout.
---
## OUTPUT:

![image](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/ac442018-3b77-49e5-9489-3b912fd60934)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/46_Assignment-9_Media_queries)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/46_Assignment-9_Media_queries/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/46_Assignment-9_Media_queries/index.html)
