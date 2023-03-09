## Getting Started

Search Demo Widget is build to test our third-party widget. The general goal of this repository is to make sure widget is creating write query on our search pages.

## How to test

1. Make the changes on search widget [repo](https://github.com/Prosple/search-widget)
2. Once done with the changes, run ``yarn build`` on your terminal
3. It will create two types of files `prosple-search.js.map` & `prosple-search.js`.
4. On this repo, create a test file for map & js minified files. Name the file `prosple-search.js-[v1-test].map` & `prosple-search-[v1-test].js`. Or name it according to what is your task or what are you currently testing.
5. Create a new html file. You can use `index.html` as based line.
6. If you're testing specific third-party widget make sure to change the ff fields:
```
$PROSPLE_SEARCH_ID =
$PROSPLE_SEARCH_NODE_TYPE =
$PROSPLE_SEARCH_ENDPOINT =
```
7. If you're gonna test just the general flow the initial format for the `index.html` will do.

## How to deploy

- Once you're done with your changes locally. Simply `git commit` your changes & `git push origin master` then merged your changes to master.
- Deployment should be automatically triggred.
- One done, you may access the deployed changes e.g `https://prosple.github.io/search-widget-demo/index.html`
