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
    -   [div](div.html){.sidebar-link}
    -   [list](list.html){.sidebar-link}
    -   [list-item](list-item.html){.sidebar-link}
    -   [scroll](scroll.html){.sidebar-link}
    -   [stack](stack.html){.sidebar-link}
    -   [swiper](swiper.html){.active .sidebar-link aria-current="page"}
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
# [\#](swiper.html#swiper){.header-anchor} swiper

## [\#](swiper.html#概述){.header-anchor} 概述

滑块视图容器。

## [\#](swiper.html#子组件){.header-anchor} 子组件

支持

## [\#](swiper.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

  名称             类型          默认值   必填   描述
  ---------------- ------------- -------- ------ -----------------------------------------------------
  index            `<number>`    ０       否     当前显示的子组件索引
  autoplay         `<boolean>`   false    否     渲染完成后，是否自动进行播放
  interval         `<number>`    3000ms   否     自动播放时的时间间隔，单位毫秒
  indicator        `<boolean>`   true     否     是否启用 indicator，默认 true
  loop             `<boolean>`   true     否     是否开启循环模式
  duration         `<number>`    \-       否     滑动动画时长（duration默认根据手指的速度动态计算）
  vertical         `<boolean>`   false    否     滑动方向是否为纵向，纵向时indicator 也为纵向
  previousmargin   `<string>`    0px      否     前边距，可用于露出前一项的一小部分，支持单位：px和%
  nextmargin       `<string>`    0px      否     后边距，可用于露出后一项的一小部分，支持单位：px和%
  enableswipe      `<boolean>`   true     否     是否支持手势滑动swiper

**备注**：`previousmargin`和`nextmargin`的总和不应该超过整个swiper大小的1/2，超过部分将会被截取。

## [\#](swiper.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

  名称                                     类型                           默认值                           必填   描述
  ---------------------------------------- ------------------------------ -------------------------------- ------ -----------------------------
  indicator-color                          `<color>`                      rgba(0, 0, 0, 0.5)               否     indicator 填充颜色
  indicator-selected-color                 `<color>`                      #33b4ff 或者 rgb(51, 180, 255)   否     indicator 选中时的颜色
  indicator-size                           `<length>`                     20px                             否     indicator 组件的直径大小
  indicator-\[top\|left\|right\|bottom\]   `<length>` \| `<percentage>`   \-                               否     indicator相对于swiper的位置

## [\#](swiper.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

  名称                                                                                                                            参数                   描述
  ------------------------------------------------------------------------------------------------------------------------------- ---------------------- --------------------------------------------------------------------------------------
  change                                                                                                                          {index:currentIndex}   当前显示的组件索引变化时触发
  swipestart[[2+]{.badge .apilevel style="vertical-align:top;" v-15b7b770=""}](../../guide/version/APILevel2.html){.apilevel-a}   {index:currentIndex}   子组件切换动画开始时触发（如果是手指拖动导致的切换，指的是手指按压开始拖动的时间点）
  swipeend[[2+]{.badge .apilevel style="vertical-align:top;" v-15b7b770=""}](../../guide/version/APILevel2.html){.apilevel-a}     {index:currentIndex}   子组件切换动画结束时触发

## [\#](swiper.html#方法){.header-anchor} 方法

  名称      参数                        描述
  --------- --------------------------- --------------------------
  swipeTo   {index: number(指定位置)}   swiper 滚动到 index 位置

## [\#](swiper.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <swiper class="swiper">
      <text class="item item-1">A</text>
      <text class="item item-2">B</text>
      <text class="item item-3">C</text>
      <text class="item item-4">D</text>
    </swiper>
    
  </div>
</template>

<style>
  .page {
    padding: 30px;
    background-color: white;
  }

  .swiper {
    width: 300px;
    height: 160px;
    indicator-size: 10px;
  }

  .item {
    text-align: center;
    color: white;
    font-size: 30px;
  }

  .item-1 {
    background-color: #3f56ea;
  }

  .item-2 {
    background-color: #00bfc9;
  }

  .item-3 {
    background-color: #47cc47;
  }

  .item-4 {
    background-color: #FF6A00;
  }
</style>
```
:::

![](../../../assets/img/swiper.3d3d5407.gif)
:::

::: page-nav
[ ← [stack](stack.html){.prev} ]{.prev} [ [text](../basic/text.html) →
]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](swiper.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](swiper.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](swiper.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](swiper.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](swiper.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[方法](swiper.html#方法 "方法")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](swiper.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
