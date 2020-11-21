# HTML CSS 一些其它的~

## 层叠上下文

- z-index 属性并不是在任何元素上都有效果。例举一些常见的有层叠上下文的情况：

    - HTML

    - 有 position ，除 static 外，设置 z-index 并且不为 auto

    - flex、grid 容器的子元素，设置 z-index 并且不为 auto

    - opacity 小于 1

    - transform filter 不为 none

- 不同层叠上下文的层叠等级之间没有意义。

## 选择器

## 文档流

## 动画