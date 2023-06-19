# OPT ESLint Configuration

## Getting Started

1. Install the dependencies

```batch
npm i -D eslint @diegogeodev/opt-eslint-config
REM or
yarn add -D eslint @diegogeodev/opt-eslint-config
```

2. Create a `.eslintrc.json` file extending the config:

> react

```json
{
  "extends": "@diegogeodev/opt-eslint-config/react"
}
```

> node

```json
{
  "extends": "@diegogeodev/opt-eslint-config/node"
}
```