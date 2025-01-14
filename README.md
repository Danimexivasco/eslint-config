# @danimexivasco/eslint-config

![npm](https://img.shields.io/npm/v/@danimexivasco/eslint-config) ![license](https://img.shields.io/npm/l/@danimexivasco/eslint-config) ![downloads](https://img.shields.io/npm/dw/@danimexivasco/eslint-config)

This is my personal flat **ESLint** configuration for **JavaScript**, **TypeScript** and **React** projects, with focus on code style. This package simplifies maintaining consistent coding standards across multiple projects.

## Installation

To install this ESLint configuration in your project:

With **pnpm**:
```bash
pnpm add @danimexivasco/eslint-config -D
```

With **npm**:
```bash
npm install @danimexivasco/eslint-config --save-dev
```

With **yarn**:

```bash
yarn add @danimexivasco/eslint-config -D
```

## Usage

To use a shareable config, import the package inside of an ``eslint.config.mjs`` file and add it into the exported array, like this:

```js
// eslint.config.js
import eslintConfig from "@danimexivasco/eslint-config";

export default [
    ...eslintConfig
];
```
> [!WARNING]
> **If you are using v1.0.12 or above:** please use eslint flat config.