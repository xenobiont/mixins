# Tasks

## Part 1

### variables

set the background for .parent and .child elements, using global sass variables

### square mixin

Write a mixin 'size', that will allow to set dimensions of the element (width and height).
If one argument is passsedit should produce a square.

### center mixin

Write a mixin 'center', that will center the contents of the block.
Use any way of centering that you know (e.g. using css grid, flex etc) Your Mixin should be able to center the content:

- on both directions at once (by default)
- only horizintally
- only vertically

make .parent and .child elements loo like squares (parent bigger than the child) and center the .child inside .parent.

### round

create subtypes for parent and child that have a round shape,
by extending the basic class. Use nested selectors.
Use mixin for that and CSS property 'border-radius: 50%'. Add HTML elements to demonstrate

### hoverable

create a mixin that will scale the element on hover (using transform:scale(1.2)) property
and apply it to round child element

## Part 2

extract all your global variables, mixins and placeholders in separate files, and use them in your main file

## Hint

in case of problems or strange behaviour, reload the browser page
