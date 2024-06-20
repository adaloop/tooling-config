# @tbrul/tsconfig

The `@tbrul/tsconfig` package exports the base TypeScript configuration for tbrul packages.

## Installation

Install the package as a development dependency from the npm packages registry.

```bash
npm i -D @tbrul/tsconfig

yarn add -D @tbrul/tsconfig

pnpm add -D @tbrul/tsconfig
```

## Usage

You must extend your `tsconfig.json` from the `tsconfig.package.json`.

```json
{
  "extends": "@tbrul/tsconfig/tsconfig.package.json",
  "compilerOptions": {
    "rootDir": "./",
    "outDir": "./build"
  }
}
```
