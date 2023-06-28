# 401 Reading 32

## Context API - Behaviors

### [Scaling Up with Reducer and Context](https://react.dev/learn/scaling-up-with-reducer-and-context)

#### How do useReducer and useContext work together to simplify state management in a React application?

Reducers help keep event handlers short & concise. Using them in conjunction with useContext you can use it as an alternative to passing props. Then all children components in the tree can access the state without 'prop drilling'.

First, `useReducer` hook on the current functions you want to update. Then you must create two seperate contexts. Export them the file so they may be used. Second, put state & dispatch into context. Finally, use your context anywhere in your tree!