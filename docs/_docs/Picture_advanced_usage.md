---
#layout: article
title: 文章中插入图片的高级用法
date: 2020-07-27
permalink: /docs/Picture_advanced_usage
key: docs-Picture-advanced-usage
---  
上一种插入图片的方式比较简单粗暴，直接占满了整个屏幕，可我们有时图片太小，或想要在图片旁边一侧打字，或为图片加上特效该如何实现呢?下面以一张小鱼的图片作为示例。  
这是小鱼的网络地址：http://pic.yupoo.com/erowz/19de4592/f9ace13f.jpg  
最简单粗暴的效果是这样的：  
![img](http://pic.yupoo.com/erowz/19de4592/f9ace13f.jpg)  
###　图片的高级用法　　
　　
## 图片

| 样式名称 |
| ---- |
| **border** |
| **shadow** |
| **rounded** |
| **circle** |

### Border

<div class="grid-containre">
<div class="grid grid--p-2">
<div class="cell cell--12 cell--md-4 " markdown="1">
![Image](https://raw.githubusercontent.com/kitian616/jekyll-TeXt-theme/master/docs/assets/images/image.jpg "Image_border"){:.border}
</div>
<div class="cell cell--12 cell--md-auto" markdown="1">
    ![Image](path-to-image){:.border}
</div>
</div>
</div>

### Shadow

<div class="grid-containre">
<div class="grid grid--p-2">
<div class="cell cell--12 cell--md-4 " markdown="1">
![Image](https://raw.githubusercontent.com/kitian616/jekyll-TeXt-theme/master/docs/assets/images/image.jpg "Image_shadow"){:.shadow}
</div>
<div class="cell cell--12 cell--md-auto" markdown="1">
    ![Image](path-to-image){:.shadow}
</div>
</div>
</div>

### Rounded

<div class="grid-containre">
<div class="grid grid--p-2">
<div class="cell cell--12 cell--md-4 " markdown="1">
![Image](https://raw.githubusercontent.com/kitian616/jekyll-TeXt-theme/master/docs/assets/images/image.jpg "Image_rounded"){:.rounded}
</div>
<div class="cell cell--12 cell--md-auto" markdown="1">
    ![Image](path-to-image){:.rounded}
</div>
</div>
</div>

### Circle

<div class="grid-containre">
<div class="grid grid--p-2">
<div class="cell cell--12 cell--md-4 " markdown="1">
![Image](https://raw.githubusercontent.com/kitian616/jekyll-TeXt-theme/master/docs/assets/images/image.jpg "Image_circle"){:.circle}
</div>
<div class="cell cell--12 cell--md-auto" markdown="1">
    ![Image](path-to-image){:.circle}
</div>
</div>
</div>

### Mixture

<div class="grid-containre">
<div class="grid grid--p-2">
<div class="cell cell--12 cell--md-4 " markdown="1">
![Image](https://raw.githubusercontent.com/kitian616/jekyll-TeXt-theme/master/docs/assets/images/image.jpg "Image_border+rounded"){:.border.rounded}
</div>
<div class="cell cell--12 cell--md-auto" markdown="1">
    ![Image](path-to-image){:.border.rounded}
</div>
</div>
</div>

<div class="grid-containre">
<div class="grid grid--p-2">
<div class="cell cell--12 cell--md-4 " markdown="1">
![Image](https://raw.githubusercontent.com/kitian616/jekyll-TeXt-theme/master/docs/assets/images/image.jpg "Image_circle+shadow"){:.circle.shadow}
</div>
<div class="cell cell--12 cell--md-auto" markdown="1">
    ![Image](path-to-image){:.circle.shadow}
</div>
</div>
</div>

<div class="grid-containre">
<div class="grid grid--p-2">
<div class="cell cell--12 cell--md-4 " markdown="1">
![Image](https://raw.githubusercontent.com/kitian616/jekyll-TeXt-theme/master/docs/assets/images/image.jpg "Image_circle+border+shadow"){:.circle.border.shadow}
</div>
<div class="cell cell--12 cell--md-auto" markdown="1">
    ![Image](path-to-image){:.circle.border.shadow}
</div>
</div>
</div>
