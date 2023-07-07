# 401 Reading 37 - Combined Reducers

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

### Why create multiple reducers?

You would create multiple reducers to avoid reducer machine becoming the bottleneck.

### How would you combine multiple reducers?

Redux provides the `combineReducers()` method.

### How will you manage state as an immutable object? why?

To manage state you have to change it with actions & reducers. This is so that everything else can detect if the state has changed. (I think, I don't really know.)

## [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

### combineReducers is a utility function to simplify the most common use case when writing \_\_\_ \_\_\_\_\_

Redux reducers

### Explain how combineReducers assembles the new state tree

It calls each slice reducer with its current slice of state & the current action, giving the slice reducer a change to respond & update state if needed.

### How would you define initial state in an app using combineReducers?

```JavaScript
initialState = {
    stuff: things
}
```

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

### Why will you want to split your reducing functions as your app becomes more complex?

Because as there is more complexity, you might want to make sure your reducing functions are only doing certain changes with certain state so there is no bottleneck.

### The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____

`combineReducer` --- `createStore`

### What is a popular convention when naming reducers?

Naming the reducer after the state slice it manages

### What are your learning goals after reading and reviewing the class README?

Understand more about how actions work - do they always set each other off if you use the same case name???
