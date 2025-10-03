::: {#app server-rendered="true"}
::: theme-container
::: navbar
::: sidebar-button
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiByb2xlPSJpbWciIHZpZXdib3g9IjAgMCA0NDggNTEyIiBjbGFzcz0iaWNvbiI+PHBhdGggZmlsbD0iY3VycmVudENvbG9yIiBkPSJNNDM2IDEyNEgxMmMtNi42MjcgMC0xMi01LjM3My0xMi0xMlY4MGMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6Ij48L3BhdGg+PC9zdmc+){.icon}
:::

[![Xiaomi Vela JS 应用开发文档](../../../logo.png){.logo} [Xiaomi Vela
JS 应用开发文档]{.site-name
.can-hide}](https://iot.mi.com/vela/quickapp/){.home-link
.router-link-active}

::: links
::: search-box
:::

::: nav-item
[教程](../../guide/version/APILevel4.html){.nav-link}
:::

::: nav-item
[组件](../index.html){.nav-link .router-link-active}
:::

::: nav-item
[JS接口](../../features/index.html){.nav-link}
:::

::: nav-item
[编程示例](../../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../../tools/index.html){.nav-link}
:::
:::
:::

::: sidebar-mask
:::

::: nav-item
[教程](../../guide/version/APILevel4.html){.nav-link}
:::

::: nav-item
[组件](../index.html){.nav-link .router-link-active}
:::

::: nav-item
[JS接口](../../features/index.html){.nav-link}
:::

::: nav-item
[编程示例](../../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../../tools/index.html){.nav-link}
:::

