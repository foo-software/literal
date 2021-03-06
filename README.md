<img src="https://literaljs.s3.amazonaws.com/literal-logo.png?v7" width="60" height="60" align="left" /> A full stack JavaScript library for creating component based websites. In the growing, complex ecosystem of web development Literal draws inspiration from popular modern JavaScript libraries but aims to prioritize interface simplicity, standardization, performance, and user experience.

**Important**: This project is under development and hasn't been released.

## Call for Contributions 📞

We'd love to have you onboard! Check the [road map section](#road-map) for details.

# Literal

While popular JavaScript libraries like React have revolutionized software engineering, some of their core characteristics impose inherent challenges to end users. The level of challenges these libraries impose can become blockers in creating web applications fit for today's standards. Literal takes alternative approaches to prioritize ease of development and optimal user experience.

Below are the main incentives of Literal.

- **To help engineers create performant websites that rank well in search engines**. [Google will prioritize page experience](https://webmasters.googleblog.com/2020/05/evaluating-page-experience.html) in its search algorithm. Literal focuses on performance first by utilizing tools like [Lighthouse](https://developers.google.com/web/tools/lighthouse) and [Web Vitals](https://github.com/GoogleChrome/web-vitals) to ensure performance optimization.
- **To provide an easy to learn API**. Literal is easy to learn and teach for engineers of all levels.
- **To provide a simple path for migration**. Literal draws inpiration from popular modern JavaScript libraries to provides similar tools, APIs and effectively a straightforward path for migration.

## RFCs

- [RFC: Literal](https://github.com/foo-software/literal-rfcs/blob/master/text/0001-literal.md)

# Comparison

- [How does Literal differ from other JavaScript libraries?](https://github.com/foo-software/literal-rfcs/blob/master/text/0001-literal.md#differences-from-popular-frameworks)
- [How is Literal similar to other JavaScript libraries?](https://github.com/foo-software/literal-rfcs/blob/master/text/0001-literal.md#similarities-to-popular-frameworks)

# Road Map

Each item on the road map is loosely described in our [main RFC](https://github.com/foo-software/literal-rfcs/blob/master/text/0001-literal.md#detailed-design). Any item on the list below without an "accepted RFC" is up for grabs. If you have an idea that differs from an in-progress RFC, feel free to propose your own - otherwise we'd encourage commenting on the existing one. To submit an RFC for any of the items below without one, follow the [process documented here][1]. See the [contributing section](#contributing) for more details.

|   | Name | Description | Status | Accepted RFC | Assignee | Dependency |
|---|------|-------------|--------|--------------| ---------| ---------- |
| 1 | Documentation server | [see main RFC][2] | to-do | -- | -- | -- |
| 2 | State management | [see main RFC][2] | to-do | -- | -- | `1` |
| 3 | Build Tooling Boilerplate | Establish a basic setup needed for `4` and `5` | to-do | -- | -- | `1` |
| 4 | JSX-like API (and tooling?) | This will be the largest part of the work. We'll need to establish syntax, data / event binding, transpiling tools to output server and client assets. [See main RFC][2] | to-do | -- | -- | `1` - `3` |
| 5 | Styling (and tooling?) | Should accommodate [Bootstrap][3] - [see main RFC][2] | to-do | -- | -- | `1` - `4` |
| 6 | Server Support | [see main RFC][2] | to-do | -- | -- | `1` - `5` |
| 7 | Build Tooling Final | Finalize build tooling - [see main RFC][2]| to-do | -- | -- | `1` - `6` |
| 8 | Unit Testing Framework | [see main RFC][2] | to-do | -- | -- | `1` - `7` |
| 9 | Examples | POC should use [Bootstrap][3] for styling - [see main RFC][2] | to-do | -- | -- | `1` - `8` |

[1]: https://github.com/foo-software/literal-rfcs
[2]: https://github.com/foo-software/literal-rfcs/blob/master/text/0001-literal.md#detailed-design
[3]: https://getbootstrap.com/

# Contributing

As a new project our contributing conventions are still being established. Below is a list of steps.

1. Create an [RFC](https://github.com/foo-software/literal-rfcs) or [issue](https://github.com/foo-software/literal/issues) to gather feedback. Establish an order of operation to achieve the proposed work. If the effort requires more than you can contribute, no problem - just simply list all the parts and identify the parts you'll be working on.
2. Once you've gathered enough feedback from an RFC or issue, create a fork, make the changes and open a PR. Make sure to reference any related RFCs or issues in your PR.
3. Wait ⌛... a core contributor will review your code soon after opening a PR.
4. 🚀
