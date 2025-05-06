# Cafe Menu

## Overview

This is a simple **Cafe Menu** built with HTML and styled with CSS. The menu displays coffee and dessert items with their respective prices. It features a background image of coffee beans and is styled in a warm, inviting way. The design is responsive, ensuring a good user experience across various screen sizes.

## Structure

### HTML File (`index.html`)

- **`<head>` Section:**
  - **Meta tag:** Sets the character encoding to UTF-8 for proper text rendering.
  - **Meta Viewport tag:** Ensures the page is displayed correctly on all screen sizes, making it mobile responsive.
  - **Title tag:** Specifies the title of the page as "Cafe Menu", which appears in the browser's tab.
  - **Link to External CSS:** Includes the `styles.css` file for styling the page.

- **`<body>` Section:**
  - **Main Menu (`.menu`):** Contains all the content of the cafe menu.
    - **`<main>`:** The main section of the page.
      - **Main Heading (`<h1>`):** Displays the title "CAMPER CAFE".
      - **Established Year (`<p class="established">`):** Displays the establishment year in italic.
      - **Horizontal Rule (`<hr>`):** Used to separate content sections visually.
      
    - **Coffee Section:**
      - **Heading (`<h2>`):** Displays the heading "Coffee".
      - **Image:** Displays a coffee-related image with `src` and `alt` attributes.
      - **Articles (`<article class="item">`):** Each article represents an individual coffee item, including:
        - **Flavor (`<p class="flavor">`):** The name of the coffee flavor.
        - **Price (`<p class="price">`):** The price of the coffee.

    - **Dessert Section:**
      - **Heading (`<h2>`):** Displays the heading "Desserts".
      - **Image:** Displays a dessert-related image.
      - **Articles (`<article class="item">`):** Each article represents an individual dessert item, with similar structure as the coffee section.

    - **Footer:**
      - **Link (`<a href>`):** A link to "Visit our website", which opens in a new tab.
      - **Address (`<p class="address">`):** Displays the cafe's address.

### CSS File (`styles.css`)

The **CSS file** provides the styling for the HTML elements and defines the layout and appearance of the menu.

- **Body:**
  - The body has a background image of coffee beans, which is set as the `background-image`.
  - The `font-family` is set to `sans-serif`, and padding is added around the menu.

- **Headings:**
  - **`<h1>`:** The title of the menu is styled with a large font size and has a margin at the top and bottom.
  - **`<h2>`:** The subheadings like "Coffee" and "Desserts" are styled with a smaller font size.

- **Menu Layout:**
  - The `.menu` class sets the width of the menu container, centers it, and adds padding.
  - It also includes a background color (burlywood) and a maximum width to ensure the layout remains clean on larger screens.

- **Images:**
  - Images are displayed as block-level elements, centered horizontally with `margin-left: auto` and `margin-right: auto`.
  - The images are slightly pulled up to reduce the space between them and the headings.

- **Horizontal Rule (`<hr>`):**
  - The horizontal rule is styled with a brown color and a height of 2px.

- **Menu Item Styling:**
  - Each **menu item** (`<article class="item">`) has **flavor** and **price** text aligned on the same line with different text alignments: the **flavor** text is left-aligned and the **price** is right-aligned.

- **Footer Styling:**
  - The footer has small text with a light grey address and a **link** that changes color when hovered.

## Usage Instructions

1. **Clone or Download:** Download or clone the files from this repository to your local machine.
2. **View in Browser:** Open the `index.html` file in your browser to view the cafe menu.
3. **CSS Customization:** You can modify the `styles.css` file to customize the appearance of the menu to fit your needs.

## Compatibility

- This menu layout and styling are compatible with modern browsers such as Chrome, Firefox, Safari, and Edge.
- The layout is responsive, adjusting to different screen sizes (mobile, tablet, and desktop).
