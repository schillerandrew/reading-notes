> # Context API - Behaviors

> ## Hooks and Context example

> ### 1.  With regard to the React Context API, what does a “provider” do?

Provides context/state updates to all of its connected consumers.

> ### 2.  With regard to the React Context API, how would we implement a “consumer” role?

Wrap a JSX element `CONTEXT-NAME.Consumer` around at least one function.

> ### 3.  Specifically with Context, how are we “wrapping” components to achieve our goals?

Components are wrapped with Provider elements to then pass context/state on to any of their children who use the Consumer element. Consumer elements aren't wrapped around components, but instead wrapped around functions inside of components. Because Context is able to be passed globally, it can be sufficient to wrap Provider around a component at or near the top, and be able to reach any component that's lower down -- not just direct children.

> ## Awesome React Context links

- [react-composer](https://github.com/jamesplease/react-composer)
  - This is a neat little component that allows you to nest render props, without multiple indentations making your code a lot wider. This is one of the few React Context libraries in the list that has a passing build and is being actively used -- 213,000 downloads a month supposedly -- and it's only 40 lines of code with supporting tests, README etc.

- [react-zap](https://github.com/troch/react-zap)
  - This app tries to bridge the gap between higher-order components and render props. It seems to even favor HoCs, but in one of the React Context articles, it sounded like devs prefer render props to HoC. Still, this app tries to make it so you don't necessarily have to choose between the two.