# @adaloop/tsconfig

The `@adaloop/tsconfig` package exports the base TypeScript configuration for adaloop packages.

## Installation

Install the package as a development dependency from the npm packages registry.

```bash
npm i -D @adaloop/tsconfig

yarn add -D @adaloop/tsconfig

pnpm add -D @adaloop/tsconfig
```

## Usage

You must extend your `tsconfig.json` from the `tsconfig.package.json`.

```json
{
  "extends": "@adaloop/tsconfig/tsconfig.package.json",
  "compilerOptions": {
    "rootDir": "./",
    "outDir": "./build"
  }
}
```
