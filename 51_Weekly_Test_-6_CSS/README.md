# Weekly Test - 6 CSS Properties.
---
## TASK 
- You need to complete **"Weekly Test 6"** task, and we have learned basic CSS Properties like:
1. **Header-section:**
   - The header contains a navigation bar with a logo and icons.
   - The header's position is set to "fixed," meaning it stays in a fixed position on the screen while scrolling.
   - The use of `z-index` is likely employed to control the stacking order of elements, ensuring the header appears above other content when necessary.
2. **Home:**
   - The "Home" section comprises four image boxes, each occupying 50% of the width of their container.
   - These image boxes are displayed using the CSS property `display: flex`, which allows for flexible layout and alignment of their contents.
   - The images inside these boxes are set to have a width of 100%, ensuring they fill their respective containers.
3. **Banner-1:**
   - "Banner-1" contains four images arranged in a flex container.
   - The use of `flex-wrap` property suggests that the images can wrap onto the next line if they don't fit in the available horizontal space.
   - This structure is likely consistent for other banners with images and text.
4. **Info:**
   - Text within the "Info" section is centered.
   - Colors and text decorations like font styling or underlines may be applied to enhance the visual presentation.
5. **Features-section:**
   - The "Features-section" is divided into three parts, each consisting of images and text displayed in a row format.
   - `flex` and `flex-row-reverse` are used to control the layout, with "flex-row-reverse" possibly flipping the order of items.
   - Boxes containing these features have defined widths and padding to control spacing.
6. **Iframe for YouTube video:**
   - An iframe is used to embed a YouTube video.
   - The iframe's width is set to 100%, ensuring it scales to the container's width, and the height is fixed at 600 pixels.
7. **Products-section:**
   - This section contains items and their prices presented in a scrollable fashion.
   - A scroll bar is added to enable users to scroll through the content.
   - Flex properties are likely used to arrange and style the items within this section.
8. **Subscribe:**
   - The "Subscribe" section includes a form.
   - There are hover effects applied to buttons, which may involve changing the button's appearance when the user hovers over them.
   - The form and buttons are centered using `display: flex`.
9. **Footer:**
   - The footer is displayed using a `flex` layout, allowing for flexible arrangement of its contents.
10. **Media Queries:**
    - Media queries are used to apply different styles and layout rules for different screen sizes.
    - For extra small devices (e.g., phones with a screen width of 600px or less), styles like `flex` and `width: 100%` are applied, possibly to make content stack vertically and take up the full width.
    - For large devices (e.g., laptops and desktops with a screen width of 992px or more), styles may include reducing padding and margin, as well as setting `flex-wrap` properties to control layout. These changes optimize the design for larger screens.
---
## CODE:

**index.html file & style.css**

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_22_35](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/53f50edc-3ffc-4962-b7c7-ca3b13293b79)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_22_44](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/9dcd730a-77e2-4f4b-a630-300d407705c7)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_22_54](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/72adcf44-31b9-4079-823b-55cb04d0580c)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_22_59](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/40f8c8d7-7865-4c5e-948f-554b37593af8)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_02](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/501a5af5-2455-412b-98a3-e61b23f1b720)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_06](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/4070e2e2-8414-4403-ac32-37bcc8ef5be4)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_22](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/c8293e89-0eca-43dc-be91-5b4278afcd95)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_25](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/a029f57a-ca9a-4e39-9830-3cdaf8a7b384)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_28](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/54875a02-cd79-4843-9834-e99c9b3a49d3)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_32](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/24181150-b328-41b9-980a-a0f005b9b8ea)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_35](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/e9b83d84-53cf-48f5-907d-745279a1bed1)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_42](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/da5e445b-61eb-4731-a93c-a14bb64737d6)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_47](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/4349c710-e275-4806-afc9-489324f03fda)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_53](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/30f50398-98e7-4af0-b6d4-ebbbb72f210b)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_23_59](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/4336f157-e7f8-4768-80d4-1cdb4c6e3e4a)

![index html - Geekster_Assignments - Visual Studio Code 28-08-2023 23_24_06](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/98a5ebce-527e-4833-94a4-63305f27f145)

---
## OUTPUT:
![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_28_50](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/80acc381-6afb-470f-b6b8-622d2975e3b2)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_28_56](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/8b7468e9-deaa-44a0-9ca2-05ab63fdf962)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_00](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/8c0afa51-c851-431c-a8fc-75d91ab2dd84)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_10](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/44f8f10b-ced2-4c75-97a3-28ec0c74a7c5)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_14](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/66a98639-8001-43f5-84d7-d3216780ec39)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_24](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/5840d72e-93f4-415f-bebc-98c30ba0295f)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_32](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/ebca348f-38d6-41ff-81be-5e4d2234e585)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_38](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/643a47d1-5ad9-4785-bd3e-1f1b766e7a4b)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_46](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/f0022d19-0b55-4ca8-b8a8-3fe771f3307a)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_29_53](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/30c0e9e2-8cff-4c0b-b771-30134b9aca98)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_30_00](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/e1d3f9cb-bfe1-46d2-bd2a-46b5af0c8796)

![Booster Electric Scooters - Personal - Microsoft​ Edge 28-08-2023 23_30_08](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/assets/84591804/dd1f08a2-f7b2-4120-9a41-5f0124e9582f)

---
## Submission Required:
- GitHub Repository Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/tree/master/51_Weekly_Test_-6_CSS)
- README.md File Link: [Click Here](https://github.com/Abhishek-Sharma-007/Geekster_Assignments/blob/master/51_Weekly_Test_-6_CSS/README.md)
- Hosted Link: [Click Here](https://abhishek-sharma-007.github.io/Geekster_Assignments/51_Weekly_Test_-6_CSS/index.html)
