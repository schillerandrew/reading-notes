> # State and Props

1. `render` occurs before 'componentDidMount'
1. `constructor()` is the first thing that happens in a lifecycle
1. constructor -> render -> componentDidMount -> React Updates -> componentWillUnmount
1. because `componentDidMount()` is called immediately after a component mounts, it's used for certain connections, such as network requests, DOM initializations, subscriptions, API connections, etc

- three phases of a component's lifecycle:
  - mounting
  - updating
  - unmounting
  ```
  What types of things can you pass in the props?
  ```
1. pretty much any kind of data that a different component will need -- kind of like arguments for a function

    ```
    What is the big difference between props and state?
    ```
1. props are sent to different components and handled elsewhere, whereas state remains inside a component and is handled there

    ```
    When do we re-render our application?
    ```
1. user interactios, user inputs, state changes

    ```
    What are some examples of things that we could store in state?
    ```
1. anything that will change: counters/increments, user input, event handling


  