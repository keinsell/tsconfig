# tsconfig

[TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```sh
npm install --save-dev @keinsell/tsconfig
```

*This config requires TypeScript 5 or later.*

## Usage

`tsconfig.json`

```json
{
	"extends": "@keinsell/tsconfig",
	"compilerOptions": {
		"outDir": "dist"
	}
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "@keinsell/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2023"
	}
}
```
