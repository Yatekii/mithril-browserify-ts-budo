# Mithril / Babel / Browserify / HMR / Budō

This is a starter project for [Mithril](https://mithril.js.org/), Babel, Browserify with hot-module-replacement and [Budō](https://github.com/mattdesl/budo) local dev server for hot CSS reloading.

This project also uses PostCSS for CSS compilation.

This repo also contains a branch that performs code-splitting (separating your app and vendor bundles.)

	git checkout code-split

## Install

	npm install

## Run & Develop

	npm start

Then go to http://localhost:3000 in your browser

## Build Minified

	npm run build

Outputs compiled JS to `public/js` and CSS to `public/css`.
