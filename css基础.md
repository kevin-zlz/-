# css #

1.CSS 指层叠样式表 (Cascading Style Sheets)，样式定义如何显示 HTML 元素，样式通常存储在样式表中，把样式添加到 HTML 4.0 中，是为了解决内容与表现分离的问题，外部样式表可以极大提高工作效率，外部样式表通常存储在 CSS 文件中，多个样式定义可层叠为一。

2.当同一个 HTML 元素被不止一个样式定义时，会使用哪个样式呢？

1. 浏览器缺省设置
1. 外部样式表
1. 内部样式表（位于 <head> 标签内部）
1. 内联样式（在 HTML 元素内部）

3.CSS 规则由两个主要的部分构成：选择器，以及一条或多条声明。p是选择器，括号里面是属性值（声明）

    p {
      text-align: center;
      color: black;
      font-family: arial;
    }

4.css继承：通过 CSS 继承，子元素将继承最高级元素所拥有的属性。

1. 不可继承的：display、margin、border、padding、background、height、min-height、max-height、width、min-width、max-width、overflow、position、left、right、top、bottom、z-index、float、clear、table-layout、vertical-align、page-break-after、page-bread-before和unicode-bidi。

1. 所有元素可继承：visibility和cursor。

1. 内联元素可继承：letter-spacing、word-spacing、white-space、line-height、color、font、font-family、font-size、font-style、font-variant、font-weight、text-decoration、text-transform、direction。

1. 终端块状元素可继承：text-indent和text-align。

1. 列表元素可继承：list-style、list-style-type、list-style-position、list-style-image。

5.CSS 元素选择器，文档的元素就是最基本的选择器。选择器通常将是某个 HTML 元素，比如 p、h1、em、a，甚至可以是 html 本身。