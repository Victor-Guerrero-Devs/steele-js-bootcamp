# Timer

## About

First project from the part 2 section

A timer with an animated border that goes around the circle in tandem with the countdown on the timer

## Keyword This

In order to have 'this' within methods to refer to the object made by the constructor, you have to declare the method with the arrow syntax.

If you use the pre-ES6 function declaration, 'this' will not refer to the
object.

### Good

`printToConsole = () => console.log(this)`

### Bad

`printToConsole() { console.log(this) } `
