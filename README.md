# boilerplate-babel-webpack

[![npm version](https://badge.fury.io/js/boilerplate-babel-webpack.svg)](https://badge.fury.io/js/boilerplate-babel-webpack)
[![downloads count](https://img.shields.io/npm/dt/boilerplate-babel-webpack.svg)](https://www.npmjs.com/~piecioshka)
[![dependencies](https://david-dm.org/piecioshka/boilerplate-babel-webpack.svg)](https://github.com/piecioshka/boilerplate-babel-webpack)

:fork_and_knife: Starter with Babel.js and Webpack

## Features

* :white_check_mark: Webpack v4.29.6
* :white_check_mark: Babel v7.3.4
* :white_check_mark: Support syntax ES2015 & ES2016 & ES2017 & ES2018
* :white_check_mark: Static directory: `public/`
* :white_check_mark: Source Map of bundle file.
* :white_check_mark: Analysis of bundle file weight.

## Getting started

You can start in two ways:

### Use Git

```bash
mkdir PROJECT_NAME
cd $_     # Note: "$_" is last argument of previous command
git init  # Note: branch "master" is created
git remote add boilerplate git@github.com:piecioshka/boilerplate-babel-webpack.git
git pull boilerplate master
git remote remove boilerplate
```

or ...

### Use Zip

1. Download package file:<br/>
https://github.com/piecioshka/boilerplate-babel-webpack/archive/master.zip
2. Extract it to your project directory.

## How to build the application?

```bash
npm install
npm run build
# Open public/ directory in browser
```

Your source will be minified.

## How to develop the application?

```bash
npm install
npm run watch
# Open public/ directory in browser
```

## Remove generated directory

If you would like to remove `public/dist` directory (created by Webpack):

```bash
npm run clear
```

If you would like to remove `node_modules/` and remove `public/dist/`

```bash
npm run clear:all
```

## Count LOC (Lines of Code)

If you would like to know how many lines of code you write:

```bash
npm run count
```

## Analysis of bundle file weight

If you would like to check how much a bundle file weight:

```bash
npm run audit
```

## License

[The MIT License](http://piecioshka.mit-license.org) @ 2017
