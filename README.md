# webapp


## Getting Started

- Install dependencies: `npm install --global yo gulp bower`
- Install the generator: `npm install --global generator-gulp-webapp`

- Git Clone this repo `git clone https://github.com/mkoller/webapp.git `
- cd into this repo
- run `npm install`
- run `bower install`

App should now be built out

- Run `gulp serve` to preview and watch for changes
- Run `bower install --save <package>` to install frontend dependencies
- Run `gulp serve:test` to run the tests in the browser
- Run `gulp` to build your webapp for production
- Run `gulp serve:dist` to preview the production build


## Features

* CSS Autoprefixing
* Built-in preview server with BrowserSync
* Automagically compile Sass with [libsass](http://libsass.org)
* Automagically lint your scripts
* Map compiled CSS to source stylesheets with source maps
* Awesome image optimization
* Automagically wire-up dependencies installed with [Bower](http://bower.io)
* The gulpfile makes use of [ES2015 features](https://babeljs.io/docs/learn-es2015/) by using [Babel](https://babeljs.io)

![Image of Calvin and Hobbes](http://i.imgur.com/5gAr7fy.jpg)