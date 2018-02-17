# babel-preset-flow-node

This is preset containing all the flow babel plugins / presets to produce output compatible with latest [nodejs].

> Babel preset for flow code targeting nodejs.

This preset includes the following plugins & presets:

* [preset-flow-syntax][]
* [plugin-add-module-exports][]

## Installation

```sh
npm install --save-dev babel-preset-flow-node
```

## Usage

### Via `.babelrc` (Recommended)

**`.babelrc`**

```json
{
  "presets": ["flow-node"]
}
```

### Via CLI

```sh
babel --presets flow-node script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["flow-node"]
})
```

[nodejs]: https://nodejs.org/en/
[preset-flow-syntax]: https://github.com/Gozala/babel-preset-flow-syntax
[plugin-add-module-exports]: https://github.com/59naga/babel-plugin-add-module-exports
