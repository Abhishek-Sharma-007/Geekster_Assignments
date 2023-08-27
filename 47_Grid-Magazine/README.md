# Grid - Magazine
---
## TASK 
- You need to complete "**Grid - Magazine**" task, and in this assignment we have learned basic CSS Grid Properties like:
1. **Grid Template (`grid-template-rows` and `grid-template-columns`):**
    - `grid-template-rows` defines the height of rows in the grid, while `grid-template-columns` defines the width of columns.
    - You can specify values for these properties in various units like pixels, percentages, or `fr` units (fraction of available space).
    - These properties are crucial for setting up the structure of your grid layout.
2. **Grid Area (`grid-area`):**
    - `grid-area` is used to assign a name to a grid item, which can then be referenced in the `grid-template-areas` property.
    - This property allows you to control where specific elements should appear in your grid layout.
    - It's useful for creating complex grid layouts with named areas.
3. **Grid Column (`grid-column`):**
    - `grid-column` is used to explicitly place a grid item within specific column lines of the grid.
    - You can define the start and end positions of the grid item within the grid columns.
    - For example, `grid-column: 2 / 4;` would place the item between the second and fourth column lines.
---
## CODE:

**index.html & styles.css**

![index html - Geekster_Assignments - Visual Studio Code 27-08-2023 19_28_55](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/f4bf7f93-5518-411e-8ee0-1d65bc611f42)

![index html - Geekster_Assignments - Visual Studio Code 27-08-2023 19_29_15](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/7a1c64f9-e834-4311-9539-886e2a777126)

![index html - Geekster_Assignments - Visual Studio Code 27-08-2023 19_29_29](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/e561cc93-8e71-4c92-aff3-7cd2a59a0ba3)

![index html - Geekster_Assignments - Visual Studio Code 27-08-2023 19_29_46](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/f6a39490-ae48-459d-8d37-b096c38f4297)

![index html - Geekster_Assignments - Visual Studio Code 27-08-2023 19_30_18](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/ab8c29fc-4d34-4f50-a935-eee1169c6ccb)

![index html - Geekster_Assignments - Visual Studio Code 27-08-2023 19_30_34](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/d178ebf9-ee92-4577-b023-1d1425c1a8a3)

**EXPLANATION:**
1. **HTML Code (index.html):**
    1. `<meta>` Tags: These meta tags define the character encoding and the viewport settings for responsive design.
    2. `<link>` Tags: These `<link>` tags include external CSS stylesheets and fonts. The first link includes Google Fonts, the second includes Font Awesome for icons, and the third links to an external CSS file called "styles.css."
    3. `<main>` Element: This is the main content container of your webpage.
    4. `<section>` Elements: These represent different sections of your content, such as the "heading" and "text" sections.
    5. Various HTML elements like `<header>`, `<h1>`, `<p>`, `<a>`, `<img>`, `<blockquote>`, and `<ul>` are used to structure and format your content.
    6. Classes (e.g., `class="heading"`, `class="first-paragraph"`) are used to group and style elements in CSS.
2. **CSS Code (styles.css):**
    1. Universal Selector `*`: This selector resets margins and paddings to zero and sets the box-sizing property to border-box for all elements, ensuring consistent spacing and sizing.
    2. `html`: Sets the base font size to 62.5% (10px by default), making it easier to use relative units like `rem` for font sizes.
    3. `body`: Styles the overall body of the webpage, including font, text color, and background color.
    4. Font Family Styling (`h1`, `h2`, `h3`, `h4`, `h5`, `h6`, `a`): Specifies different font families for various heading levels and links.
    5. `main`: Sets up the grid layout for the main content, with three columns and a gap between rows.
    6. `img`: Ensures that images within your content stretch to the full width of their container and maintain their aspect ratio using `object-fit: cover`.
    7. `hr`: Styles horizontal lines to separate content sections.
    8. `.heading`: Styles the heading section, including the grid layout, row gap, and column layout.
    9. `.text`: Styles the main text section, including font size, letter spacing, column width, and text alignment.
    10. `.hero`: Styles the hero section at the top with a full-width column.
    11. `.hero-title`, `.hero-subtitle`: Styles the hero title and subtitle with specific colors and font sizes.
    12. `.author`, `.publish-date`: Styles the author and publish date sections.
    13. `.social-icons`: Sets up the grid layout for social media icons.
    14. `.first-paragraph`: Styles the first paragraph with a larger initial letter.
    15. `.quote`: Styles blockquotes with specific colors, font size, and alignment.
    16. `.text-with-images`: Styles the section with text and images using a grid layout.
    17. `.lists`: Styles unordered lists within the text.
    18. `.list-title`, `.list-subtitle`: Styles list titles and subtitles with specific colors.
    19. `.image-wrapper`: Styles the container for images, arranging them in a grid.
    20. Media Queries: These queries adjust styles for different screen sizes, making the website responsive. They change font sizes and layouts for various screen widths.

---
## OUTPUT:

![Magazine - Personal - Microsoft​ Edge 27-08-2023 19_42_42](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/56d12369-f472-40e4-b30d-9657d561ad04)

![Magazine - Personal - Microsoft​ Edge 27-08-2023 19_42_50](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/35913743-c2b0-409c-b9a5-94e40ce99ddd)

![Magazine - Personal - Microsoft​ Edge 27-08-2023 19_43_01](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/17eb92dc-e021-4629-ac3a-5ae29e1a9041)

![Magazine - Personal - Microsoft​ Edge 27-08-2023 19_43_09](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/366fb61e-3157-4fdf-9889-d586dee8a34a)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/47_Grid-Magazine)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/47_Grid-Magazine/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/47_Grid-Magazine/index.html)
- FreeCodeCamp ID: [Click Here](https://www.freecodecamp.org/Abhishek_77)
- FreeCodeCamp Last Step Link: [Click Here](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-grid-by-building-a-magazine/step-80)
