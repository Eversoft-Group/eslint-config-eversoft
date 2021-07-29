# eversoft/eslint-config

[![npm](https://img.shields.io/npm/v/@eversoft/eslint-config?style=flat-square)](https://badge.fury.io/js/eslint-config-leapfrog)
[![npm](https://img.shields.io/npm/dm/@eversoft/eslint-config?style=flat-square)](https://npmjs.org/package/eslint-config-leapfrog)

ESlint rules for JavaScript projects at Leapfrog.

## Requires

- ESLint **>= 6.0.0**

## Usage

Add `@eversoft/eslint-config` as a dev dependency.

```bash
yarn add @eversoft/eslint-config --dev
# or
npm install @eversoft/eslint-config --save-dev
```

Include `@eversoft/eslint-config` in your [.eslintrc](https://eslint.org/docs/user-guide/getting-started#configuration) file.

```json
{
  "extends": ["@eversoft/eslint-config"]
}
```