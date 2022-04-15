> # Putting it all together

## Thinking in React

1. What is the single responsibility principle and how does it apply to components?
    - A design technique that says each component should do only one thing. If a component starts doing more than one thing, it should be broken down into smaller components, so that each component only does one thing.

1. What does it mean to build a ‘static’ version of your application?
    - a version that doesn't use state yet (only props) and can't do any user interactivity -- thus the name "static"

1. Once you have a static application, what do you need to add?
    - state, and interactive user interface features

1. What are the three questions you can ask to determine if something is state?
    - Does it come in from a parent through props?
    - Does it stay the same over time?
    - Can it be computed based on other state or props?

1. How can you identify where state needs to live?
    - Look at every component that uses that state, and find a common parent where the state should be. The state can even be higher up than the nearest common parent, and the state doesn't need to go inside an already existing component -- you can create one if needed just to house a state.

    ## Higher-order Functions

1. What is a “higher-order function”?
    - a function that operates on other functions, such as using a function for an argument or a return value

1. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
    - It's certainly returning a value, but I'm not certain -- perhaps a boolean based on whether the `m` argument is greater than `n`?

1. Explain how either map or reduce operates, with regards to higher-order functions.
    - map is a classic example of a higher-order function, because it's able to take in a function as one of its arguments. As it loops through all of the elements in an array, it can apply a functoin to each of those elements and return the new elements into a new array.