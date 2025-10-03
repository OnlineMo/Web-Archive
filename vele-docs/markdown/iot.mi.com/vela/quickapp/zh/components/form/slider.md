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
    [表单组件](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [input](input.html){.sidebar-link}
    -   [picker](picker.html){.sidebar-link}
    -   [switch](switch.html){.sidebar-link}
    -   [slider](slider.html){.active .sidebar-link aria-current="page"}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](slider.html#slider){.header-anchor} slider

## [\#](slider.html#概述){.header-anchor} 概述

滑动选择器

## [\#](slider.html#子组件){.header-anchor} 子组件

不支持

## [\#](slider.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

  名称    类型         默认值   必填   描述
  ------- ------------ -------- ------ ------
  min     `<number>`   ０       否     \-
  max     `<number>`   100      否     \-
  step    `<number>`   1        否     \-
  value   `<number>`   0        否     \-

## [\#](slider.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

  名称                      类型         默认值                            必填   描述
  ------------------------- ------------ --------------------------------- ------ ------------
  color                     `<color>`    #f0f0f0 或者 rgb(240, 240, 240)   否     背景条颜色
  selected-color            `<color>`    #009688 或者 rgb(0, 150, 136)     否     已选择颜色
  block-color               `<color>`    \-                                否     滑块的颜色
  padding-\[left\|right\]   `<length>`   32px                              否     左右边距

## [\#](slider.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

  ----------------------------------------------------------------------------------
  名称                    参数                          描述
  ----------------------- ----------------------------- ----------------------------
  change                  {progress:progressValue,      完成一次拖动后触发的事件\
                          isFromUser:isFromUserValue}   isFromUser说明：\
                                                        该事件是否由于用户拖动触发

  ----------------------------------------------------------------------------------

## [\#](slider.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <text class="title">slider 组件</text>
    <slider class="slider" min="0" max="100" step="10" value="{{ initialSliderValue }}" onchange="onSliderChange"></slider>
    <text>slider的值：{{ sliderValue }}</text>
  </div>
</template>

<script>
  export default {
    private: {
      initialSliderValue: 10,
      sliderValue: null
    },
    onSliderChange (e) {
      this.sliderValue = e.progress
    }
  }
</script>

<style>
  .page {
    flex-direction: column;
    padding: 30px;
    background-color: #ffffff;
  }

  .title {
    font-weight: bold;
  }

  .slider {
    margin-top: 20px;
    margin-bottom: 20px;
    padding-left: 0;
    padding-right: 0;
  }
</style>
```
:::

![](../../../assets/img/slider.bd6bc385.gif)
:::

::: page-nav
[ ← [switch](switch.html){.prev} ]{.prev}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](slider.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](slider.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](slider.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](slider.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](slider.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](slider.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
