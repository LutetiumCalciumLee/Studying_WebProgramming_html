# Chapter 4 . Styling Web Pages with CSS3


**Key Points:**

- **What is CSS3?**  
  CSS3 (Cascading Style Sheets Level 3) is the latest standard for describing the look and formatting of web documents. It enables customization of colors, fonts, spacing, borders, backgrounds, and visual effects.

- **How to Apply CSS3:**  
  CSS3 styles can be added to HTML in three main ways:  
  - Inside a `` tag in the `` section (internal stylesheet)  
  - Directly in an element’s `style` attribute (inline style)  
  - By linking to an external `.css` file using the `` tag or `@import` rule (external stylesheet)

- **Selectors:**  
  CSS uses selectors to target HTML elements for styling. Types include:
  - Tag selectors (e.g., `h3 { color: brown; }`)
  - Class selectors (e.g., `.warning { color: red; }`)
  - ID selectors (e.g., `#list { background: mistyrose; }`)
  - Combinators for parent-child or descendant relationships
  - Attribute selectors (e.g., `input[type=text] { color: red; }`)
  - Pseudo-classes (e.g., `a:hover`, `li:active`, `h3:first-letter`)

- **Core CSS3 Properties:**
  - **Color and Background:** Control text color, background color, and background images, including position, size, and repeat options.
  - **Text Styling:** Adjust alignment, indentation, decoration (underline, overline, line-through), and shadow effects.
  - **Font Control:** Set font family, size, weight, style, and use shorthand properties for concise definitions.
  - **Box Model:** Every HTML element is a rectangular box consisting of content, padding, border, and margin. CSS3 allows precise control over each part, including border styles, widths, colors, and border-radius for rounded corners.
  - **Visual Effects:** Add shadows to text and boxes (`text-shadow`, `box-shadow`), and use images as borders (`border-image`).

- **Inheritance and Cascading:**  
  CSS properties can be inherited from parent to child elements. If multiple styles apply, CSS follows a priority order: browser defaults < external stylesheets < internal styles < inline styles.

- **Units:**  
  CSS3 supports various units for sizing and spacing, such as `px` (pixels), `em` (relative to font size), `%` (percentage), `cm` (centimeters), and more.

- **Cursor Control:**  
  The `cursor` property customizes the mouse pointer when hovering over elements.
