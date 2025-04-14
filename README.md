# stylelint-config-scss

**Shareable [Stylelint](https://stylelint.io) configuration for SCSS syntax [Sass](https://sass-lang.com) files.**

[![npm](https://img.shields.io/npm/v/@cargosense/stylelint-config-scss.svg?logo=npm&style=for-the-badge)](https://www.npmjs.com/package/@cargosense/stylelint-config-scss)
[![Downloads](https://img.shields.io/npm/dt/@cargosense/stylelint-config-scss.svg?logo=npm&style=for-the-badge)](https://www.npmjs.com/package/@cargosense/stylelint-config-scss)
[![Build](https://img.shields.io/github/actions/workflow/status/CargoSense/stylelint-config-scss/ci.yml?logo=github&style=for-the-badge)](https://github.com/CargoSense/stylelint-config-scss/actions/workflows/ci.yml)

## Installation

```sh
npm install --save-dev @cargosense/stylelint-config-scss
```

## Usage

Stylelint supports [a variety of configuration file formats](https://stylelint.io/user-guide/configure).

> [!TIP]
> We recommend using a configuration file named `stylelint.config.js` using either [ECMAScript module (ESM)](https://nodejs.org/api/esm.html) or [CommonJS module](https://nodejs.org/api/modules.html) syntax.

### YAML

In a file named `.stylelintrc` or `.stylelintrc.yml`:

```yaml
---
extends: "@cargosense/stylelint-config-scss"
---
```

### JSON

In a file named `.stylelintrc` or `.stylelintrc.json`:

```json
{
  "extends": "@cargosense/stylelint-config-scss"
}
```

### JavaScript

In a JavaScript file using ESM syntax:

```js
// stylelint.config.mjs
export { default } from "@cargosense/stylelint-config-scss";

// or…
import config from "@cargosense/stylelint-config-scss";

export default {
  extends: [config]
};
```

In a JavaScript file using CommonJS module syntax:

```js
// stylelint.config.cjs
module.exports = {
  extends: ["@cargosense/stylelint-config-scss"]
}
```

## License

stylelint-config-scss is freely available under the [MIT License](https://opensource.org/licenses/MIT).
