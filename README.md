ember-template-lint-plugin-css-modules
==============================================================================

[ember-template-lint] plugin for [ember-css-modules]

[ember-template-lint]: https://github.com/ember-template-lint/ember-template-lint
[ember-css-modules]: https://github.com/salsify/ember-css-modules


Installation
------------------------------------------------------------------------------

```bash
yarn add --dev ember-template-lint-plugin-css-modules
```


Usage
------------------------------------------------------------------------------

```js
// .template-lintrc.js

module.exports = {
  plugins: ['ember-template-lint-plugin-css-modules'],

  rules: {
    'css-modules/static-local-class': true,
  },
};
```


Rules
------------------------------------------------------------------------------

- [no-class](./rules/no-class.md) – Disallows usage of all `class` attributes
- [static-local-class](./rules/static-local-class.md) – Disallows use of
  variable values in `local-class` attributes


License
------------------------------------------------------------------------------

This projects is developed by and &copy; [simplabs GmbH](http://simplabs.com)
and contributors. It is released under the [MIT License](LICENSE.md).
