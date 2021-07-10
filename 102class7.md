# JavaScript

## Expressions and Operators
An **expression** is any valid unit of code that resolves to a value.

## Functions 
**Functions** are similar to a procedure or process. It includes:
- Name of the function
- List of parameters to the function, enclosed in parentheses and separated by commas
- JS statements that define the function, enclosed in curly brackets `{...}`

## Control Flow
The **control flow** is the order in which the commputer executes statements in a script. It will always run in order from first line to last line, unless there is a loop unless or until a condition is met, or a conditional that requires skipping part of the code.

What happens in the function STAYS in the function.

When you write a function, JavaScript does something called "hoisting" that looks for executable code. A function is not executable, you need to **call** or **invoke** the function. 

```
function getTime(){
    let today = new Date();
    let hourNow = today.getHours();
    let greeting;

    if (hourNow > 18) {
      greeting = 'Good evening';
    } else if (hourNow > 11) {
      greeting = 'Good afternoon';
    } else if (hourNow >= 0) {
      greeting = 'Good morning';
    } else {
      greeting = 'Welcome';  
    }
    
    document.write ('<h3>' + greeting + '</h3>')'
}

getTime();
```

**Refactoring** your code makes the code more efficient, but *does not* change the outcome of the code at all.


***

#### [Home](README.md) | [Code 102](102.md) | [Code 201](201.md) | [Code 301](301.md) | [Code 401](401.md)