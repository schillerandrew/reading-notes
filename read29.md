> # Advanced State with Reducers

> ## useReducer hook

> ### 1.  Name an alternative to the useState Hook.

`useReducer()`

> ### 2.  Why might the useReducer Hook be preferable to the useState Hook?

`useReducer` is better for more complex state logic, such as when there are multiple sub-values, or the next state depends on the previous state.

> ### 3.  What are two ways to set the initial state?

- pass in the initial state as a second argument
- pass in an `init` as a third argument; the `init`'s argument becomes the initial state

> ## Ultimate Guide to useReducer

> ### 1.  In terms of state, what does useReducer expect to receive as a parameter?

Two parameters: a `reducer` function first, and the initial state second.

> ### 2.  What does useReducer return?

an array containing: the current state, and a `dispatch` function

> ### 3.  Explain dispatch to a non-technical recruiter.

`dispatch` is sort of a "helper" for `useReducer`. `dispatch` contains a `type` and a `payload`. The `type` gives more information about the dispatch -- what "type" of dispatch it is. And the `payload` is the value that will be used to update state. If you're resetting a state value to it's initial state, your `dispatch` might have a `type` of `reset`, and its `payload` might be equal to initial value of the state. So in resetting that state value, the `dispatch` says hey just so you know this is a reset, and here's the `payload`, just set the state to this payload, ok?
