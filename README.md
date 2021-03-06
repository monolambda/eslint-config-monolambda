# eslint-config
[![npm version](https://img.shields.io/npm/v/@monolambda/eslint-config.svg)](https://www.npmjs.com/package/@monolambda/eslint-config)
[![Travis branch](https://img.shields.io/travis/monolambda/eslint-config/master.svg)](https://travis-ci.org/monolambda/eslint-config)
[![npm](https://img.shields.io/npm/dt/@monolambda/eslint-config.svg)](https://www.npmjs.com/package/@monolambda/eslint-config)

## Rules>

#### Rule set based on:
- ESLint Recommended
- [JavaScript Standard Style](https://github.com/feross/standard)
- [JavaScript Standard React](https://github.com/feross/eslint-config-standard-react)

#### Included Plugins
- `eslint-plugin-jest`

#### Opinions:
- Uses `babel-eslint` parser by default.
- Uses `4, spaces` for easier readability.
- Keeps most of the rules recommended rules.

**Note:** The current ruleset is subject to change and under review, please feel free to send a PR for rules you feel that are over the top.

## Installation:
```sh
npm install @monolambda/eslint-config eslint --save
``` 
## Usage
In `.eslintrc`:

```json
{
    "extends": "@monolambda/eslint-config"
}
```
