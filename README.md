# REACT TUTORIAL
## My remarks


***
### Creating a Single Page Application

```
npm install -g create-react-app
create-react-app hello-world
cd hello-world
npm start
```
_Create React App doesn't handle backend logic or databases; it just creates a frontend build pipeline, so you can use it with any backend you want. It uses Webpack, Babel and ESLint under the hood, but configures them for you._

We recommend using React from npm with a bundler like [Browserify](http://browserify.org/) or [webpack](https://webpack.github.io/).

If you use npm for client package management, you can install React with:
`npm install --save react react-dom`

and import it from your code with something like:
```jsx
import React from 'react';
import ReactDOM from 'react-dom';

ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);
```

### Enabling ES6 and JSX

The [Babel](https://babeljs.io/docs/setup/) setup instructions explain how to configure Babel in many different build environments.

_Make sure you install_ `babel-preset-react` _and_ `babel-preset-es2015` _and enable them in your_ **.babelrc,** _and you're good to go._

### Using a CDN

```
<script src="https://unpkg.com/react@15/dist/react.js"></script>
<script src="https://unpkg.com/react-dom@15/dist/react-dom.js"></script>
```

_To load a specific version of_ `react` _and_ `react-dom`, _replace 15 with the version number._


### A Note on JavaScript

_We also use some of the ES6 syntax in the examples. We try to use it sparingly because it's still relatively new, but we encourage you to get familiar with_ `arrow functions`, `classes`, `template literals`, `let`, _and_ `const` _statements. You can use Babel REPL to check what ES6 code compiles to._
