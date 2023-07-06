# 401 Reading 36

## Application State with Redux

[Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)

### What is the first principle of Redux?

Redux is a singular store for data sharing.

### What is a store and what do we use our reducers for within that store?

The store has the current state value & the reducer within itself. We use our reducer to take in previous state and an action and make a new updated instance of state.

### Name three Redux store methods given to us by createStore and describe their use

- getState() - return the current state of object tree
- dispatch(action) - dispatch the action to change the state of object tree
- subscribe(listener) - listen to changes in the state of object tree

### Explain to a non-technical recruiter what combineReducers() does and why it is useful

CombineReducers allows you to call many reducers at once, or make many changes at once. This basically is like making changes to work flow that would allow you to change multiple things around the office at once, rather than walking around to each section of the office, making changes one by one.

### Bookmark and Review

- [worlds easiest guide to redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)
- [testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux Docs](https://redux.js.org/)

### Looking ahead at this module’s course schedule, What do you look forward to learning?

I'm nervous and excited about mock interviews.

### What are your learning goals after reading and reviewing the class README?

Continue to wrap my head around State & how Redux changes it.

