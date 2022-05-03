# Quick Client Using Webpack Dev Server

Minimalist development server that provides live reloading.
For cloning when I want to try some quick prototyping in JS and don't want to remember how to configure webpack.

## Run

`yarn run serve`

## Webpack

`webpack.config.js` takes entry where js is written and builds to the `dist` directory.

Webpack dev server runs from the `dist` directory on port 3000

## HTML

The `index.html` file is hard-coded in the `dist` directory. It can be built from the [html-webpack-plugin](https://medium.com/a-beginners-guide-for-webpack-2/index-html-using-html-webpack-plugin-85eabdb73474) which might be useful to not keep using the cached HTML file in the browser if it is going to change often in development. Not needed for the purposes of a quick prototype, but seemed cool when I was looking around so wanted to make note of it here.
