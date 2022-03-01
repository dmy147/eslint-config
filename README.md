# @dmy/eslint-config

Project forked [![npm](https://img.shields.io/npm/v/@dmy/eslint-config)](https://npmjs.com/package/@antfu/eslint-config)

## Usage

### Install

```bash
pnpm add -D eslint @dmy/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": [
    "@dmy"
  ]
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
