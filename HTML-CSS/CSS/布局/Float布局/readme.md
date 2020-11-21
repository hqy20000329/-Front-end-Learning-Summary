## 如何实现圣杯布局与双飞翼布局？（PC浏览器中常见的、使用 float 的布局方式）

- 目的
    - 三栏布局，中间一栏最先加载和渲染（内容最重要）
    - 两侧内容固定，中间内容宽度自适应
    - 一般用于 PC 网页

- 总结
    - 使用 float 布局
    - 两侧使用 margin 负值，以便和中间内容横向重叠
    - 防止中间内容被两侧覆盖，一个用 padding ，一个用 margin

## 手写 clearfix （清除浮动）

.clearfix:after{
    content: '';
    display: table;
    clear:both;
}