::: {#app server-rendered="true"}
::: theme-container
::: navbar
::: sidebar-button
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiByb2xlPSJpbWciIHZpZXdib3g9IjAgMCA0NDggNTEyIiBjbGFzcz0iaWNvbiI+PHBhdGggZmlsbD0iY3VycmVudENvbG9yIiBkPSJNNDM2IDEyNEgxMmMtNi42MjcgMC0xMi01LjM3My0xMi0xMlY4MGMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6Ij48L3BhdGg+PC9zdmc+){.icon}
:::

[![Xiaomi Vela JS 应用开发文档](../../logo.png){.logo} [Xiaomi Vela JS
应用开发文档]{.site-name
.can-hide}](https://iot.mi.com/vela/quickapp/){.home-link
.router-link-active}

::: links
::: search-box
:::

::: nav-item
[教程](../guide/version/APILevel4.html){.nav-link}
:::

::: nav-item
[组件](index.html){.nav-link .router-link-exact-active
.router-link-active aria-current="page"}
:::

::: nav-item
[JS接口](../features/index.html){.nav-link}
:::

::: nav-item
[编程示例](../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../tools/index.html){.nav-link}
:::
:::
:::

::: sidebar-mask
:::

::: nav-item
[教程](../guide/version/APILevel4.html){.nav-link}
:::

::: nav-item
[组件](index.html){.nav-link .router-link-exact-active
.router-link-active aria-current="page"}
:::

::: nav-item
[JS接口](../features/index.html){.nav-link}
:::

::: nav-item
[编程示例](../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../tools/index.html){.nav-link}
:::

-   ::: {.section .sidebar-group .depth-0}
    [通用规范](general/index.html){.sidebar-heading .clickable .open}
    -   [通用样式](general/style.html){.sidebar-link}
    -   [颜色配置](general/color.html){.sidebar-link}
    -   [动画样式](general/animation-style.html){.sidebar-link}
    -   [背景图样式](general/background-img-styles.html){.sidebar-link}
    -   [通用属性](general/properties.html){.sidebar-link}
    -   [通用事件](general/events.html){.sidebar-link}
    -   [通用方法](general/methods.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [容器组件](container/index.html){.sidebar-heading .clickable}
    -   [div](container/div.html){.sidebar-link}
    -   [list](container/list.html){.sidebar-link}
    -   [list-item](container/list-item.html){.sidebar-link}
    -   [scroll](container/scroll.html){.sidebar-link}
    -   [stack](container/stack.html){.sidebar-link}
    -   [swiper](container/swiper.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [基础组件](basic/index.html){.sidebar-heading .clickable}
    -   [text](basic/text.html){.sidebar-link}
    -   [span](basic/span.html){.sidebar-link}
    -   [a](basic/a.html){.sidebar-link}
    -   [image](basic/image.html){.sidebar-link}
    -   [image-animator](basic/image-animator.html){.sidebar-link}
    -   [progress](basic/progress.html){.sidebar-link}
    -   [marquee](basic/marquee.html){.sidebar-link}
    -   [chart](basic/chart.html){.sidebar-link}
    -   [qrcode](basic/qrcode.html){.sidebar-link}
    -   [barcode](basic/barcode.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [表单组件](form/index.html){.sidebar-heading .clickable}
    -   [input](form/input.html){.sidebar-link}
    -   [picker](form/picker.html){.sidebar-link}
    -   [switch](form/switch.html){.sidebar-link}
    -   [slider](form/slider.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](index.html#组件){.header-anchor} 组件

组件分为预定义组件和自定义组件。

预定义组件是框架预先定义好、由框架实现渲染和逻辑的组件，例如开发页面时开发者必须用到的
text、div，这些组件是由平台 Native 底层渲染出来的。

如果开发一个复杂的页面，开发者把所有的 UI
部分写在一个文件的`<template>`，那代码的可维护性将会很低，并且模块之间容易产生不必要的耦合关系，为了更好地组织逻辑与代码，可以把页面按照功能拆成多个模块，每个模块负责其中的一个功能部分，最后页面将这些模块引入管理起来，传递业务与配置数据完成代码分离，那么这就是自定义组件的意义。

[自定义组件](../guide/framework/template/component.html)是一个开发者编写的组件，使用起来和
Native
组件一样，最终按照组件的`<template>`来渲染；同时开发起来又和页面一样，拥有
ViewModel 实现对数据、事件、方法的管理。

这么来看，页面也是一种特殊的自定义组件，无需引入即可使用，同时服务于整个页面。

本章节主要详细介绍预定义的 Native
组件的用法，包括其支持的样式、属性、事件。
:::
:::
:::

::: global-ui
:::
:::
