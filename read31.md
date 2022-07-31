> # Context API

> ## Context API

> ### 1.  What can React Context provide your app?

React Context provides a way to share data to many components at once without having to specifically link them together -- like with props.

> ### 2.  Why might we use Context?

For data/functionality that is considered "global" to an app, such as a theme, preferences, current user identification, etc.

> ### 3.  Why should we use it sparingly?

Context makes it harder to reuse components, so in order to keep things reusable and modularized, Context use should be limited.

> ## Awesome React Context links

- [What’s new in React 16.3](https://medium.com/@baphemot/whats-new-in-react-16-3-d2c9b7b6193b) by Bartosz Szczeciński
  - React Context wasn't widely used when it was first introduced, out of fear that it could later change and should be avoided until it was hashed out further. Even with new features and functionality in popular tools, there can be grey area about what to adopt and when.

- [React's new context API: toggle between local and global state](https://www.freecodecamp.org/news/reacts-new-context-api-how-to-toggle-between-local-and-global-state-c6ace81443d0) by Diego Haz
  - In this article, Diego talked about how React Context provides a different approach to state, and a tool he wrote called [constate](https://github.com/diegohaz/constate). Diego said that many developers over-optimize (or unnnecessarily optimize) their apps. This is an idea I've come across before, that time and resources are spent gathering and building things that ultimately aren't utilized. Constate is an attempt to tamp down some of that over-optimization by allowing easier transitions between local state (non-Context) and global state (Context).