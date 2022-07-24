> # useState() Hook

> ## Introducing Hooks

> ### 1. What was the motivation for introducing Hooks?

Reusing or sharing stateful logic used to require significant changes/restructuring of component hierarchy -- using Hooks avoids this. Hooks also allows stateful logic to be broken down in new ways, and it offers a non-class syntax that is more user-friendly for people who are newer to JavaScript.

> ### 2. What changes are important regarding implementing Hooks versus Component Classes?

`this` is used very differently in JavaScript compared to other languages and can sometimes be a barrier. Because Hooks don't use classes, you don't need to learn how to use `this`.

> ### 3. Hooks allow you to reuse stateful logic without changing:

component hierarchy

> ## [hooks api](https://reactjs.org/docs/hooks-overview.html)

> ### 1. Name two rules imposed by React Hook usage.

- Hooks should only be called at the top level -- not inside loops, conditions or nested functions.
- Hooks should only be called from within React function components (or within custom Hooks) -- not regular JavaScript functions.

> ### 2. How would you identify a custom Hook and why might you create one?

Custom Hooks have names starting with `use` and they call other Hooks. Custom Hooks can be utilized to reuse stateful logic between components.

> ## the state hook

> ### 1. What is a Hook?

A special non-class function that lets you access state and other features within React.

> ### 2. When would I use the useState Hook?

When state is needed inside that component.

> ### 3. If you were to add React state to a function component by declaring a state variable:

What does calling useState do? It declares a state variable (without using class syntax/logic).

What do we pass to useState as an argument? the initial value of the state variable

What does useState return? a pair of variables: the current state and function that updates the state
