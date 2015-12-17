# CSS / SASS Styleguide

## Table of Content

- SASS
  - Formatting
  - Examples
- BEM
- Mixin
- File organization


## SASS

### 语法格式

- 使用两个空格缩进
- 使用 // 进行注释，注释单独一行
- 给特殊代码详细注释，例如：z-index，兼容性 hacks
- 每一个选择器单独一行，每一个 CSS 规则单独一行
- 属性声明 : 后加空格
- 使用十六进制表示颜色，除非必须使用 rgba( )（rgba( ) 方法重新加载接受十六进制的颜色作为参数，例如：rgba(#000, .5)）
- 使用缩写，但避免不必要的缩写，例如：margin: 0 0 20px;
- 避免使用多余的单位，例如：margin: 0em; 而不是 margin: 0;
- 避免使用多余的 0，例如：margin: .5em; 而不是 margin: 0.5em;
- 属性值使用单引号
- 嵌套尽量不超过三层（BEM 命名可避免）
- 不使用 ID 选择器

### 例子

  // Example
  .styleguide-format,
  .styleguide-format-multi
    color: #000
    background-color: rgba(0, 0, 0, .5)
    border: 1px solid #0f0
    margin: 0 .5em 10px 20px
    padding: 0

  .another-selector
    display: block
    content: '\2193'


## BEM

## Mixin

## File organization
