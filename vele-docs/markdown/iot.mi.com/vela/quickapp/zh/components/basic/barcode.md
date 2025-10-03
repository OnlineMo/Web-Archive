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
    -   [progress](progress.html){.sidebar-link}
    -   [marquee](marquee.html){.sidebar-link}
    -   [chart](chart.html){.sidebar-link}
    -   [qrcode](qrcode.html){.sidebar-link}
    -   [barcode](barcode.html){.active .sidebar-link
        aria-current="page"}
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
# [\#](barcode.html#barcode){.header-anchor} barcode[[2+]{.badge .apilevel style="vertical-align:top;" v-15b7b770=""}](../../guide/version/APILevel2.html){.apilevel-a} {#barcode}

## [\#](barcode.html#概述){.header-anchor} 概述

条形码，将文本内容转换为条形码展示。

## [\#](barcode.html#子组件){.header-anchor} 子组件

不支持

## [\#](barcode.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

  名称    类型       默认值   必填   描述
  ------- ---------- -------- ------ -------------------------------------------------
  value   `string`   \-       是     条形码内容，码制为Code128码，长度小于等于20字节

## [\#](barcode.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

  名称               类型        默认值    必填   描述
  ------------------ ----------- --------- ------ ----------------
  color              `<color>`   #000000   否     条形码颜色
  background-color   `<color>`   #ffffff   否     条形码背景颜色

::: {.custom-block .warning}
注意

-   当设置transform的rotate属性时，该组件只能旋转为垂直或者水平状态；
-   当设置transform的scale属性时，该组件只能支持整数倍缩放。
:::

## [\#](barcode.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

## [\#](barcode.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
    <barcode value="barcodetest" style="color: #008cff;"></barcode>
  </div>
</template>
```
:::

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASgAAABMCAIAAABRd722AAAACXBIWXMAAA7EAAAOxAGVKw4bAAABOElEQVR4nO3VQQrCMBRAQev9PXNcKCJtlLrxoZ1ZlZB808LDZYxxAr7rXF8Ajkh4EBAeBIQHAeFBQHgQEB4EhAcB4UFAeBAQHgR+L7zlclou94fHymrDq/Xpwcf6mwm3PdsJr+Y8b5ieffOLq217XnN6t50TVsc/ev3phO3z9lNMr3covxce/AHhQUB4EBAeBIQHAeFBQHgQEB4EhAcB4UFAeBAQHgSEBwHhQUB4EBAeBIQHAeFBQHgQEB4EhAcB4UFAeBAQHgSEBwHhQUB4EBAeBIQHAeFBQHgQEB4EhAcB4UFAeBAQHgSEBwHhQUB4EBAeBIQHAeFBQHgQEB4EhAcB4UFAeBAQHgSWMUZ9Bzgc/3gQEB4EhAcB4UFAeBAQHgSEBwHhQUB4EBAeBIQHAeFBQHgQEB4Erhf9L51U2f+gAAAAAElFTkSuQmCC)
:::

::: page-nav
[ ← [qrcode](qrcode.html){.prev} ]{.prev} [ [input](../form/input.html)
→ ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](barcode.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](barcode.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](barcode.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](barcode.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](barcode.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](barcode.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
