# @yonyou-cloud/eslint-config

> eslint-config for yonyou.

## Usage

```bash
npm i eslint @yonyou-cloud/eslint-config -D
```

```js
// .eslintrc.js for js.
module.exports = {
  extends: ['@yonyou-cloud/eslint-config']
}

// .eslintrc.js for react.
module.exports = {
  extends: ['@yonyou-cloud/eslint-config/react']
}

// .eslintrc.js for vue.
module.exports = {
  extends: ['@yonyou-cloud/eslint-config/vue']
}
```

## Included

+ babel-eslint
+ eslint:recommended
+ standard
+ eslint-plugin-react
+ eslint-plugin-vue