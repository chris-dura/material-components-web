# Material Design Style Guide

A library offering Material Design components in CSS, JS and HTML.

## Getting Started

### Clone / download

Clone or [download](https://github.com/google/material-styleguide/archive/master.zip) this repository
and reference the following files in your project:

```html
<script src="js/material.min.js">
<link rel="stylesheet" href="css/material.min.css">
```

You will want to include the entire package to ensure optional assets like images or fonts are correctly
included.

### Bower

```sh
$ bower install material-styleguide
```

### npm

```sh
$ npm install material-styleguide
```

## Development

The sources (JS, Sass) and demo files for all components can be found in the `src` directory. To get started
modifying them, first install the necessary dependencies, from the root of the project:

```sh
$ npm install && npm install -g gulp
```

Next, run the following one-liner to preview the components:

```sh
$ gulp serve
```

Any changes made to files inside the `src` directory will cause the page to reload. This page can also be loaded
up on physical devices thanks to BrowserSync.

To build a production version of the components, run:

```sh
$ gulp
```

This will clean and update the `css`, `js` and `images` directories in the root of the project with minified and
concatenated versions of the component files. Namely, `css/material.min.css` and `js/material.min.js`.

## License

Copyright Google, 2015. Licensed under an Apache-2 license.