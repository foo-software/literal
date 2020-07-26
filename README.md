> <img src="https://literaljs.s3.amazonaws.com/literal-logo.png" width="60" height="60" align="left" /> A full stack JavaScript library for creating component based websites. In the growing, complex ecosystem of web development Literal draws inspiration from popular modern JavaScript libraries but aims to prioritize interface simplicity, standardization, performance, and user experience.

**Important**: This project is under development and hasn't been released.

# Literal

While popular JavaScript libraries like React have revolutionized software engineering, some of their core characteristics impose inherent challenges to end users. The level of challenges these libraries impose can become blockers in creating web applications fit for today's standards. Literal takes alternative approaches to prioritize ease of development and optimal user experience.

Below are the main incentives of Literal.

- **To help engineers create performant websites that rank well in search engines**. [Google will prioritize page experience](https://webmasters.googleblog.com/2020/05/evaluating-page-experience.html) in its search algorithm. Literal focuses on performance first by utilizing tools like [Lighthouse](https://developers.google.com/web/tools/lighthouse) and [Web Vitals](https://github.com/GoogleChrome/web-vitals) to ensure performance optimization.
- **To provide an easy to learn API**. Literal is easy to learn and teach for engineers of all levels.
- **To provide a simple path for migration**. Literal draws inpiration from popular modern JavaScript libraries to provides similar tools, APIs and effectively a straightforward path for migration.

## RFCs

Coming soon...

# Comparison

How Literal differs from popular JavaScript libraries:

- **A "literal" DOM** (server-side rendering by default): The concept of a "virtual DOM" has been all the hype with its slick assumed component based API and efficient data binding. Libraries like React and Vue don't support server-side rendering out of the box. Users who are concerned about SEO, for example, typically establish server-side rendering by utilizing frameworks like Next.js on top of React, but by doing so have to manage another dependency and its versions. Server-side rendering in React also yields the challenge of maintaining parity between server-side and client-side rendering. Long running client-side hydration can cause a bad experience and degrade performance. The cost of virtual DOM [reconcilliation](https://reactjs.org/docs/reconciliation.html) is not worth the value. Literal provides the good things about a virtual DOM with a declarative component-based interface, but without the over-engineering and coins the term "literal DOM". Literal provides server-side rendering by default.
- **Opinionated**: While some JavaScript libraries like React highlight an unopinionated, flexible characteristic - Literal focuses on establishing an opinionated, **standardized** framework. React requires the end user to "shop" for solutions that can lead to a "dependency hell" in which a variety of dependencies and versions of dependencies conflict. *State management* is a good example that can cause this situation. To handle global state React engineers need to choose between the core Context API, or Redux, Sagas, RxJS, etc, etc. Many of these libraries add significant bytes to parsed JavaScript which degrade website performance dramatically. Not only do these dependencies add bytes to parse by the browser but also a variety of complexities in testing and integration. By establishing a standardized open-source library, solutions like state management are developed and contributed to in its core and mature over time.
- **Simple, stable APIs**: Between its component lifecycle (with methods like `componentDidMount`, `getDerivedStateFromProps` and legacy methods like `UNSAFE_componentWillMount`), hooks API and more, React is difficult to understand and learn. At the time of this writing users can choose to implement components with a class-based structure or functional. Depending on the choice of component structure, local state is either managed with [hooks](https://reactjs.org/docs/hooks-reference.html) or by the component class method `setState`. Functional components with hooks state management seem to be the recommended approach, however the ["rules of hooks"](https://reactjs.org/docs/hooks-rules.html) and API itself are not intuitive. Literal aims to take a simpler, standard approach in its APIs so that engineers can grow with the library. Literal is easy to teach and learn.

How Literal is similar to popular JavaScript libraries:

Coming soon...

# Road Map

Coming soon...
