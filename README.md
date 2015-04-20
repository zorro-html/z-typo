# Type

基本的字体字号边距等，包括

* 区域内的字体字号字色行高
* `<body>` 的背景色和边距
* 各级标题、段落和列表的字号和边距

注：需要在最外层 (如 `<html>` 标签中) 加入一个特性 `z`，即：`<html z>`

## Example

```
<html z>
  <head>...</head>
  <body>
    <h1>Hello World</h1>
    <p>Paragraph</p>
    <ul>
      <li>Item</li>
      <li>Item</li>
      <li>Item
        <ul>
          <li>Item</li>
          <li>Item</li>
          <li>Item</li>
        </ul>
      </li>
    </ul>
  </body>
</html>
```
