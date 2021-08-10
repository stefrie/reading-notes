#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)
***
# Code 201 | Reading 4 - HTML Links, CSS Layout, JS Functions
***
## From the Duckett HTML book:
### Chapter 4: Ch.4 “Links” (pp.74-93)
- Links are created using the `<a>` element.
- There is a root folder with child and grandchild folders (depending on how many levels)
- Relative URLs can be used if you're referencing a folder within the same directory. 
- Open new windows by using `<target="_blank">` in your `<a>` tag

### Chapter 15: “Layout” (pp.358-404)
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

## From the Duckett JS book:
### Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
- Functions and Methods
    - Declaring vs. calling a function
        - Declaring the function is defining the actions you want the code to take
        - Invoking the function (or "calling" the function) is actually asking the function to act
    - Getting values out of a function
    - Anonymouse functions and function expressions
    - Variable scope

### Article: “6 Reasons for Pair Programming”

***
#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)