# OPT ESLint Configuration

## Getting Started

1. Install the dependencies

```batch
npm i -D eslint @diegogeodev/eslint-config
REM or
yarn add -D eslint @diegogeodev/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:

> react

```json
{
  "extends": "@diegogeodev/eslint-config/react"
}
```

> node

```json
{
  "extends": "@diegogeodev/eslint-config/node"
}
```