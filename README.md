# @dmy147/eslint-config

Project forked [![npm](https://img.shields.io/npm/v/@antfu/eslint-config)](https://npmjs.com/package/@antfu/eslint-config)

## Usage

### Install

```bash
pnpm add -D prettier eslint @dmy147/eslint-config

# for react native
pnpm add -D prettier eslint @dmy147/eslint-config-react-native
```

### Config `.eslintrc`

```json
{
  "extends": ["@dmy147"]
}
```

### for `React Native`

```json
{
  "extends": ["@dmy147/eslint-config-react-native"]
}
```

### Config `.eslintignore`

```txt
dist
public
```

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint \"**/*.{vue,ts,js}\""
  }
}
```

### Config VSCode auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
