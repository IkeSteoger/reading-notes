# 401 Reading 15

## Advanced State with Reducers

### [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

#### What is the motivation for adding a reducer?

As components grow in complexity, it can get harder to see at a glance the different ways in which a components state gets updated.

#### What are actions in the context of a reducer? How are they different than setting state directly?

Actions are objects that describe the state they change. Actions are different form settings state directly because they provide a standardized way to describe state changes.

#### What common list operation is useReduce named for, and why?

Its named after the operation `reduce()`, because that operation lets you take an array and "accumulate" a single value out of many.

#### When should you switch from useState to useReducer?

"We recommend using a reducer if you often encounter bugs due to incorrect state updates in some component, and want to introduce more structure to its code. You don’t have to use reducers for everything: feel free to mix and match! You can even useState and useReducer in the same component." (react.dev)

### Bookmark and Review

- [useReducer hook](https://react.dev/reference/react/useReducer)
- [Keeping Components Pure](https://react.dev/learn/keeping-components-pure)
- [Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

### Reflection

#### What are your learning goals after reading and reviewing the class README?

Understand `useState` `useReducer` and `useEffect` better.
