## 什么是BFC？如何应用？

- Block format context 块级格式化上下文

- 一块独立渲染的区域，内部元素的渲染不会影响边界以外的元素（可以理解为，内部元素不会跑出去。外界元素也不会挡着你，只会你挡着它。）

## 形成 BFC 的常见条件

- float 不是 none

- position 是 absolute 或 fixed

- overflow 不是 visible

- display 是 flex inline-block 等

## BFC 的应用

- 清除浮动