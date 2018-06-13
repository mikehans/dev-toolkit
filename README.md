Adding a bundler
* Webpack - out of date content
* Others (Not used)
	* Rollup
	* Browserify
	* JSPM

Adding webpack-dev-middleware to devServer.js

Sourcemaps
* allows debugging compiled into original source
* only get downloaded when dev tools are opened
* sourcemaps created thru webpack.config.js

ESLint watching
* webpack eslint-loader
* eslint-watch
    * ESLint wrapper that adds file watching
    * not tied to webpack
    * message enhancements
        * displays clean message
    * can lint ALL JS files (inc. build and test scripts)
* why do it via auto build process?
    * all get the same configuration
    * not tied to editor
    * part of CI process
