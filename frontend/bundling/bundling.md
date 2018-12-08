# Bundling

## General

Bundling allows us to load one [JavaScript](../javascript/javascript.md) file in to another [JavaScript](../javascript/javascript.md) file so we can separate code in to different files.

Bundling is standard practice for most large projects today and the idea is that instead of loading multiple [JavaScript](../javascript/javascript.md) files or concatenating script files together in order to create a single large file we use tools to do this for us.

The benefit of this is that we can write large [JavaScript](../javascript/javascript.md) applications without having to keep all the code in one file or manually tracking what code needs to be loaded before other code.

## CommonJS

CommonJS is at the time of writing this document the most common way of loading one [JavaScript](../javascript/javascript.md) file in to another [JavaScript](../javascript/javascript.md) file.

You can read more about CommonJS [here](http://www.commonjs.org/).

## Asynchronous Module Definition (AMD)

AMD is another common module loading system and you should be aware of it even if it is less common in the industry at the time of writing this document.

You can read more about AMD [here](https://en.wikipedia.org/wiki/Asynchronous_module_definition).

## Webpack

Webpack is a bundling tool that allows you to build large scale [JavaScript](../javascript/javascript.md) applications and it is at the time of writing this document the best supported and most widely used bundling tool in the industry.

You can read more about Webpack [here](https://webpack.js.org/).

## Common Webpack loaders

* [Style loader](https://github.com/webpack-contrib/style-loader)
* [Css loader](https://github.com/webpack-contrib/css-loader)
* [Sass loader](https://github.com/webpack-contrib/sass-loader)
* [Postcss loader](https://github.com/postcss/postcss-loader)
* [Babel loader](https://github.com/babel/babel-loader)

## Common Webpack plugins

* [HtmlWebpackPlugin](https://webpack.js.org/plugins/html-webpack-plugin/)

## Common Webpack additions

* [Hot module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)

**[back](../../README.md)**
