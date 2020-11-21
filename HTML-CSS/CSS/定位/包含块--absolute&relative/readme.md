## relative 

- 具体效果可以理解为反方向移动

- 包含块为最近的祖先块元素的**内容区**的边缘

    - 也就是 border 和 padding 都会影响 relative 的位置

## absolute 

- 包含块为主要为最近的以下情况的**内边距区**

    - 也就是 border 会影响 absolute ，而 padding 不会

- position:static 之外的定位元素

- transform / perspective 不是 none 

- body


详情见：[包含块](https://developer.mozilla.org/zh-CN/docs/Web/CSS/All_About_The_Containing_Block)

