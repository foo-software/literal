> <img src="https://literaljs.s3.amazonaws.com/literal-logo.png" width="60" height="60" align="left" /> A full stack JavaScript library for creating component based websites. In the growing, complex ecosystem of web development Literal draws inspiration from popular modern JavaScript libraries but aims to prioritize interface simplicity, standardization, performance, and user experience.

**Important**: This project is under development and hasn't been released.

# Literal

While popular JavaScript libraries like React have revolutionized software engineering, their evolution have nurtured the growth of inherent challenges absorbed by the end user.

Below are a list of JavaScript library characteristics Literal aims to differ on compared to the mainstream.

- **A "Literal" DOM** (server-side rendering by default): The concept of a "virtual DOM" has been all the hype with its slick component based API and efficient data binding. Libraries like React and Vue don't support server-side rendering out of the box. Users who are concerned about SEO, for example, typically establish server-side rendering by utilizing frameworks like Next.js on top of React, but by doing so have to manage another dependency and its versions. Server-side rendering in React also yields the challenge of maintaining parity between server-side and client-side rendering. Long running client-side hydration can cause a bad experience and degrade performance. The cost of virtual DOM [reconcilliation](https://reactjs.org/docs/reconciliation.html) is not worth the value. Literal provides the good things about a virtual DOM with a declarative component-based interface, but without the over-engineering and coins the term "literal DOM". Literal provides server-side rendering by default.
- **Opinionated**: While some JavaScript libraries like React highlight an unopinionated, flexible stance - Literal focuses on establishing an opinionated, standardized framework. React requires the end user to "shop" for solutions that can yield to a "dependency hell" in which a variety of dependencies and versions of dependencies conflict. *State management* is a good example that can cause this situation. To handle global state React engineers need to choose between the core Context API, or Redux, Sagas, RxJS, etc, etc. Many of these libraries add significant bytes to parsed JavaScript which degrade website performance dramatically. Not only do these dependencies add bytes to parse by the browser but also a variety of complexities in testing and integration. By establishing a standardized open-source library, solutions like state management are developed in its core and mature over time.

More coming soon...
