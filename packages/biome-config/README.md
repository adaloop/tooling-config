# @tbrul/prettier-config

The `@tbrul/prettier-config` package exports the base Biome configuration for tbrul packages.

## Installation

Install the package as a development dependency from the npm packages registry.

```bash
npm i -D @tbrul/biome-config

yarn add -D @tbrul/biome-config

pnpm add -D @tbrul/biome-config
```

## Usage

Add the following rule to your package biome config file.

```json
{
  "extends": "@tbrul/biome-config/package"
}
```
