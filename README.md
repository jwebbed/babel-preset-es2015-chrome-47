# babel-preset-es2015

> Babel preset for all es2015 plugins.

## Install

```sh
$ npm install --save-dev jwebbed/babel-preset-es2015-chrome-47 babel-plugin-transform-es2015-parameters babel-plugin-transform-es2015-unicode-regex babel-plugin-transform-es2015-sticky-regex babel-plugin-transform-es2015-block-scoping babel-plugin-transform-es2015-classes babel-plugin-transform-es2015-object-super --save
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015"]
});
```
