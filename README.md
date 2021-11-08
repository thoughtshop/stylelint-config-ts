# stylelint-config-ts
Thought Shop shareable configuration for Stylelint.

This config:
- extends the `stylelint-config-standard-scss`

To see the rules that this config uses, please read the [config itself](/index.js).

## Installation

```shell
yarn add --dev stylelint-config-ts
```

## Usage

Set your `stylelint` config to:

```json
{
  "extends": "stylelint-config-ts"
}
```

### Extending the config

Simply add a `"rules"` key to your config, then add your overrides and additions there.

For example, to turn off the `scss/dollar-variable-pattern` rule:

```json
{
  "extends": "stylelint-config-standard-scss",
  "rules": {
    "scss/dollar-variable-pattern": null
  }
}
```