> # React and Forms

## Forms

1. What is a ‘Controlled Component’?
    - a component that renders something and also controls the state of user inputs that are part of the rendered thing 
1. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
    - User inputs should be put into state as soon as possible because state can be slow enough to where there is a gap that makes it appear as if state didn't change. Sometimes it's even necessary to break down code so that state updating is separate from state handling, to avoid critical gaps in state changes -- so the sooner state can be updated, the more likely gaps are likewise avoided.
1. How do we target what the user is entering if we have an event handler on an input field?
    - `event.target.value` or `event.target.name` in tandem with a `name` label

## Conditional (Ternary) Operator

1. Why would we use a ternary operator?
    - potential for shorter syntax, cleaner and clearer code, etc.

1. Rewrite the following statement using a ternary statement:
    - `if x === y ? console.log(true) : console.log(false);`