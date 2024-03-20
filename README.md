## Puz Parser

Just a simple .puz parser.

## Install

```sh
npm install @djuta/puz --save
```

## Usage

```js
const parse = require('@djuta/puz');
// Or
import parse from '@djuta/puz';

// Load a .puz file
const data = new Uint8Array(buffer);

// Parse the Uint8Array data
const puz = parse(data);
```

## Types

Types are available in [src/types.ts](src/types.ts).
