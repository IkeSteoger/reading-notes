# 301 Reading 02

## State and Props

### React Lifecycle

This diagram seems to show that 'render' happens before the 'componentDidMount'

The very first thing in the lifecycle of react is the mounting of the constructor.

The order is:

1. Constructor
2. render
3. React Updates
4. componentDidMount
5. componentWillUnmount

### React State vs Props

The type of things you can pass into props are things to be rendered or shown to the user.

The big difference between props & state that state are within and component, and props get handled out of the component and must be updated outside of the component.

We re-render our application when State gets changed

Some examples of things to be stored in state include user input or something that needs to be changed and then re-rendered while props cannot be changed without working in the code itself.
