# \<paper-relative-integer-input\>

A Material Design input field for relative integer with step up/down buttons (Polymer 1.9 - 2.x).

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-relative-integer-input.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<style>
  paper-relative-integer-input {
    max-width: 140px;
    margin: auto;
  }
</style>
<paper-relative-integer-input
  label="Quantity"
  min="1"
  max="12"
  value="6"
  step="2"
  fallback-value="1"
><paper-relative-integer-input>
```

## Installation

```bash
  bower install -S Zecat/paper-relative-integer-input
```

## Usage

For icons to appear, you can either:

- just import the iron-icons/iron-icons.html Polymer element - it is a dependency of this element but not imported by default
- create your own icon set and specify `stepDownIcon` and `stepUpIcon` properties according
- import paper-relative-integer-input/paper-relative-integer-input-icons and define `stepDownIcon` as 'integer-input:step-down' and `stepUpIcon` as 'integer-input:step-up'
