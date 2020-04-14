# material-colors-ts

[![NPM version](https://img.shields.io/npm/v/material-colors-ts.svg)](https://www.npmjs.com/package/material-colors-ts)

A zero dependency TypeScript export of the material design color system.

## Install
```bash
$ npm install material-colors-ts
```

## Usage
### NodeJS or Browser
```js
import { white, blue } from 'material-colors-ts';

export function getBackgroundColor() {
  return blue[100];
}
```

### React
```tsx
import React from 'react';
import { white, blue } from 'material-colors-ts';

export default function Example() {
  return (
    <div style={{ backgroundColor: white }}>
      <span style={{ color: blue[500] }}>
        This is some blue text
      </span>
    </div>
  )
}

```

