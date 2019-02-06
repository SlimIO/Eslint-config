# ESLint Configuration
![V2.0.3](https://img.shields.io/badge/version-2.0.3-blue.svg)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/SlimIO/Eslint-config/commit-activity)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/SlimIO/Eslint-config/blob/master/LICENSE)

SlimIO [ESLint](https://eslint.org/) configuration

## Getting Started

This package is available in the Node Package Repository and can be easily installed with [npm](https://docs.npmjs.com/getting-started/what-is-npm) or [yarn](https://yarnpkg.com).

```bash
$ npm i @slimio/eslint-config -D
# or
$ yarn add @slimio/eslint-config -D
```

## Usage example

Create an `.eslintrc` file at the root of your project with the following (JSON) content:
```json
{
    "extends": "@slimio/eslint-config"
}
```

Edit the file as you want by adding [custom rules](https://eslint.org/docs/rules/) if required !

> Dont forget to install **ESLint as a DevDependencies**: `npm i eslint -D`

## Why ?

| rule name | value | why we choose this configuration |
| --- | --- | --- |
| indent | 4 | We are considering indent `2` not enougth for code visibility/readability |
| semi | always | We are following the official TC39 ASI recommandation |
