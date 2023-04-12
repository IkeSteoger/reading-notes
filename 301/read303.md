# 301 Reading 03

## Lists and Keys

`map()` returns a new array that is the same length as the old one.

To loop through an array and display each value in JSX you could use the `map()` method.

Each list item neds a unique key.

The purpose of a key is to help React identify which items have been changed, are added, or are removed. (reactjs.org)

## The Spread Operator

The spread operator or spread syntax refers to the use of an ellipsis of three dots `(...)` to expand an iterable object into the list of arguments (medium.com)

The spread operator can "spread" arrays in to separate arguments. It can also copy an array, concatenate/combine arrays, use Math functions, use an array as arguments, add an item to a list, add to state in React, combine objects, and convert NodeList to an array. (medium.com)

To combine an array, you could do the following:

>`const array1 = [1]`
>
>`const array2 = [2]`
>
>`const combinedArray = [...array1,...array2]`

To add new item to an array with the spread operator you would do something like the following:

>`const array1 = [1]`
>
>`const addToArray = [2, 3, ...array2]`

To combine two objects into one with a spread operator, do the following:

>`const objectOne = {hello}`
>
>`const objectTwo = {world}`
>
>`const combinedobjecy = {...object1,...object2, "!"}`

## Pass Functions Between Components

The first step to pass functions between components is create the function where ever the state is we are going to change.

The `increment` function in the video will loop through the array and checks if the names are matching if it does then it increments the count up by one, then updates the state at the end.

You can pass a method from a parent component into a child component by adding the method as a prop to the child component.

The child component can invoke a method that was passed to it by the parent by using `this.props.method()`.


## Things I want to know more about

I think I need to spend some time practicing passing methods around, it seems fairly simple but I worry it can get complex with more and more methods?
