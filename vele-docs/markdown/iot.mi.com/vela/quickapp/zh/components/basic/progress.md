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
    -   [span](span.html){.sidebar-link}
    -   [a](a.html){.sidebar-link}
    -   [image](image.html){.sidebar-link}
    -   [image-animator](image-animator.html){.sidebar-link}
    -   [progress](progress.html){.active .sidebar-link
        aria-current="page"}
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
# [\#](progress.html#progress){.header-anchor} progress

## [\#](progress.html#概述){.header-anchor} 概述

进度条

## [\#](progress.html#子组件){.header-anchor} 子组件

不支持

## [\#](progress.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

  名称      类型                默认值       必填   描述
  --------- ------------------- ------------ ------ ----------------------------
  percent   `<number>`          0            否     \-
  type      horizontal \| arc   horizontal   否     进度条类型，不支持动态修改

## [\#](progress.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

注：horizontal progress 底色为#f0f0f0；height 属性失效

  名称           类型         默认值                            必填   描述
  -------------- ------------ --------------------------------- ------ ------------------
  color          `<color>`    #33b4ff 或者 rgb(51, 180, 255)    否     进度条的颜色
  stroke-width   `<length>`   32px                              否     进度条的宽度
  layer-color    `<color>`    #f0f0f0 或者 rgb(240, 240, 240)   否     进度条的背景颜色

type=arc时生效：

  名称          类型         默认值                 必填   描述
  ------------- ------------ ---------------------- ------ --------------------------------------------------------------------------------------------
  start-angle   `<deg>`      240                    否     弧形进度条起始角度，以时钟0点为基线。范围为0到360（顺时针）
  total-angle   `<deg>`      240                    否     弧形进度条总长度，范围为-360到360，负数表示起点到终点为逆时针
  center-x      `<length>`   组件宽度的一半         否     弧形进度条中心位置，（坐标原点为组件左上角顶点）。该样式需要和 center-y \\ radius 一起使用
  center-y      `<length>`   组件高度的一半         否     弧形进度条中心位置，（坐标原点为组件左上角顶点）。该样式需要和 center-x \\ radius 一起使用
  radius        `<length>`   组件宽高较小值的一半   否     弧形进度条半径，该样式需要和 center-x \\ center-y 一起使用

## [\#](progress.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

## [\#](progress.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div style="flex-direction: column">
    <progress class="p1" percent="40"></progress> 
    <progress class="p2" percent="80" type="arc"></progress>
  </div>
</template>
<style>
  .p1 {
    margin-bottom: 10px;
    stroke-width: 12px;
  }

  .p2 {
    margin-bottom: 10px;
    stroke-width: 12px;
    start-angle: 0;
    total-angle: 360deg;
  }
</style>
```
:::

![](data:image/png;base64,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)
:::

::: page-nav
[ ← [image-animator](image-animator.html){.prev} ]{.prev} [
[marquee](marquee.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](progress.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](progress.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](progress.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](progress.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](progress.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](progress.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
