# mdi-preact [![npm package](https://img.shields.io/npm/v/mdi-react.svg?style=flat-square)](https://npmjs.org/package/mdi-react)
[Material Design Icons](https://materialdesignicons.com) for Preact packaged as single components

Forked from [mdi-react](https://github.com/levrik/mdi-react) and updated to work with Preact.

## Installation

```bash
npm install mdi-preact
# or if you use Yarn
yarn add mdi-preact
```

*The version number of `mdi-preact` is in sync with the original font.*

## Usage

Just search for an icon on [materialdesignicons.com](https://materialdesignicons.com) and look for its name.  
The name translates to PascalCase followed by the suffix `Icon` in `mdi-preact`.

For example the icons named `alert` and `alert-circle`:

```javascript
import AlertIcon from 'mdi-preact/AlertIcon';
import AlertCircleIcon from 'mdi-preact/AlertCircleIcon';

const MyComponent = () => {
  return (
    <div>
      <AlertIcon />
      <AlertCircleIcon className="some-class" />
    </div>
  );
};
```

The icons get a class named `mdi-icon` attached for styling. You can also attach own additional classes with the `className` property.
