# @tbrul/prettier-config

The `@tbrul/prettier-config` package exports the base Prettier configuration for tbrul packages.

## Installation

Install the package as a development dependency from the npm packages registry.

```bash
npm i -D @tbrul/prettier-config

yarn add -D @tbrul/prettier-config

pnpm add -D @tbrul/prettier-config
```

## Usage

To enable these rules, add a `prettier` property in your `package.json` and reference this shared config as follows:

```json
{
  "prettier": "@tbrul/prettier-config"
}
```
