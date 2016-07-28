[![CircleCI](https://circleci.com/gh/palantir/eslint-config-palantir.svg?style=shield&circle-token=b247f939bd76123d71494eec8a6738bf2c82f91f)](https://circleci.com/gh/palantir/eslint-config-palantir)
[![npm version](https://badge.fury.io/js/eslint-config-palantir.svg)](https://badge.fury.io/js/eslint-config-palantir)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# ESLint Config Palantir

Linter configuration for [ESLint](http://eslint.org/).

## Usage

### Install

```sh
npm install --save-dev eslint-config-palantir
```

### Lint JavaScript

[ESLint](http://eslint.org) is the preferred JS linter. Configure your `.eslintrc` file to extend the one in this
package:

```yaml
extends: "./node_modules/eslint-config-palantir/.eslintrc.yml"

rules:
  # Add overrides and additional rules here
  no-console:
    - 1
```

The path to your `node_modules` directory may vary.

See the [ESLint docs](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) for details about the
`extends` property.
