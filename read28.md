> # `useEffect()` Hook

> ## effects hook

> ### 1.  What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?

`useEffect()` combines the functionality of the class methods, such as `componentDidMount`, `componentDidUpdate`, and `componentWillMount`, for performing side effects.

> ### 2. When using the useEffect Hook:

What does useEffect do? It lets React know that a side effect must be performed after the component is rendered.

Why is useEffect called inside a component? For easy access to state and props.

> ### 3. Explain the importance of properly implementing effects with Cleanup

If effects that require cleanup aren't properly implemented, this can introduce bugs or performance issues with potentially major consequences.
