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
    [通用规范](../general/index.html){.sidebar-heading .clickable}
    -   [通用样式](../general/style.html){.sidebar-link}
    -   [颜色配置](../general/color.html){.sidebar-link}
    -   [动画样式](../general/animation-style.html){.sidebar-link}
    -   [背景图样式](../general/background-img-styles.html){.sidebar-link}
    -   [通用属性](../general/properties.html){.sidebar-link}
    -   [通用事件](../general/events.html){.sidebar-link}
    -   [通用方法](../general/methods.html){.sidebar-link}
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
    [基础组件](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [text](text.html){.sidebar-link}
    -   [span](span.html){.active .sidebar-link aria-current="page"}
    -   [a](a.html){.sidebar-link}
    -   [image](image.html){.sidebar-link}
    -   [image-animator](image-animator.html){.sidebar-link}
    -   [progress](progress.html){.sidebar-link}
    -   [marquee](marquee.html){.sidebar-link}
    -   [chart](chart.html){.sidebar-link}
    -   [qrcode](qrcode.html){.sidebar-link}
    -   [barcode](barcode.html){.sidebar-link}
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
# [\#](span.html#span){.header-anchor} span

## [\#](span.html#概述){.header-anchor} 概述

格式化的文本，只能作为[`<text>`](text.html)、[`<a>`](a.html)和`<span>`的子组件。

## [\#](span.html#子组件){.header-anchor} 子组件

仅支持`<span>`

## [\#](span.html#属性){.header-anchor} 属性

  名称    类型          默认值   必填   描述
  ------- ------------- -------- ------ -----------------------------------------
  id      `<string>`    \-       否     唯一标识
  style   `<string>`    \-       否     样式声明
  class   `<string>`    \-       否     引用样式表
  for     `<array>`     \-       否     根据数据列表，循环展开当前标签
  if      `<boolean>`   \-       否     根据数据 boolean 值，添加或移除当前标签

## [\#](span.html#样式){.header-anchor} 样式

  名称              类型                                默认值                必填   描述
  ----------------- ----------------------------------- --------------------- ------ -----------------------------------------------------------------------------------
  color             `<color>`                           rgba(0, 0, 0, 0.54)   否     文本颜色
  font-size         `<length>`                          30px                  否     文本尺寸
  font-style        normal \| italic                    normal                否     \-
  font-weight       normal \| bold \| `<number>`        normal                否     当前平台仅支持`normal`与`bold`两种效果，当值为数字时，低于`550`为前者，否则为后者
  text-decoration   underline \| line-through \| none   none                  否     \-

## [\#](span.html#事件){.header-anchor} 事件

不支持

## [\#](span.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
    <text>
      <span>I am span,</span>
      <span style="color: #f76160">I am span,</span>
      <span style="color: #f76160;text-decoration: underline;">I am span,</span>
    </text>
  </div>
</template>
```
:::

![](data:image/png;base64,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)
:::

::: page-nav
[ ← [text](text.html){.prev} ]{.prev} [ [a](a.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](span.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](span.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](span.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](span.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](span.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](span.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
