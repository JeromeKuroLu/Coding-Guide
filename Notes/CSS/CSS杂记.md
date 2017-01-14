<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [CSS杂记](#css%E6%9D%82%E8%AE%B0)
  - [页面渲染流程](#%E9%A1%B5%E9%9D%A2%E6%B8%B2%E6%9F%93%E6%B5%81%E7%A8%8B)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## CSS杂记

### 页面渲染流程

- Style(样式)
    + 浏览器计算样式
- Layout(布局)
    + 设置页面属性
    + width
    + height
    + margin
    + left
    + right
    + top
    + bottom
    + ...
- Paint(渲染)
    + 填充像素
    + box-shadow
    + border-radious
    + color
    + background-color
    + ...
- Composite(合成)
    + transform
        * translate
        * scale
        * rotate
        * opacity

`transform`影响浏览器渲染的最后一个阶段，因此使用`transform`做动效，且不改变原有layout（width、height、left等）的时候，页面渲染速度最快。