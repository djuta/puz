## Puz Parser

Just a simple .puz parser.

## Install

```sh
npm install puz-parser --save
```

## Usage

```js
const parse = require('puz-parser');
// Or
import parse from 'puz-parser';

// Load a .puz file
const data = new Uint8Array(buffer);

// Parse the Uint8Array data
const puz = parse(data);
```

## Types

Types are available in [src/types.ts](src/types.ts).
