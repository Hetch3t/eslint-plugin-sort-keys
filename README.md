[![npm][npm-image]][serenity-url]
[![downloads][downloads-image]][serenity-url]
[![serenity][serenity-image]][serenity-url]

[npm-image]: https://img.shields.io/npm/v/@hetchet/eslint-plugin-sort-keys.svg?style=flat
[downloads-image]: https://img.shields.io/npm/dm/@hetchet/eslint-plugin-sort-keys.svg?style=flat
[serenity-image]: https://img.shields.io/badge/code%20style-%F0%9F%AA%B7%20serenity-4AD3BA?style=flat
[serenity-url]: https://npmjs.org/package/@hetchet/eslint-config-serenity

## Description

Standard ESLint `sort-keys` rule doesn't allow sorting fields and there is no plan to implement it. However, personally I would find a lot of usages for such functionality, so I added fixing logic to default ESLint rule.

## Installation

1. Install ESLint:
   npm: `npm i eslint --save-dev`
   yarn: `yarn add -D eslint`

2. Install plugin:
   npm: `npm i @hetchet/eslint-plugin-sort-keys --save-dev`
   yarn: `yarn add -D @hetchet/eslint-plugin-sort-keys`

3. Add to your ESLint config:

```jsonc
{
	// ...
	"plugins": ["@hetchet/sort-keys"],
	"rules": {
		"@hetchet/sort-keys/sort-keys": "error"
	}
	// ...
}
```

## Options
Plugin supports same options as 
[original ESLint `sort-keys` rule](https://eslint.org/docs/latest/rules/sort-keys).

-----

### ❗️ Use this plugin at your own risk