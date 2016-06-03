# webpack

## Prerequisites

Install webpack
```bash
npm install webpack -g
```

Then install node packages
```bash
npm install
```

Read the [documentation](http://webpack.github.io/docs/).

## Build

Build the bundle
```bash
webpack --progress --colors
```

### Watch Mode

```bash
webpack --progress --colors --watch
```

## Development Server

Install the webpack development server
```bash
npm install webpack-dev-server -g
```

Then run the development server
```bash
webpack-dev-server --progress --colors
```

Then view the page from your browser
```bash
open http://localhost:8080/webpack-dev-server/
```