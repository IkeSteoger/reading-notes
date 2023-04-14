# 301 Reading 05

## Thinking in React

The `single responsibility principle` means that each component should only be doing one task, relying on other components to do their tasks as well.

Building a static version of your app means to create it and have it displaying properly before working in interactivity.

Once you have a static version of your app, then its time to add in a state & start creating interactivity.

The three questions to determine if you are working with state:

>Does it remain unchanged over time? if so, it isn't state
>
>Is it passed in from a parent via props? if so, it isn't state.
>
>Can you computer it based on existing state or props in your component? if so, it isn't state.
(react.dev)

To identify where a state should live you should idenfity EVERY component that renders something based on state, then find their closest common parent component, and if you can't find a component where it makes sense - make one solely for holding the state!

## Higher-Order Functions

A higher-order function is a function that operates on other functions, either by taking them as arguments or returning them.
(eloquentjavascript.net)

>`function greaterThan(n) {`
>`return m => m > n;`
>`}`

The second line of the above code is returning `m` when `m` is greater than `n`.

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values.

## Things I want to know more about

Am I even correct on the last two higher-order function questions? Seems quite abstract.
