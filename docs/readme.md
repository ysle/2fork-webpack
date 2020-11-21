A minimalistic Webpack 5 based project template repository.

Uses the `./docs` folder as an output, so the results are [GitHub Pages](https://pages.github.com) friendly by default.
It's an ideal starter for quick prototyping, but needs additional configuration for production ready usage.

includes :

-   [Webpack 5](https://webpack.js.org/blog/2020-10-10-webpack-5-release/)
-   [Prettier](https://prettier.io/) code formatter, with a basic config in the package.json

scripts :

-   `npm start` : for development, webpack-dev-server with livereload.
-   `npm run build` : builds a prod bundle
-   `npm run lint` : check formatting

also provides the `preversion`, `version` and `postvesion` [npm-version](https://docs.npmjs.com/cli/v6/commands/npm-version) scripts for the automated build and deployment.

example result via GitHub Page assigned to the `./docs` folder of this repo : https://ysle.com/2fork-webpack