# Simple React Project

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)

## Getting Started

### Installation

```bash
git clone https://github.com/chlee1001/simple-react-project.git
cd simple-react-project
yarn install
```

### Development server

Webpack dev server runs at `localhost:3001`.

```bash
yarn run start
```

### Production build

Build outputs are created in `dist`.

```bash
yarn build
```

## Features

- [React](https://ko.reactjs.org/): 18.2.0
- [webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)

## Dependencies

### webpack

- [`webpack`](https://github.com/webpack/webpack) - Module and asset bundler.
- [`webpack-cli`](https://github.com/webpack/webpack-cli) - Command line interface for webpack
- [`webpack-dev-server`](https://github.com/webpack/webpack-dev-server) - Development server for webpack
- [`webpack-merge`](https://github.com/survivejs/webpack-merge) - Simplify development/production configuration

### Babel

- [`@babel/core`](https://www.npmjs.com/package/@babel/core) - Transpile ES6+ to backwards compatible JavaScript
- [`@babel/preset-env`](https://babeljs.io/docs/en/babel-preset-env) - Smart preset for Babel
- [`@babel/preset-react`](https://babeljs.io/docs/en/babel-preset-react) - Babel preset for all React plugins

#### Babel plugins
- [`@babel/plugin-proposal-class-properties`](https://babeljs.io/docs/en/babel-plugin-proposal-class-properties) - The compiler for next generation JavaScript
- [`react-refresh`](https://www.npmjs.com/package/react-refresh) - Implements the wiring necessary to integrate Fast Refresh into bundlers

### Loaders

- [`babel-loader`](https://webpack.js.org/loaders/babel-loader/) - Transpile files with Babel and webpack
- [`css-loader`](https://webpack.js.org/loaders/css-loader/) - Resolve CSS imports
- [`style-loader`](https://webpack.js.org/loaders/style-loader/) - Inject CSS into the DOM

### Plugins

- [`clean-webpack-plugin`](https://github.com/johnagan/clean-webpack-plugin) - Remove/clean build folders
- [`@pmmmwh/react-refresh-webpack-plugin`](https://github.com/pmmmwh/react-refresh-webpack-plugin) - React Refresh Webpack Plugin
- [`mini-css-extract-plugin`](https://github.com/webpack-contrib/mini-css-extract-plugin) - Extracts CSS file per JS file which contains CSS
- [`html-webpack-plugin`](https://github.com/jantimon/html-webpack-plugin) - Generate HTML files from template

### Linters

- [`eslint`](https://github.com/eslint/eslint) - Enforce styleguide across application
- [`eslint-config-airbnb`](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Base JS styleguide of Airbnb
- [`eslint-config-airbnb-base`](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base) - Base JS styleguide of Airbnb
- [`eslint-config-prettier`](https://github.com/prettier/eslint-config-prettier) - Implement prettier rules
- [`eslint-plugin-import`](https://github.com/benmosher/eslint-plugin-import) - Implement import rules
- [`eslint-plugin-jsx-a11y`](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y) - Static AST checker for accessibility rules on JSX elements
- [`eslint-plugin-prettier`](https://github.com/prettier/eslint-plugin-prettier) - Dependency for prettier usage with ESLint
- [`eslint-plugin-react`](https://github.com/jsx-eslint/eslint-plugin-react) - React specific linting rules for `ESLint`
- [`eslint-plugin-react-hooks`](https://www.npmjs.com/package/eslint-plugin-react-hooks) - This ESLint plugin enforces the Rules of Hooks
- [`prettier`](https://github.com/prettier/prettier) - code formatter

## License

This project is licensed under the [MIT License](./LICENSE).