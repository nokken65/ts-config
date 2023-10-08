# `@nokken65/ts-config`

> Here is my personal [TypeScript](https://www.typescriptlang.org/) config.

## Install

```sh
npm install @nokken65/ts-config -D
```

```sh
yarn add @nokken65/ts-config -D
```

```sh
pnpm add @nokken65/ts-config -D
```

## Usage

React config

```js
// tsconfig.json
{
  "extends": "@nokken65/tsconfig/react",
  "include": [
    "src"
  ],
  "exclude": [
    "node_modules"
  ]
}
```

Vite config

```js
// tsconfig.node.json
{
  "extends": "@nokken65/tsconfig/vite",
  "include": [
    "vite.config.ts"
  ],
  "exclude": [
    "node_modules"
  ]
}
```

Base config

```js
// tsconfig.json
{
  "extends": "@nokken65/tsconfig",
  "compilerOptions": {
    "target": "ESNext",
    "lib": ["DOM", "DOM.Iterable", "ESNext"],
    "jsx": "react-jsx"
  }
  "include": [
    "src"
  ],
  "exclude": [
    "node_modules"
  ]
}
```
