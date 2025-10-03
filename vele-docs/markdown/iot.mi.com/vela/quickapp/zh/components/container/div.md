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
    [容器组件](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [div](div.html){.active .sidebar-link aria-current="page"}
    -   [list](list.html){.sidebar-link}
    -   [list-item](list-item.html){.sidebar-link}
    -   [scroll](scroll.html){.sidebar-link}
    -   [stack](stack.html){.sidebar-link}
    -   [swiper](swiper.html){.sidebar-link}
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
# [\#](div.html#div){.header-anchor} div

## [\#](div.html#概述){.header-anchor} 概述

基础容器，用作页面结构的根节点或将内容进行分组。

## [\#](div.html#子组件){.header-anchor} 子组件

支持

## [\#](div.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

## [\#](div.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

## [\#](div.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

## [\#](div.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <div style="flex-direction: row;">
      <text class="item color-1">1</text>
      <text class="item color-2">2</text>
      <text class="item color-3">3</text>
    </div>
  </div>
</template>
<style>
  .page {
    margin: 20px;
    flex-direction: column;
    background-color: white;
  }

  .item {
    height: 100px;
    width: 100px;
    text-align: center;
    margin-right: 10px;
  }
  
  .color-1 {
    background-color: #09ba07;
  }
  
  .color-2 {
    background-color: #f76160;
  }
  
  .color-3 {
    background-color: #0faeff;
  }
</style>
```
:::

![](data:image/png;base64,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)
:::

::: page-nav
[ ← [通用方法](../general/methods.html){.prev} ]{.prev} [
[list](list.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](div.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](div.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](div.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](div.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](div.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](div.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
