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

## Build

Build the bundle
```bash
webpack ./entry.js bundle.js --module-bind 'css=style!css'
```