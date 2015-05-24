# Typo

General styles of some basic HTML5 elements.

- `<h1>` ~ `<h6>`, `<p>`
- `<ul>`, `<ol>`, `<li>`

## Import

```
<link rel="import" href="z-typo/z-typo.html">
```

## Usage

Just add `[z]` attribute to any parent element of the target table like `<body z>`

## Examples

```
<div z>
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
  <p>Paragraph</p>
  <ul>
      <li>List Item</li>
      <li>List Item</li>
      <li>List Item</li>
      <li>List Item
          <ul>
              <li>List Item</li>
              <li>List Item</li>
              <li>List Item</li>
              <li>List Item</li>
          </ul>
      </li>
  </ul>
  <ol>
      <li>Ordered List Item</li>
      <li>Ordered List Item</li>
      <li>Ordered List Item</li>
      <li>Ordered List Item
          <ol>
              <li>Ordered List Item</li>
              <li>Ordered List Item</li>
              <li>Ordered List Item</li>
              <li>Ordered List Item</li>
          </ol>
      </li>
  </ol>
  <ul unstyled>
      <li>Unstyled List Item</li>
      <li>Unstyled List Item</li>
      <li>Unstyled List Item</li>
      <li>Unstyled List Item
          <ul>
              <li>List Item</li>
              <li>List Item</li>
              <li>List Item</li>
              <li>List Item</li>
          </ul>
      </li>
  </ul>
</div>
```
