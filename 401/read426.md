# 401 Reading 26

## Component Based UI

### What are the building blocks of a React app?

Components! A component is a piece of the UI (user interface) that has its own logic and appearance. A component can be as small as a button, or as large as an entire page. (react.dev/learn)

### What is the difference between an HTML element and a React component?

A React component is an object represenation of a DOM node. Its a plain old object, and not an actual DOM HTML element.

### What is JSX and why do we use it?

JSX is a markup syntax for using React. It's optional but most React projects use JSX. JSX is stricter than HTML. You must close tags. Also components can't return multiple JSX tags. You must wrap them into a shared parent, ala `<>...</>`

### Describe the process of embedding JavaScript expressions in JSX

You can put any valid JavaScript expression inside the curly braces in JSX.

### Does React or JSX have any special features for iteration or conditional logic?

There are no special syntax for writing conditions, use the traditional JavaScript conditional logics.

### How does React know to respond to a user’s inputs?

Using an Event Handler!

### What word indicates that a React component manages data with a Hook?

`useState` indicates that a React component manages data with a Hook.

### How can two react components share data?

The parent component must hold the information and keep both children updated.

### What are the three steps of refreshing a React UI?

1. Triggering a render
2. Rendering the component
3. Committing to the DOM

### How do you trigger updates to a component after the initial render?

Update the state with the `set` function.

### Does React recreate DOM nodes on every rerender?

It doesn't update every node in the DOM.

### After React has updated the DOM, what still needs to happen before the user sees the change?

It will be re-rendered

### Bookmark and Review

- [Your First Component](https://react.dev/learn/your-first-component)
- [Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)
- [Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)
- [sass cheatsheet](https://devhints.io/sass)
- [react cheatsheet](https://devhints.io/react)

### Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?

It seems often that we use camelCase for most variables.

### Looking ahead at this module’s course schedule, What do you look forward to learning?

I'm excited to learn more about React.

### What are your learning goals after reading and reviewing the class README?

Understand JSX!

### Things I want to know more about

React!
