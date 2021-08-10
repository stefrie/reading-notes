# Code 201 | Reading 8 - CSS Layout
***
## From the Duckett HTML book:
### Ch. 15, “Layout” (again; repeat of Class 4 reading)

- Positioning Elements using:
    - Normal Flow
    - Relative Positioning
    - Absolute Positioning
    - Floats

**CSS Displays**
- Display: inline
    - Puts an element inline with the other elements around it. Any height and width properties will have no effect
- Display: inline-block
    - Compared to `display: inline` the major difference is that `display: inline-block` allows us to set a width and height on the element
    - With `display: inline-block`, the top and bottom margins/padding are respected, but with `display: inline`, they are not.
    - Compared to `display: inline`, the major difference is that `display: inline-block` doesn’t add a line-break after the element, so the element can sit next to other elements.
- Display: block 
    - `<div>` is a block because it creates its own display block
    - Displays an element as a block element (like). It starts on a new line, and takes up the whole width of its containing element.

**Positioning**
- Static types
    - is standard where the element would normally fit on the screen
- Relative types
    - Relative - Elements that are `position: relative` can be moved out of their normal flow position while still taking up the same space. This is achieved by utilizing those offset properties (top, bottom, left, right) to offset the element, relative to itself.
    - Absolute - essentially does the same thing as position: relative, with two key differences:
        - Element is taken out of normal flow and leaves no space behind
        - Element is positioned relative to its nearest parent with a relative-type (relative, absolute, fixed) positioning
    - Fixed - same as absolute with one key difference:
        - Element is fixed to the viewport (on the page) and not to the code
    - Sticky - similar to fixed
        - Sticks the box to the screen, but if you use top: 0px, it will only go to the point you define

- Responsive design

- Fixed width vs. liquid layouts

- Grids



***

#### [Home](README.md) | [Code 102](102.md) | [Code 201](201.md) | [Code 301](301.md) | [Code 401](401.md)