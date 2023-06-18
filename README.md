# OPT ESLint Configuration

## Getting Started

1. Install the dependencies

```batch
npm i -D eslint @opt/opt-eslint-config
REM or
yarn add -D eslint @opt/opt-eslint-config
```

2. Create a `.eslintrc.json` file extending the config:

> react

```json
{
  "extends": "@opt/opt-eslint-config/react"
}
```

> node

```json
{
  "extends": "@opt/opt-eslint-config/node"
}
```