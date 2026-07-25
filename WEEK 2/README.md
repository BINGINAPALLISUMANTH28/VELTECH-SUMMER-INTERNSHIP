# Week 2: CSS Training & UI Styling
**South Central Railway WWO Vijayawada Division - Full Stack Intern Weekly Report**

## Theory Notes

### Introduction to CSS & Integrating Styles
- **CSS (Cascading Style Sheets):** Used to style and layout web pages.
- **Integration Methods:**
  - **Inline:** Using the `style` attribute inside HTML tags (e.g., `<p style="color: red;">`).
  - **Internal:** Using `<style>` tags within the `<head>` section of an HTML document.
  - **External:** Linking an external `.css` file using the `<link rel="stylesheet" href="style.css">` tag (Best practice for maintainability).

### Selectors, Colors, and Background Properties
- **Selectors:** Used to target HTML elements for styling.
  - Element selector (e.g., `p`, `h1`)
  - Class selector (e.g., `.my-class`)
  - ID selector (e.g., `#my-id`)
  - Universal selector (`*`)
- **Colors:** Can be defined using names (e.g., `red`), Hex codes (e.g., `#ff0000`), RGB (e.g., `rgb(255, 0, 0)`), or HSL.
- **Backgrounds:** Properties like `background-color`, `background-image`, `background-size`, and `background-repeat`.

### The CSS Box Model
- **Box Model:** Every HTML element is essentially a box.
  - **Content:** The actual text/image.
  - **Padding:** Space between the content and the border (inside the box).
  - **Border:** A line surrounding the padding and content.
  - **Margin:** Space outside the border, separating the element from others.
- Total element width/height = content + padding + border + margin.

### Layout techniques & Element Positioning
- **Positioning:**
  - `static`: Default, follows normal document flow.
  - `relative`: Positioned relative to its normal static position.
  - `absolute`: Positioned relative to its closest positioned ancestor.
  - `fixed`: Positioned relative to the viewport, stays in place during scrolling.
  - `sticky`: Toggles between relative and fixed depending on scroll position.
- **Display:** `block`, `inline`, `inline-block`, `none`.
- **Modern Layouts:** Flexbox (1D layouts) and Grid (2D layouts).



## Practice Summary
- Implemented an external stylesheet (`style.css`).
- Used various selectors (ID, Class, Element) to style content.
- Applied the Box Model concepts (margins, padding, borders) to structure elements.
- Explored Flexbox for laying out elements side-by-side.

