---
title: width offsetWidth clientWidth比较
pubDatetime: 2015-05-06T00:00:00.000Z
description: width offsetWidth clientWidth
---

# First.width相关

1、offsetWidth (width+padding+border)
表示当前对象的宽度，style.width也是当前对象的宽度(width+padding+border)。
区别：
1)style.width返回值除了数字外还带有单位px；2)如对象的宽度设定值为百分比宽度,则无论页面变大还是变小，style.width都返回此百分比,而offsetWidth则返回在不同页面中对象的宽度值而不是百分比值；3)如果没有给 HTML 元素指定过 width样式，则 style.width 返回的是空字符串；
2.clientWidth(不包括border)
获取对象可见内容的宽度，不包括滚动条，不包括边框；
3.scrollWidth(包括滚动条)

# Second. scroll相关

scrollHeight
表示自身元素的高度＋隐藏元素的高度（或者滚动条卷起来的高度），与之对比的是offsetHeight表示元素自身的高度。
scrollTop
表示卷起来的高度值，一般想让元素滚动到底部是，通过把scrollHeight赋值给scrollTop来实现。
