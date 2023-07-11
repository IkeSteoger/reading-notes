# 401 Reading 39

## Redux - Additional Topics

### [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

#### What concerns are addressed by Redux Toolkit?

Redux Toolkit addresses several concerns related to Redux development, including reducing boilerplate code, simplifying store setup, providing a standard approach for defining reducers and actions, enabling immutability by default, and supporting the use of Redux middleware.

#### What does configureStore() do?

The configureStore() function is a utility provided by Redux Toolkit that simplifies the setup of a Redux store by combining several steps into a single function call. It automatically configures the store with sensible defaults, including the use of the Redux DevTools Extension for debugging, and allows for easy customization of middleware and other store options.

#### How would I use createSlice()?

To use createSlice() from Redux Toolkit, you would define a slice of your Redux state by specifying an initial state and an object containing reducers. It automatically generates action creators and action types based on the provided reducers, allowing you to easily create and handle actions for that specific slice of state.

### [MobX](https://mobx.js.org/getting-started.html)

#### What is Mobx?

Mobx is a state management library for JavaScript applications, including React, Angular, and Vue. It enables developers to create observable data structures that automatically update the user interface whenever the underlying data changes. Mobx follows the principle of “observable programming,” where any changes made to the observed data are automatically tracked and propagated to the relevant components, simplifying the process of managing and synchronizing state in applications.

#### How does MobX make it “impossible” to produce an inconsistent state?

Mobx achieves consistency in state by leveraging the concept of observable data and reactive updates. Whenever a piece of data marked as observable changes, Mobx automatically triggers the necessary reactions to update any dependent components or computations. This reactive nature ensures that the state and UI are always in sync, eliminating the possibility of inconsistent or out-of-date data. Additionally, Mobx provides mechanisms like computed values and actions, which enforce proper data manipulation and encapsulation, further preventing inconsistencies in the state.

#### How would we build a reactive user interface?

To build a reactive user interface, we can use a reactive programming library like Mobx or RxJS. By defining observable data and reactive computations, we establish a relationship between the data and the UI, allowing the UI to automatically update whenever the data changes, creating a seamless and reactive user experience.

### Tutorial

#### What take-away(s) did this tutorial provide?

The tutorial gave me a little better insight into redux. Hoping to make good use of createSlice()

### [Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

### [HookState](https://hookstate.js.org/)

#### What are your learning goals after reading and reviewing the class README?

Properly understand createSlice()
