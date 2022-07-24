> # Component Based UI

> ## react hello world

> ### 1. What are the building blocks of a React app?

elements and components

> ### 2. What is the difference between an element and a React component?

Elements describe what the visual output (the user's screen) should look like, and they go inside of components. Components are more like Javascript functions or Node modules (files) and they are arranged together to form the entire front end.

> ### 3. What are some advantages of React’s component based architecture?

React's advantages center on extreme modularization. Components are already very modularized -- often existing in their own files and connecting to each other and back to the root app file. But also there's no need to interact directly with the DOM, so changing one component is even less likely to impact other components -- even more so than usual. Similarly, JSX is easily incorporated into React, which eliminates even more overlap between JS and HTML, and different components or functionalities.

> ## Introducing JSX

> ### 1. What is JSX and why do we use it?

JSX is a syntax extension within JavaScript, and it's used to weave together JavaScript and HTML. JSX is not required, but it's a popular tool used within React.

> ### 2. Describe the process of embedding JavaScript expressions in JSX.

Any valid JavaScript expression can be embedded in JSX by simply enclosing it in curly brackets: `{}`.

> ### 3. Is it safe to embed user input in JSX? Explain.

Yes, because everything is converted into a string before being rendered. So anything which isn't explicitly part of an app, won't be rendered -- malicious code can't come in via normal user inputs.

> ### 1. Explain what a React Component is to a non-technical friend.

React apps are broken down into smaller pieces -- components. Different components do different things. One way to think about components is see them as different physical tools, like a hammer or a screwdriver. You don't combine a hammer and a screwdriver, you keep them separate. It's similar in a React application. If things are different enough, they become their own components.

> ### 2. Describe mutability and React Components, specifically, how is the UI updated?

Mutability is basically whether something can be altered or not: Immutable things generally cannot be altered, or only altered in certain ways, whereas mutable things are generally easy to alter. In React, the UI is updated by re-running the render method and displaying the most up-to-date UI. 

> ### 3. If changes are made to the UI, what does React update?

The DOM is only updated according to the specific UI parts that were changed.
