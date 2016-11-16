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
