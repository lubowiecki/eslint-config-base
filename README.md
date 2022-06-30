# @lubowiecki/eslint-config-base

## Install

```
npm install -D @lubowiecki/eslint-config-base
```

### Angular

```
ng add @angular-eslint/schematics
```

## Config

.eslintrc.json

```
{
	"extends": [
		"@lubowiecki/base"
	]
}
```

## VS Code settings.json

```
{
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "[typescript]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "eslint.format.enable": true
}
```
