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
    -   [a](a.html){.active .sidebar-link aria-current="page"}
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
# [\#](a.html#a){.header-anchor} a

## [\#](a.html#概述){.header-anchor} 概述

超链接（默认不带下划线）

## [\#](a.html#子组件){.header-anchor} 子组件

仅支持[`<span>`](span.html)

## [\#](a.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  名称           类型           默认值         必填           描述
  -------------- -------------- -------------- -------------- ------------------------------------------------------------------------------------------------------------------------------------
  href           `string`       \-             否             支持的格式参见[页面路由](../../features/basic/router.html)中的 uri 参数。\
                                                              额外的：\
                                                              href
                                                              还可以通过"?param1=value1"的方式添加参数，参数可以在页面中通过`this.param1`的方式使用。使用`this.param1`变量时，需要在目标页面中在
                                                              `public`（应用外传参）或 `protected`（应用内传参）下定义 key 名相同的属性\
                                                              示例：\
                                                              `<a href="/about?param1=value1">关于</a>`

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## [\#](a.html#样式){.header-anchor} 样式

支持[text样式](text.html)

支持[通用样式](../general/style.html)

## [\#](a.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

## [\#](a.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
    <a class="link" href="/home">goHome</a>
    <a href="/home">
      <span class="link">使用span子组件</span>
    </a>
  </div>
</template>
```
:::
:::

::: page-nav
[ ← [span](span.html){.prev} ]{.prev} [ [image](image.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](a.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](a.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](a.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](a.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](a.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](a.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
