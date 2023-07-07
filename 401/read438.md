# 401 Reading 38 - Redux - Asynchronous Actions

## [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

### Why use Redux middleware?

By itself, REdux store doesn't know anything about async logic. Redux middleware were designed to enable writing logic that has side effects.

### Consider the Redux Async Data Flow Diagram. Describe the flow in your own words

UI rendered using initial state, something happens (such as button click), app code dispatches the action to the store, the store runs reducer function (updating state), the store notifies all parts of the UI that the store has been updated, the UI re-renders if it needs to. but with Async function, you would be able to run logic like AJAX requests before dispatching actions.

### How are we accommodating async in our Redux app?

By using middleware, perhaps Redux Thunk

## [thunk middleware](https://github.com/reduxjs/redux-thunk)

### Why would you need redux-thunk middleware?

To handle async actions in Redux

### Redux Thunk middleware allows you to write action creators that return a ____ instead of an action

function

### Describe how any return value from the inner thunk function will be made available

Any return value from the inner function will be available as the return value of dispatch itself.

### What are your learning goals after reading and reviewing the class README?

Truly understand Redux & how to use middleware appropriately.
