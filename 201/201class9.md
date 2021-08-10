#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)
***
# Code 201 | Reading 9 - Forms and JS Events
***
## From the Duckett HTML book:
### Chapter 7: “Forms” (p.144-175)
**Form Controls**
- adding text by text input, password input, text area (multi-line)
- making choices by using radio buttons, checkboxes, or dropdown menus
- submitting forms by using submit buttons, image buttons
- upload files

**Form Structure**
- `<form>` - element should carry the action attribute and will also have a method and id attribute
- `action` - attribute is the URL where the data will be stored once submitted
- `method` - can use `get` or `post` methods to send data to the URL
- `id` - used to identify the form from other elements on the page

**Input**
- `type="text"` creates a single line of text input
- `type="password"`same as text, but blocks out the characters when they're being typed
- `<textarea>` creates a larger text box where you can add several lines of comments
- `type="radio"` creates radio buttons for users to choose one
- `type="checkbox"` creates boxes for users to choose several options
- `<select>` creates a dropdown list
- `<option>` specifies the options the user can choose from
- `type="file"` creates a box that looks like a text input line, but includes a "browse" button to add files
- `type="submit"` creates a button to send the form data to the server
- `type="image"` allows you to use images for the submit button
- `type="hidden"` is a hidden form control for page authors


### Chapter 14: “Lists, Tables & Forms” (pp.330-357)
**CSS Properties for Creating Lists, Tables, and Forms**
- List Styles
    - `list-style-type` allows you to control the shape or style of a bullet point
    - `list-style-image` allows you to use your own image for the bullet points
    - `list-style-position` allows you to change the indentation if there's a word wrap
    - `list-style` shorthand allows you to add all of the above within one key:value pair

- Table Properties
    - width
    - padding
    - text-transform
    - letter-spacing, font-size
    - border-top, border-bottom
    - text-align
    - background-color
    - :hover
    - empty-cells (this allows to hide the border on empty cells)
    - border-spacing, border-collapse

## From the Duckett JS book:
### Chapter 6: “Events” (pp.243-292)
**Events** are what happens any time a user interacts with a web page. They can have no resulting effect to the user, or they can take action (such as changing the color of a button as you hover over it)
**Binding** is what connects the event that needs to happen with the actual element on which it should occur


***
#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)