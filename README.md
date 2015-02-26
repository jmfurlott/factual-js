# factual-js

A wrapper for the Factual API that uses Superagent.  Works with both frontend and backend JS apps.

## Installation

```
$ npm install
```

## Usage

## Development

Require the module

```
import 'Factual' from 'factual-js';
```

### Demo

When making changes to the source, you have to build the `src` folder.

```
$ npm run demo
```

After the demo is bundled, visit the `demo/index.html` in your web browser to view the changes.  This command will build the source into the `dist` folder and will also generate `demo.js` out of the the `src/factualDemo.js` file.  Since this file imports the `src/factual.js` file, it will be included as well.

## Licence

MIT
