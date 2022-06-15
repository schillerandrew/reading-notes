> # Express, NPM, TDD, CI/CD

The current class module is focusing heavily on server-side development in Express, using NPM to set up servers and dependencies, test-driven development (TDD) to drive coding, and continous integration and deployment (CI/CD) to deploy to the cloud -- this reading is going over critical concepts and information.

> ## Express

1. Explain middleware, answer as though I were a non-technical recruiter.

- Software that runs in between software layers -- in "the middle".

1. Express is the most popular: *Node web framework*.

1. Express is “unopinionated.” What does that mean?

- It means that development within Express is more open-ended. It's more flexible and has a wider range of application.

1. What is a module and why is modularity useful to us as developers?

- A module is any JavaScript file or library -- they are commonly imported into other files/modules.

> ## NPM

1. What version of npm are you running on your machine?

- 8.7.0

1. What command would you type to install a library/package called ‘jshint’ into your node project?

- `npm i jshint`

> ## TDD

1. Explain why tests are important. Please explain as though I were your non technical elder.

- Testing promotes good development practices: breaking problems down into smaller pieces, looking at things from different angles (big picture and small), and a more 'modularized' approach.

1. What are three expected benefits of testing?

- They tend to be very useful at avoiding problems in your code, while not requiring a significant amount of time.
- Testing tends to get a project finished faster, at the cost of more upfront time but with more time saved towards the end.
- Testing can lead to higher quality code.

1. Name at least 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

- individual pitfalls: writing too many tests at once or writing tests that are too large
- team pitfalls: only part of the team uses TDD, or the test suite is not maintained

> ## CI / CD

1. What are three benefits of Continuous Integration?

- Better integration of everyone's changes, bug catching, reducing merge conflicts

1. What is the difference between Continuous Delivery and Continuous Deployment?

- Continuous delivery means software can be released at any time. Continous deployment is part of continuous delivery, and involves deploying features quickly.

1. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.

- GitHub uses all three of these things: continuous integration, delivery and deployment. And all of three of those require keeping track of old and new code. GitHub allows you to merge code together (or not) and more directly update your software.
