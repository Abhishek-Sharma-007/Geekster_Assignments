# Major Project using Tailwind
---
## TASK 
- You need to complete **Major Project using Tailwind** task, and we have learned basic CSS Properties like:
1. **Utility-First Approach:** Tailwind follows a utility-first approach, which means that it provides a large set of utility classes that you can use to style your elements. This eliminates the need to write custom CSS for most of your UI elements, saving you a lot of time and effort.
2. **Responsive Design:** Tailwind makes it easy to create responsive designs by providing classes for various screen sizes. You can use classes like `sm`, `md`, `lg`, and `xl` to apply different styles based on the screen width. For example, `lg:text-xl` will increase the font size on large screens.
3. **Flexibility:** Tailwind is highly flexible and allows you to customize your styles by modifying the configuration file. You can add your own utility classes or tweak existing ones to match your project's design system.
4. **Rapid Prototyping:** Tailwind is excellent for rapid prototyping. You can quickly build and iterate on UI components by applying classes directly to HTML elements. This means you spend less time writing CSS and more time designing and refining your UI.
5. **Readability and Maintainability:** Tailwind classes are self-explanatory and provide a clear separation of concerns. This makes your HTML markup more readable and makes it easier for your team to maintain and collaborate on the codebase.
6. **Consistency:** Tailwind enforces consistency in your UI design because it encourages you to use a predefined set of classes. This consistency can lead to a more polished and professional-looking application.
7. Commonly used properties in Tailwind CSS:
   - **Text Color (`text-`):** Tailwind provides classes like `text-red-500` to set the text color. The number represents the shade of the color.
   - **Background Color (`bg-`):** Classes like `bg-blue-300` set the background color of an element.
   - **Padding (`p-`) and Margin (`m-`):** These classes control the spacing around elements. For example, `p-4` adds padding of 1rem (16px), and `m-2` adds a margin of 0.5rem (8px).
   - **Font Size (`text-`):** Use classes like `text-lg` to set the font size. The sizing is based on a predefined scale.
   - **Flexbox (`flex`, `justify-`, `items-`):** Tailwind includes classes for creating flexible layouts easily. `flex` sets an element to a flex container, `justify-center` centers items horizontally, and `items-center` centers items vertically within a container.
   - **Grid (`grid`, `grid-cols-`, `gap-`):** Tailwind provides classes for creating grid layouts. `grid` sets an element as a grid container, `grid-cols-3` divides the container into three columns, and `gap-4` adds a 1rem (16px) gap between grid items.
   - **Responsive Prefixes (`sm:`, `md:`, `lg:`):** These prefixes allow you to apply classes conditionally based on screen sizes. For example, `md:text-xl` will apply the `text-xl` class only on medium-sized screens and larger.
   - **Customization:** Tailwind allows you to customize the default configuration to add your own classes, modify existing ones, or define your color palette, making it adaptable to your project's needs.
---
## OUTPUT:

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/57_Major_Project_using_Tailwind)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/57_Major_Project_using_Tailwind/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/57_Major_Project_using_Tailwind/index.html)

## CODE:

**index.html file(Tailwind css code)**

![tailwind config js - Geekster_Assignments - Visual Studio Code 05-09-2023 01_27_08](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/71600e0b-0b4d-4151-96bf-0376dbed0c8e)

![tailwind config js - Geekster_Assignments - Visual Studio Code 05-09-2023 01_27_41](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/c40a1b0f-02a5-4dcb-a6fb-20fad2adcf66)

![tailwind config js - Geekster_Assignments - Visual Studio Code 05-09-2023 01_28_19](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/1e8d870e-35ad-4c6e-a131-b0549ed97a42)

![tailwind config js - Geekster_Assignments - Visual Studio Code 05-09-2023 01_28_43](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/83e9c7fe-2365-44ae-87c5-81a7d3fe7649)

![tailwind config js - Geekster_Assignments - Visual Studio Code 05-09-2023 01_29_15](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/3e22ceb6-4434-4c02-9ee7-5ee2f7de8e67)

![tailwind config js - Geekster_Assignments - Visual Studio Code 05-09-2023 01_29_48](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/f5dbc860-1619-4799-81ed-4dd18f57271a)

![tailwind config js - Geekster_Assignments - Visual Studio Code 05-09-2023 01_30_46](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/0a2e193f-0e7a-4ff3-aae7-0ca45e1a2567)

---
## EXPLANATION:
1. **HTML Structure**:
   - The document starts with the usual HTML5 doctype declaration (`<!DOCTYPE html>`).
   - The `<html>` element wraps the entire HTML content.
   - The `<head>` section contains various metadata, including character encoding, viewport settings, and a reference to an icon (favicon).
   - It also includes references to external resources like Font Awesome icons, CSS stylesheets, and a JavaScript library (AOS - Animate On Scroll).
   - The website title is set to "The_November_Room" in the `<title>` tag.  
2. **Body Structure**:
   - The `<body>` element contains the main content of the webpage.   
3. **Navbar**:
   - The website has a navigation bar (`<nav>`) at the top of the page.
   - The navigation bar includes a logo and navigation links.
   - It uses Tailwind CSS classes for styling and responsiveness.
   - There is a JavaScript function (`toggleNavbar`) defined for handling the responsive behavior of the navigation bar when viewed on smaller screens.
4. **Main Content**:
   - The main content of the webpage is wrapped in a `<main>` element.
   - The first section of the main content features a hero section with a background image, a headline, and a call-to-action button.
   - A gradient overlay is applied to the background image to improve text readability.
5. **About Section**:
   - The second section is an "About" section that provides information about the gym.
   - It includes an image, a title, and a description.
   - A list of features is presented using icons and descriptions.
6. **Meet our Trainers Section**:
   - The third section introduces the gym's trainers.
   - It displays images, names, and titles for each trainer.   
7. **Contact Sections**:
   - The fourth and fifth sections are dedicated to contacting the gym.
   - The fourth section provides a form for users to send messages.
   - The fifth section includes contact information and social media links.
8. **Footer**:
   - The website ends with a footer that contains copyright information and social media links.  
9. **JavaScript**:
   - Two JavaScript functions are included at the end of the document.
   - `toggleNavbar` is used for toggling the responsive navigation bar.
   - `AOS.init` initializes the AOS library for smooth scrolling animations.
10. **Styling**:
    - The website's styling is primarily achieved using Tailwind CSS, a popular utility-first CSS framework.
    - Various Tailwind CSS classes are applied to elements throughout the document to control layout, spacing, typography, and more.
