[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Zecat/paper-number-input)

# \<paper-number-input\>

A Material Design input field for numeric values with step up/down buttons (Polymer 2).

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-number-input.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <style>
      paper-number-input {
        max-width: 140px;
        margin: auto;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-number-input
  label="Quantity"
  min="1"
  max="12"
  value="6"
  step="1.1"
  fallback-value="0"
><paper-number-input>
```

## Installation

```bash
  bower install -S Zecat/paper-number-input
```

## Usage

For icons to appear, you can either:

- just import the iron-icons/iron-icons.html Polymer element - it is a dependency of this element but not imported by default
- create your own icon set and specify `stepDownIcon` and `stepUpIcon` properties according
- import paper-number-input/paper-number-input-icons and define `stepDownIcon` as 'integer-input:step-down' and `stepUpIcon` as 'integer-input:step-up'
