### 水平垂直居中

父元素
```css
display:flex;
align-items: center; // 垂直居中
justify-content:center;// 水平居中 
height: 100%;
```
### 动画需要在 display 为块或行块元素才能作用

### `nth-child(odd)` 和 `nth-child(even)` 分别选择单数和复数子标签

### `attr(属性名)` 动态获得属性

### 除了 `display:grid`,子元素如果定位为 `absolute`,会和父元素重合

### `overflow: hidden;` 失效

1. 拥有 `overflow:hidden` 样式的块元素不具有 `position:relative` 和 `position:absolute` 样式；
2. 内部溢出的元素是通过 `position:absolute` 绝对定位；