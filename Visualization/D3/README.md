## 画布
HTML 5 提供两种强有力的“画布”：SVG 和 Canvas。

### svg
svg 是可缩放矢量图形

有以下特点
1. SVG 绘制的是矢量图，因此对图像进行放大不会失真
2. 基于 XML，可以为每个元素添加 JavaScript 事件处理器
3. 每个图形均视为对象，更改对象的属性，图形也会改变
4. 不适合游戏应用

### Canvas

Canvas 是通过 JavaScript 来绘制 2D 图形，是 HTML 5 中新增的元素。

有以下特点：

1. 绘制的是位图，图像放大后会失真
2. 不支持事件处理器
3. 能够以 .png 或 .jpg 格式保存图像
4. 适合游戏应用

> PS：d3中提供了众多的svg图形生成器。因此，建议使用svg画布

[快速入门](http://hsilomedus.me/wp-content/uploads/javadayd3/index.html#myCarousel)
