title:  Blog::Web UI
layout: blog.liquid
permalink: /blog/2018/01-20:Web-UI.html
---

### HTML元素:
*  div、p 元素属于block类型。span、a 元素属于inline类型.
*  inline-block类型属于block类型，显示inline类型特点，所以拥有width和height等block类型拥有的属性。
*  [header标签](http://www.tuicool.com/articles/MNbi6zu)

### viewport设置属性如下：
- width：可设定数值，或者指定为 device-width
- height：可设定数值，或者指定為 device-height
- initial-scale：第一次进入页面的初始比例
- minimum-scale：允许缩小最小比例
- maximum-scale：允许放大最大比例
- user-scalable：允许使用者缩放，1 or 0 (yes or no)

```html
<header>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge,chrome=1">
    <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no,shrink-to-fit=no">
    <meta name="HandheldFriendly" content="true">
    <!-- 以上 meta 标签 *必须* 放在 head 的最前面；其他任何的 head 内容必须在这些标签的 *后面* -->
    <!-- 文档标题 -->
    <title>页面标题</title>

    <!-- 基本 URL 作用于文档中所包含的所有相对 URL -->
    <base href="https://example.com/page.html">

    <!-- 外部的 CSS -->
    <link rel="stylesheet" href="styles.css">

    <!-- 文档内的 CSS -->
    <style>
    /* ... */
    </style>

    <!-- JavaScript -->
    <script src="script.js"></script>
    <noscript><!--无 JS 时的替代--></noscript>
</header>
```

* [Responsive Web Design](https://developers.google.com/web/fundamentals/design-and-ui/responsive/?hl=zh-cn)
* [自适应设计与响应式设计](http://www.alloyteam.com/2015/04/zi-shi-ying-she-ji-yu-xiang-ying-shi-wang-ye-she-ji-qian-tan/)
* [响应式布局设计](http://www.tuicool.com/articles/IBbIraZ)
* [HTML5/CSS3响应式布局介绍以及设计流程概述](http://www.tuicool.com/articles/yyIfmaZ)
* [响应式布局技巧](http://www.tuicool.com/articles/mAzA7jM)
* [CSS Grid布局](http://www.tuicool.com/articles/IbiiyqJ)
* [flex盒子模型](http://www.tuicool.com/articles/mYNvEna)
