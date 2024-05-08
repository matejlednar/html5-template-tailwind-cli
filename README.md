# HTML 5 template + Tailwind CSS (CLI)

## File structure

- src/css/main.css - place your CSS here,
- src/css/tailwind.css - place tailwind functions, directives, etc. here,
- src/css/styles.css - auto-generated CSS by watch script (don't edit),
- src/js/script.js - place your JavaScript here,
- src/index.html - place your HTML here,

## Prerequisites

- Node.js
- npm

## Installation

```npm install```

## Development

### Watch CSS changes in CSS files

Auto-generated styles.css file for development (src/css/styles.css). Don't edit src/css/styles.css. Use main.css for styling.

``` npm run css-watch ```

## Build

### Create the CSS output file

 Auto-generated styles.css file for production (dist/css/styles.css)

``` npm run css-build ```

## Configuration

### npm 

Edit package.json file.

Change the entry point here.

``` "main": "src/js/script.js",```
