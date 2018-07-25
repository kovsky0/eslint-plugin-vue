---
sidebarDepth: 0
---

# All rules

## Base Rules (Enabling Correct ESLint Parsing)

Enforce all the rules in this category, as well as all higher priority rules, with:

```json
{
  "extends": "plugin:vue/base"
}
```

| Rule ID | Description |    |
|:--------|:------------|:---|
| [vue/comment-directive](./comment-directive.md) | support comment-directives in `<template>` |  |
| [vue/jsx-uses-vars](./jsx-uses-vars.md) | prevent variables used in JSX to be marked as unused |  |

## Priority A: Essential (Error Prevention)

Enforce all the rules in this category, as well as all higher priority rules, with:

```json
{
  "extends": "plugin:vue/essential"
}
```

| Rule ID | Description |    |
|:--------|:------------|:---|
| [vue/no-async-in-computed-properties](./no-async-in-computed-properties.md) | disallow asynchronous actions in computed properties |  |
| [vue/no-dupe-keys](./no-dupe-keys.md) | disallow duplication of field names |  |
| [vue/no-duplicate-attributes](./no-duplicate-attributes.md) | disallow duplication of attributes |  |
| [vue/no-parsing-error](./no-parsing-error.md) | disallow parsing errors in `<template>` |  |
| [vue/no-reserved-keys](./no-reserved-keys.md) | disallow overwriting reserved keys |  |
| [vue/no-shared-component-data](./no-shared-component-data.md) | enforce component's data property to be a function | :wrench: |
| [vue/no-side-effects-in-computed-properties](./no-side-effects-in-computed-properties.md) | disallow side effects in computed properties |  |
| [vue/no-template-key](./no-template-key.md) | disallow `key` attribute on `<template>` |  |
| [vue/no-textarea-mustache](./no-textarea-mustache.md) | disallow mustaches in `<textarea>` |  |
| [vue/no-unused-vars](./no-unused-vars.md) | disallow unused variable definitions of v-for directives or scope attributes |  |
| [vue/require-component-is](./require-component-is.md) | require `v-bind:is` of `<component>` elements |  |
| [vue/require-render-return](./require-render-return.md) | enforce render function to always return value |  |
| [vue/require-v-for-key](./require-v-for-key.md) | require `v-bind:key` with `v-for` directives |  |
| [vue/require-valid-default-prop](./require-valid-default-prop.md) | enforce props default values to be valid |  |
| [vue/return-in-computed-property](./return-in-computed-property.md) | enforce that a return statement is present in computed property |  |
| [vue/valid-template-root](./valid-template-root.md) | enforce valid template root |  |
| [vue/valid-v-bind](./valid-v-bind.md) | enforce valid `v-bind` directives |  |
| [vue/valid-v-cloak](./valid-v-cloak.md) | enforce valid `v-cloak` directives |  |
| [vue/valid-v-else-if](./valid-v-else-if.md) | enforce valid `v-else-if` directives |  |
| [vue/valid-v-else](./valid-v-else.md) | enforce valid `v-else` directives |  |
| [vue/valid-v-for](./valid-v-for.md) | enforce valid `v-for` directives |  |
| [vue/valid-v-html](./valid-v-html.md) | enforce valid `v-html` directives |  |
| [vue/valid-v-if](./valid-v-if.md) | enforce valid `v-if` directives |  |
| [vue/valid-v-model](./valid-v-model.md) | enforce valid `v-model` directives |  |
| [vue/valid-v-on](./valid-v-on.md) | enforce valid `v-on` directives |  |
| [vue/valid-v-once](./valid-v-once.md) | enforce valid `v-once` directives |  |
| [vue/valid-v-pre](./valid-v-pre.md) | enforce valid `v-pre` directives |  |
| [vue/valid-v-show](./valid-v-show.md) | enforce valid `v-show` directives |  |
| [vue/valid-v-text](./valid-v-text.md) | enforce valid `v-text` directives |  |

## Priority B: Strongly Recommended (Improving Readability)

Enforce all the rules in this category, as well as all higher priority rules, with:

```json
{
  "extends": "plugin:vue/strongly-recommended"
}
```

| Rule ID | Description |    |
|:--------|:------------|:---|
| [vue/attribute-hyphenation](./attribute-hyphenation.md) | enforce attribute naming style on custom components in template | :wrench: |
| [vue/html-end-tags](./html-end-tags.md) | enforce end tag style | :wrench: |
| [vue/html-indent](./html-indent.md) | enforce consistent indentation in `<template>` | :wrench: |
| [vue/html-self-closing](./html-self-closing.md) | enforce self-closing style | :wrench: |
| [vue/max-attributes-per-line](./max-attributes-per-line.md) | enforce the maximum number of attributes per line | :wrench: |
| [vue/mustache-interpolation-spacing](./mustache-interpolation-spacing.md) | enforce unified spacing in mustache interpolations | :wrench: |
| [vue/name-property-casing](./name-property-casing.md) | enforce specific casing for the name property in Vue components | :wrench: |
| [vue/no-multi-spaces](./no-multi-spaces.md) | disallow multiple spaces | :wrench: |
| [vue/require-default-prop](./require-default-prop.md) | require default value for props |  |
| [vue/require-prop-types](./require-prop-types.md) | require type definitions in props |  |
| [vue/v-bind-style](./v-bind-style.md) | enforce `v-bind` directive style | :wrench: |
| [vue/v-on-style](./v-on-style.md) | enforce `v-on` directive style | :wrench: |

## Priority C: Recommended (Minimizing Arbitrary Choices and Cognitive Overhead)

Enforce all the rules in this category, as well as all higher priority rules, with:

```json
{
  "extends": "plugin:vue/recommended"
}
```

| Rule ID | Description |    |
|:--------|:------------|:---|
| [vue/attributes-order](./attributes-order.md) | enforce order of attributes | :wrench: |
| [vue/html-quotes](./html-quotes.md) | enforce quotes style of HTML attributes | :wrench: |
| [vue/no-confusing-v-for-v-if](./no-confusing-v-for-v-if.md) | disallow confusing `v-for` and `v-if` on the same element |  |
| [vue/order-in-components](./order-in-components.md) | enforce order of properties in components | :wrench: |
| [vue/this-in-template](./this-in-template.md) | enforce usage of `this` in template |  |

## Uncategorized

| Rule ID | Description |    |
|:--------|:------------|:---|
| [vue/html-closing-bracket-newline](./html-closing-bracket-newline.md) | require or disallow a line break before tag's closing brackets | :wrench: |
| [vue/html-closing-bracket-spacing](./html-closing-bracket-spacing.md) | require or disallow a space before tag's closing brackets | :wrench: |
| [vue/no-use-v-if-with-v-for](./no-use-v-if-with-v-for.md) | disallow use v-if on the same element as v-for |  |
| [vue/no-v-html](./no-v-html.md) | disallow use of v-html to prevent XSS attack |  |
| [vue/prop-name-casing](./prop-name-casing.md) | enforce specific casing for the Prop name in Vue components | :wrench: |
| [vue/script-indent](./script-indent.md) | enforce consistent indentation in `<script>` | :wrench: |