title: JS中各种定位属性汇总
author: Hyuni
date: 2016-07-24 20:24:09
tags:
---
参考资料：MDN
# element.clientWidth/Height  
表示元素的内部宽度，以像素计。该属性包括内边距，但不包括垂直滚动条（如果有的话）、边框和外边距。
# element.scrollWidth/Height
元素的scrollWidth只读属性以px为单位返回元素的内容区域宽度或元素的本身的宽度中更大的那个值。若元素的宽度大于其内容的区域（例如，元素存在滚动条时）, scrollWidth的值要大于clientWidth。
# element.offsetWidth/Height  
HTMLElement.offsetWidth 是一个只读属性，返回一个元素的布局宽度。一个典型的offsetWidth是测量元素的边框(borders)、水平线上的内边距(padding)、竖直方向滚动条(scroolbar)（如果存在的话）、以及CSS设置的宽度(width)的值。
# element.clientLeft/Top

# element.offsetLeft/Top
返回当前元素**左上角**对于offsetParent节点的左/上边界的偏移像素值。