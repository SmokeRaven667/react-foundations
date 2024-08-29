# What Is This?

`react-foundations` is my follow-along code for the nextjs tutorial titled, coindicentally, `react-foundations`

check it out:
https://nextjs.org/learn/react-foundations

the `react-foundations` tutorial is meant to precede the `dashboard-app` tutorial proper, which is here for reference:
https://nextjs.org/learn/dashboard-app

# Takeaways

1. `Imperative` is step-by-step instructions, and `Declarative` is giving end result without concern for steps. ("knead dough, add ingredients, put in oven" versus "pepperoni pizza please")
1. React is a declarative UI library.
1. `JSX` is syntax extension for JavaScript allowing HTML-like syntax. Has to be transpiled by something like `Babel`.
1. `Component` is a function that returns UI elements.
1. React components should be \*_capitalized_ to distinguish them from HTML and JavaScript.
1. Use `object destructuring` to get values from `props`.
   - destructuring is syntax for unpacking values from arrays or properties from objects into distinct variables.
1. JavaScript variable inside `JSX` can be accessed by wrapping variable in brackets (i.e. `{value}`).
1. `props` are used to pass information to `components`.
1. Interactivity with component is acheived via `state` and `event handlers`.
1. In React, event handlers are `camelCased`.
1. the React hook used to manage state is `useState()`.
1. common to use `set<Variable>` as second, update, parameter in hook.
1. logic for updating state should be kept within the component where state was initially created.
1. `Props` are read-only information passed to `components` and `State` is information that can change over time, usually triggered by a user interaction.
1. get ready for Next by adding package.json with `{}` then `npm install react@latest react-dom@latest next@latest`
1. Nextjs uses file-system routing.
1. Nextjs uses `React Server Components` and they do not support `useState` so must use `Client Component` instead.
1. After server components are rendered, special data format is sent to client: `React Server Component Payload (RSC)`; it contains rendered result of server components and placeholders where client components shoudl be rendered with references to their JavaScript files.

# Some MS Code Extensions

Some MS Code extensions recommended in this decent Medium article:
https://medium.com/@fariqmh95/10-extensions-in-vs-code-that-you-must-install-for-react-71a7bfa7adde

1. ESLint: This extension integrates ESLint, a popular JavaScript linter, into VS Code. It helps you maintain a consistent coding style and catch common mistakes.

1. Prettier — Code Formatter: Prettier is a code formatter that automatically formats your code according to a predefined style guide. This extension ensures that your React code is consistently formatted.

1. Simple React Snippets: This extension provides a collection of React code snippets that can save you time by generating common React component code and patterns.

1. React Native Tools: If you’re working with React Native, this extension provides tools and debugging support specifically tailored to React Native development.

1. Auto Import: Auto Import automatically adds import statements when you reference a component or module in your code, making it easier to manage imports in your React application.

1. Path Intellisense: This extension helps you import modules and components with ease by providing autocomplete suggestions for file paths.

1. File Utils : A convenient way of creating, duplicating, moving, renaming, deleting files and directories.

1. Bracket Pair Colorization : This extension colorizes matching brackets and parentheses in your code, making it easier to navigate and identify code blocks in your React components.

1. Vscode-styled-components: If you’re using styled-components for styling in your React application, this extension provides syntax highlighting and IntelliSense support for styled-components.

1. GitLens: While not specific to React, GitLens is a powerful Git extension that provides insights into your code’s history and allows you to navigate and explore Git repositories directly within VS Code. Useful for collaborative React projects.
