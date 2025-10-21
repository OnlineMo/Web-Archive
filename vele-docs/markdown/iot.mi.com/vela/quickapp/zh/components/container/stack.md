::: {#app server-rendered="true"}
::: theme-container
::: navbar
::: sidebar-button
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiByb2xlPSJpbWciIHZpZXdib3g9IjAgMCA0NDggNTEyIiBjbGFzcz0iaWNvbiI+PHBhdGggZmlsbD0iY3VycmVudENvbG9yIiBkPSJNNDM2IDEyNEgxMmMtNi42MjcgMC0xMi01LjM3My0xMi0xMlY4MGMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6Ij48L3BhdGg+PC9zdmc+){.icon}
:::

[![Xiaomi Vela JS 应用](../../../logo.png){.logo} [Xiaomi Vela JS
应用]{.site-name
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

::: nav-item
::: dropdown-wrapper
[选择语言]{.title} []{.arrow .down}

[选择语言]{.title} []{.arrow .right}

-   [简体中文](stack.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/container/stack.html){.nav-link}
:::
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

::: nav-item
::: dropdown-wrapper
[选择语言]{.title} []{.arrow .down}

[选择语言]{.title} []{.arrow .right}

-   [简体中文](stack.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/container/stack.html){.nav-link}
:::
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
    -   [div](div.html){.sidebar-link}
    -   [list](list.html){.sidebar-link}
    -   [list-item](list-item.html){.sidebar-link}
    -   [scroll](scroll.html){.sidebar-link}
    -   [stack](stack.html){.active .sidebar-link aria-current="page"}
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
# [\#](stack.html#stack){.header-anchor} stack

## [\#](stack.html#概述){.header-anchor} 概述

基本容器，子组件排列方式为层叠排列，每个直接子组件按照先后顺序依次堆叠，覆盖前一个子组件。

## [\#](stack.html#子组件){.header-anchor} 子组件

支持

## [\#](stack.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

## [\#](stack.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

## [\#](stack.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

## [\#](stack.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <stack class="stack">
      <div class="box box1"></div>
      <div class="box box2"></div>
      <div class="box box3"></div>
      <div class="box box4"></div>
    </stack>
  </div>
</template>

<style>
  .page {
    padding: 30px;
    background-color: white;
  }

  .box {
    border-radius: 8px;
    width: 100px;
    height: 100px;
  }

  .box1 {
    width: 200px;
    height: 200px;
    background-color: #3f56ea;
  }

  .box2 {
    left: 20px;
    top: 20px;
    background-color: #00bfc9;
  }

  .box3 {
    left: 50px;
    top: 50px;
    background-color: #47cc47;
  }

  .box4 {
    left: 80px;
    top: 80px;
    background-color: #FF6A00;
  }
</style>
```
:::

![](../../../images/components/stack.png)
:::

::: page-nav
[ ← [scroll](scroll.html){.prev} ]{.prev} [ [swiper](swiper.html) →
]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](stack.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](stack.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](stack.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](stack.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](stack.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](stack.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
