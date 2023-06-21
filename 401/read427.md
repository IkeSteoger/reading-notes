# 401 Reading 27

## `UseState()` Hook

[Thinking in React](https://react.dev/learn/thinking-in-react)

### Summarize the five steps of thinking in react

1. Break the UI into component hierarchy
2. Build a static version in React
3. Find the minimal but complete respresentation of UI state
4. Identify where your state should live
5. Add inverse data flow

[State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)

### What is one reason a local variable isn’t sufficient for managing a React component?

1. Local Variables don't persist between renders
2. Changes to local variables won't trigger renders

### What is the argument to the `useState` hook, and what are the two parts of its return array?

Retain the data & trigger React to render the component

1. A state variable to retain the data between renders
2. A state setter function to update the variable and trigger React to render again

### How can Component A access state from Component B?

Using the `useState` hook will allow access between two components.

### Bookmark and Review

- [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)
- [Rendering Lists](https://react.dev/learn/rendering-lists)
- [State as Snapshot](https://react.dev/learn/state-as-a-snapshot)
- [`useState` hook](https://react.dev/reference/react/useState)

### What are your learning goals after reading and reviewing the class README?

I hope to truly understand state & how to pass it around properly.