-   ::: {.section .sidebar-group .depth-0}
    [通用规范](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [通用样式](style.html){.sidebar-link}
    -   [颜色配置](color.html){.sidebar-link}
    -   [动画样式](animation-style.html){.active .sidebar-link
        aria-current="page"}
    -   [背景图样式](background-img-styles.html){.sidebar-link}
    -   [通用属性](properties.html){.sidebar-link}
    -   [通用事件](events.html){.sidebar-link}
    -   [通用方法](methods.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [容器组件](../container/index.html){.sidebar-heading .clickable}
    -   [div](../container/div.html){.sidebar-link}
    -   [list](../container/list.html){.sidebar-link}
    -   [list-item](../container/list-item.html){.sidebar-link}
    -   [scroll](../container/scroll.html){.sidebar-link}
    -   [stack](../container/stack.html){.sidebar-link}
    -   [swiper](../container/swiper.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [基础组件](../basic/index.html){.sidebar-heading .clickable}
    -   [text](../basic/text.html){.sidebar-link}
    -   [span](../basic/span.html){.sidebar-link}
    -   [a](../basic/a.html){.sidebar-link}
    -   [image](../basic/image.html){.sidebar-link}
    -   [image-animator](../basic/image-animator.html){.sidebar-link}
    -   [progress](../basic/progress.html){.sidebar-link}
    -   [marquee](../basic/marquee.html){.sidebar-link}
    -   [chart](../basic/chart.html){.sidebar-link}
    -   [qrcode](../basic/qrcode.html){.sidebar-link}
    -   [barcode](../basic/barcode.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [表单组件](../form/index.html){.sidebar-heading .clickable}
    -   [input](../form/input.html){.sidebar-link}
    -   [picker](../form/picker.html){.sidebar-link}
    -   [switch](../form/switch.html){.sidebar-link}
    -   [slider](../form/slider.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](animation-style.html#动画样式){.header-anchor} 动画样式

Vela JS
应用支持开发者制作动画，提供了`transform`类、`transform-origin`类、`animation`类与`transition`类的动画样式属性，且参数格式与
CSS 对齐，更方便开发者上手适配动画。

`transform`可参考此[文档![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
.outbound} [(opens new
window)]{.sr-only}](https://developer.mozilla.org/zh-CN/docs/Web/CSS/transform){target="_blank"
rel="noopener noreferrer"}。

`transform-origin`可参考此[文档![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
.outbound} [(opens new
window)]{.sr-only}](https://developer.mozilla.org/zh-CN/docs/Web/CSS/transform-origin){target="_blank"
rel="noopener noreferrer"}。

`animation`可参考此[文档![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
.outbound} [(opens new
window)]{.sr-only}](https://developer.mozilla.org/zh-CN/docs/Web/CSS/animation){target="_blank"
rel="noopener noreferrer"}。

`transition`
可参考此[文档![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
.outbound} [(opens new
window)]{.sr-only}](https://developer.mozilla.org/zh-CN/docs/Web/CSS/transition){target="_blank"
rel="noopener noreferrer"}。

## [\#](animation-style.html#动画样式列表){.header-anchor} 动画样式列表

  名称                         类型                                                                                                                                                                                            默认值   描述
  ---------------------------- ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  transform                    `<string>`                                                                                                                                                                                      \-       见下面 transform 操作
  transform-origin             `<string>`                                                                                                                                                                                      \-       见下面 transform-origin 操作
  animation-name               `<string>`                                                                                                                                                                                      \-       与@keyframes 的 name 相呼应，见下面@keyframes 属性
  animation-delay              `<time>`                                                                                                                                                                                        0        目前支持的单位为\[ s(秒) \| ms(毫秒) \]
  animation-duration           `<time>`                                                                                                                                                                                        0        目前支持的单位为\[ s(秒) \| ms(毫秒) \]
  animation-iteration-count    `<integer>` \| `infinite`                                                                                                                                                                       1        定义动画播放的次数，可设置为`infinite`无限次播放
  animation-timing-function    linear \| ease \| ease-in \| ease-out \| ease-in-out \| cubic-bezier(`<number>`, `<number>`, `<number>`, `<number>`) \| step-start \| step-end \| steps(number_of_steps\[, step-direction\]?)   ease     \-
  transition-property          `<string>`                                                                                                                                                                                      all      指定执行 transition 效果的通用样式属性名称，参见[详情](animation-style.html#transition-property-%E6%94%AF%E6%8C%81%E7%9A%84%E9%80%9A%E7%94%A8%E6%A0%B7%E5%BC%8F%E5%B1%9E%E6%80%A7)
  transition-duration          `<time>`                                                                                                                                                                                        0s       指定 transition 执行时间
  transition-timing-function   linear \| ease \| ease-in \| ease-out \| ease-in-out \| cubic-bezier(`<number>`, `<number>`, `<number>`, `<number>`) \| step-start \| step-end \| steps(number_of_steps\[, step-direction\]?)   ease     指定 transition 执行时的时间函数。该参数释义与 animation 相同
  transition-delay             `<time>`                                                                                                                                                                                        0s       指定 transition 开始执行的时间，即当改变元素属性值后多长时间开始执行 transition 效果

**注**：

-   animation-timing-function 类型

cubic-bezier(`<number>`, `<number>`, `<number>`, `<number>`) \|
step-start \| step-end \| steps(number_of_steps\[,
step-direction\]?)其中：

steps(number_of_steps，step-direction)

+-------------+-------------+-------------+-------------+-------------+
| 名称        | 类型        | 默认值      | 必填        | 描述        |
|             |             |             |             |             |
|             |             | ::: w50     | ::: w50     |             |
|             |             | :::         | :::         |             |
+=============+=============+=============+=============+=============+
| numb        | `<integer>` | \-          | 是          | 表          |
| er_of_steps |             |             |             | 示等间隔步  |
|             |             |             |             | 数的正整数  |
+-------------+-------------+-------------+-------------+-------------+
| ste         | jump-start  | end         | 否          | 指示函数左  |
| p-direction | \| jump-end |             |             | 连续或右连  |
|             | \|          |             |             | 续的关键字  |
|             | jump-none   |             |             |             |
|             | \|          |             |             |             |
|             | jump-both   |             |             |             |
|             | \| start \| |             |             |             |
|             | end         |             |             |             |
+-------------+-------------+-------------+-------------+-------------+

-   cubic-bezier(x1, y1, x2, y2)

参数 x1, y1, x2, y2 是 `<number>`
类型的值，代表当前定义的立方贝塞尔曲线中的 P1 和 P2
点的横坐标和纵坐标，x1 和 x2 必须在 \[0，1\] 范围内，否则当前值无效。

## [\#](animation-style.html#transform-操作){.header-anchor} transform 操作

向元素应用 2D 转换。该属性允许我们对元素进行旋转、缩放、移动。
支持的样式属性列表如下：

  名称         类型
  ------------ ---------------------------
  translate    `<length>` \| `<percent>`
  translateX   `<length>` \| `<percent>`
  translateY   `<length>` \| `<percent>`
  scale        `<number>`
  scaleX       `<number>`
  scaleY       `<number>`
  rotate       `<deg>`

## [\#](animation-style.html#transform-origin-操作){.header-anchor} transform-origin 操作

更改一个元素变形的原点，目前支持改变元素的 X 和 Y 轴。

**注意：**

-   使用此属性必须先使用 transform 属性。

示例代码：

::: {.language-css .extra-class}
``` language-css
/* 使用 % 值 */
div {
  transform: rotate(30deg); 
  transform-origin: 20% 40%;
}
/* 使用 px 值 */
div {
  transform: rotate(30deg); 
  transform-origin: 100px 100px;
}
```
:::

## [\#](animation-style.html#animation-name-属性){.header-anchor} animation-name 属性

指定所采用的一系列动画，属性值的每个名称代表一个由 \@keyframes
属性定义的关键帧序列。该属性支持在组件中应用单个动画或多个动画 `1070+`
，应用多个动画时动画同时开始执行。

示例代码：

::: {.language-js .extra-class}
``` language-js
/* 单个动画 */
animation-name: Color;
animation-name: translate;
animation-name: rotate;

/* 多个动画 1070+ */
animation-name: Color, Opacity;
animation-name: Width, translate, rotate;
```
:::

## [\#](animation-style.html#keyframes-属性){.header-anchor} \@keyframes 属性

+-----------------+-----------------+-----------------+-----------------+
| 名称            | 类型            | 默认值          | 描述            |
|                 |                 |                 |                 |
|                 |                 | ::: w50         |                 |
|                 |                 | :::             |                 |
+=================+=================+=================+=================+
| b               | `<color>`       | \-              | \-              |
| ackground-color |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| back            | `<length>`      | 0px 0px         | 描述了背景      |
| ground-position | \|`             |                 | 图片在容器中绘  |
|                 | <percentage>`\| |                 | 制的位置，支持  |
|                 | left \| right   |                 | 1-4             |
|                 | \| top \|       |                 | 个参数，详      |
|                 | bottom \|       |                 | 情见[背景图样式 |
|                 | center          |                 | ](background-i  |
|                 |                 |                 | mg-styles.html) |
+-----------------+-----------------+-----------------+-----------------+
| opacity         | `<number>`      | \-              | \-              |
+-----------------+-----------------+-----------------+-----------------+
| width/height    | `<length>`      | \-              | 暂不支持百分比  |
+-----------------+-----------------+-----------------+-----------------+
| transform       | `<string>`      | \-              | 可              |
|                 |                 |                 | 以对元素进行旋  |
|                 |                 |                 | 转、缩放、移动  |
+-----------------+-----------------+-----------------+-----------------+

**注**：

暂时不支持起始值(0%)或终止值(100%)缺省的情况，都需显式指定。

## [\#](animation-style.html#transition-过渡动画){.header-anchor} transition 过渡动画

transition
过渡动画是实现动画的另一种方式。过渡动画可以为元素定义在不同状态之间切换时的过渡效果，比如通过
JavaScript 实现的状态变化。

### [\#](animation-style.html#transition-使用示例){.header-anchor} transition 使用示例

共 4
个样式属性：transition-property、transition-duration、transition-timing-function、transition-delay，直接写在样式当中，使用示例如下：

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <div class="div {{otherClass}}"></div>
  </div>
</template>

<script>
  export default {
    data: {
      otherClass: ""
    },
    onShow() {
      const that = this
      setTimeout(() => {
        that.otherClass = "new-width"
      }, 1000);
    }
  };
</script>

<style>
.page {
  padding: 60px;
  align-items: center;
}
.div {
  width: 100px;
  height: 200px;
  background-color: red;
  transition-property: width;
  transition-duration: 2000ms;
  transition-timing-function: ease-in;
  transition-delay: 500ms;
}
.new-width {
  width: 300px;
}
</style>
```
:::

上述 4 个样式属性可简写到一个中，表示当触发 div 的 width 变化后
0.5s，以加速的方式变化至新的 width 值，过渡动画持续 2s：

::: {.language-css .extra-class}
``` language-css
.div {
  transition: width 2000ms ease-in 500ms;
}
```
:::

### [\#](animation-style.html#transition-property-支持的通用样式属性){.header-anchor} transition-property 支持的通用样式属性

JS 应用中 transition-property 支持的通用样式属性列表如下：

                     样式名称                        备注
  ----------------------------------------------- ----------
                       width                          √
                      height                          √
                      opacity                         √
                    visibility                        √
                       color                       暂不支持
                 transform-origin                  暂不支持
                     transform                     暂不支持
                      padding                      暂不支持
       padding-\[left\|top\|right\|bottom\]        暂不支持
                      margin                       暂不支持
        margin-\[left\|top\|right\|bottom\]        暂不支持
                      border                       暂不支持
        border-\[left\|top\|right\|bottom\]        暂不支持
                   border-width                       √
     border-\[left\|top\|right\|bottom\]-width     暂不支持
                   border-color                       √
     border-\[left\|top\|right\|bottom\]-color     暂不支持
                   border-radius                   暂不支持
   border-\[top\|bottom\]-\[left\|right\]-radius   暂不支持
                    background                     暂不支持
                 background-color                     √
                  background-size                  暂不支持
                background-position                   √
                       flex                        暂不支持
                     flex-grow                     暂不支持
                    flex-shrink                    暂不支持
                    flex-basis                     暂不支持
           \[left\|top\|right\|bottom\]            暂不支持
:::

::: page-nav
[ ← [颜色配置](color.html){.prev} ]{.prev} [
[背景图样式](background-img-styles.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[动画样式列表](animation-style.html#动画样式列表 "动画样式列表")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[transform 操作](animation-style.html#transform-操作 "transform 操作")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[transform-origin
操作](animation-style.html#transform-origin-操作 "transform-origin 操作")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[animation-name
属性](animation-style.html#animation-name-属性 "animation-name 属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[\@keyframes
属性](animation-style.html#keyframes-属性 "@keyframes 属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[transition
过渡动画](animation-style.html#transition-过渡动画 "transition 过渡动画")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[transition
使用示例](animation-style.html#transition-使用示例 "transition 使用示例")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[transition-property
支持的通用样式属性](animation-style.html#transition-property-支持的通用样式属性 "transition-property 支持的通用样式属性")
:::
:::
:::

::: global-ui
:::
:::
