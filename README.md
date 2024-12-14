# CSS-Exersice
---

# Image1
# Simple Table Styling Example
## HTML Structure
1. **Title**:
   - A header `<h3>` displays the title **"Table Style"**.

2. **Table Content**:
   - A 2x3 grid with labeled cells like `R1, C1` to `R2, C3` for easy identification.

## CSS Highlights
1. **Table Layout**:
   - **Border Spacing**: The table cells are separated by `12px` for a neat layout.

2. **Cell Styling (`<td>`)**:
   - **Borders**:
     - Each cell has a solid dark gray border (`rgb(68, 65, 65)`).
     - Borders are rounded with a `5px` radius for a softer appearance.
   - **Padding**:
     - Cells have `8px` padding, ensuring adequate space around the text.
   - **Box Shadow**:
     - A subtle shadow (`0 4px 4px rgb(83, 81, 81)`) adds a 3D effect, making the cells visually appealing.

3. **Heading Styling (`<h3>`)**:
   - Positioned slightly to the left (`margin-left: 4px`) for alignment.
---
# Image2
# Floating Articles Layout
## HTML Structure
- A container `<div>` with the class `main` holds the content.
- A heading (`<h3>`) serves as the title.
- Multiple `<p>` elements are styled to appear side by side.
- A special `<p>` with the ID `midP` has unique styling and a scrollable feature.

## CSS Highlights
1. **Container (`.main`)**:
   - Light beige background with a black border.
   - Fixed width (`750px`) and padded content.

2. **Paragraphs (`.main p`)**:
   - Fixed size (`200px x 105px`), gray background.
   - Inline-block display for horizontal alignment.

3. **Special Paragraph (`#midP`)**:
   - Wider (`84%`) with black top/bottom borders.
   - Bold text and scrollable overflow for longer content.

4. **Heading (`h3`)**:
   - Left-aligned with consistent spacing.
---

# Image3
# Styling Experiment with Links and Lists
## HTML Structure
1. **Heading and Horizontal Rule**:
   - A main heading (`<h4>`) with a styled `<hr>`.

2. **Paragraphs with Links**:
   - Regular `<p>` elements with embedded `<a>` tags.
   - Nested `<span>` for added customization.

3. **Unordered Lists**:
   - Main `<ul>` with nested `<ul>` levels.
   - List items (`<li>`) include both text and links.

## CSS Highlights
1. **Paragraph Styling**:
   - Text inside `<div>` styled in **blue** (`div p`).
   - Links inside `<div>` are **orange** (`div a`).

2. **Highlighted Links**:
   - Links within `<span>` have a **yellow background** and **brown text**.

3. **Nested List Styling**:
   - Nested list items (`ul li ul li`) are **blue**.
   - Bold styling applied to certain elements:
     - The list item "111" and "red" via `ul li ul span`.

4. **Horizontal Rule (`<hr>`)**:
   - Floated to the left with a **25% width**.

5. **Nested Indentation**:
   - Nested `<ul>` with additional indentation (`margin-left: 40px`).
   - Custom list styling disables bullets (`list-style: none`).
   ---

# Imag4
## Table Styling with Hidden Elements
## HTML Structure
1. **Two Tables**:
   - **Table 1 (`.t1`)**:
     - A 3x4 grid with some hidden cells (`.tdh`).
   - **Table 2 (`.t2`)**:
     - A 2x4 grid positioned to the right of Table 1.

2. **Table Content**:
   - Text values inside `<td>` cells, organized row by row.

## CSS Highlights
1. **General Table Styling**:
   - **Background Color**: Light gray (`rgb(243, 241, 241)`).
   - **Positioning**: 
     - Tables have a relative position.
     - Margins separate the two tables (`margin-left` for `.t2`).

2. **Cell Styling**:
   - **Cell Colors**: Each `<td>` has a light gray background (`rgb(234, 230, 230)`) with navy text (`rgb(47, 61, 128)`).
   - **Borders**: Thin, rounded borders with no top border.
   - **Padding and Alignment**: Centered text with consistent padding.

3. **Hidden Cells**:
   - Cells marked with the `.tdh` class are **completely hidden** using `visibility: hidden`.

4. **Positioning Adjustments**:
   - Tables and cells have slight position offsets using `top`, `left`, and `right` properties.
