# @adaloop/prettier-config

The `@adaloop/prettier-config` package exports the base Prettier configuration for adaloop packages.

## Installation

Install the package as a development dependency from the npm packages registry.

```bash
npm i -D @adaloop/prettier-config

yarn add -D @adaloop/prettier-config

pnpm add -D @adaloop/prettier-config
```

## Usage

To enable these rules, add a `prettier` property in your `package.json` and reference this shared config as follows:

```json
{
  "prettier": "@adaloop/prettier-config"
}
```
