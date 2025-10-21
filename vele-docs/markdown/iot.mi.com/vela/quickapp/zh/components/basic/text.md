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

-   [简体中文](text.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/basic/text.html){.nav-link}
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

-   [简体中文](text.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/basic/text.html){.nav-link}
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
    -   [text](text.html){.active .sidebar-link aria-current="page"}
    -   [span](span.html){.sidebar-link}
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
# [\#](text.html#text){.header-anchor} text

## [\#](text.html#概述){.header-anchor} 概述

文本内容写在标签内容区，支持转义字符`"\"`。

## [\#](text.html#子组件){.header-anchor} 子组件

仅支持`<span>`

## [\#](text.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

## [\#](text.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

  名称              类型                                默认值                必填   描述
  ----------------- ----------------------------------- --------------------- ------ -----------------------------------------------------------------------------------
  lines             `<number>`                          -1                    否     文本行数，-1 代表不限定行数
  color             `<color>`                           rgba(0, 0, 0, 0.54)   否     文本颜色
  font-size         `<length>`                          30px                  否     文本尺寸
  font-style        normal \| italic                    normal                否     
  font-weight       normal \| bold \| `<number>`        normal                否     当前平台仅支持`normal`与`bold`两种效果，当值为数字时，低于`550`为前者，否则为后者
  text-decoration   underline \| line-through \| none   none                  否     
  text-align        left \| center \| right             left                  否     
  text-indent       `<length>` \| `<percentage>`        \-                    否     规定文本块首行的缩进
  line-height       `<length>`                          \-                    否     文本行高
  text-overflow     clip \| ellipsis                    clip                  否     在设置了行数的情况下生效

**示例**

-   单行省略

    ::: {.language-css .extra-class}
    ``` language-css
    text {
      width: 150px;
      lines: 1;
      text-overflow: ellipsis;
    }
    ```
    :::

    ![](../../../images/components/text-overflow.png)

-   多行省略，以两行为例

    ::: {.language-css .extra-class}
    ``` language-css
    text {
      width: 100px;
      lines: 2;
      text-overflow: ellipsis;
    }
    ```
    :::

    ![](../../../images/components/text-overflow-2.png)

## [\#](text.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

## [\#](text.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
    <text>这是一段文本</text>
  </div>
</template>
```
:::

![](../../../images/components/text-example.png)
:::

::: page-nav
[ ← [swiper](../container/swiper.html){.prev} ]{.prev} [
[span](span.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](text.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](text.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](text.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](text.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](text.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](text.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
