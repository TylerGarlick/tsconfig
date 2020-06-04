# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

Install the package using your favorite package manager

**Yarn**

```bash
$ yarn add @tylergarlick/tsconfig --dev
```

**NPM**

```bash
$ npm i @tylergarlick/tsconfig --only-dev
```

## Usage

`tsconfig.json`

```json
{
	"extends": "@tylergarlick/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "es2018",
		"lib": [
			"es2018"
		]
	}
}
```

## License

MIT © Tyler Garlick
