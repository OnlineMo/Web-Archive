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

-   [简体中文](events.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/general/events.html){.nav-link}
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

-   [简体中文](events.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/general/events.html){.nav-link}
:::
:::

-   ::: {.section .sidebar-group .depth-0}
    [通用规范](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [通用样式](style.html){.sidebar-link}
    -   [颜色配置](color.html){.sidebar-link}
    -   [动画样式](animation-style.html){.sidebar-link}
    -   [背景图样式](background-img-styles.html){.sidebar-link}
    -   [通用属性](properties.html){.sidebar-link}
    -   [通用事件](events.html){.active .sidebar-link
        aria-current="page"}
    -   [通用方法](methods.html){.sidebar-link}
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
    [表单组件](../form/index.html){.sidebar-heading .clickable}
    -   [input](../form/input.html){.sidebar-link}
    -   [picker](../form/picker.html){.sidebar-link}
    -   [switch](../form/switch.html){.sidebar-link}
    -   [slider](../form/slider.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](events.html#通用事件){.header-anchor} 通用事件

通用事件，即所有组件都支持的`事件回调`。

开发者可以在组件标签上使用`on{eventName}`（如`onclick`）或`@{eventName}`（如`@click`）注册回调事件。

更详细的讲解，可查阅[事件绑定](../../guide/framework/template/event.html)文档了解。

## [\#](events.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
      <text onclick="clickFunction1">line 1</text>
      <text @click="clickFunction2">line 2</text>
  </div>
</template>
```
:::

## [\#](events.html#通用事件列表){.header-anchor} 通用事件列表

  ---------------------------------------------------------------------------------------------------------------
  名称              参数              描述                                                      冒泡
  ----------------- ----------------- --------------------------------------------------------- -----------------
  touchstart        TouchEvent        手指刚触摸组件时触发                                      支持

  touchmove         TouchEvent        手指触摸后移动时触发                                      支持

  touchend          TouchEvent        手指触摸动作结束时触发                                    支持

  click             MouseEvent        组件被点击时触发                                          支持

  longpress         MouseEvent        组件被长按时触发                                          支持

  swipe             { direction:      组件上快速滑动后触发（滑动方向有滚动条时不触发该事件）\   不支持
                    \<`"left"` \|     参数说明：\                                               
                    `"right"` \|      left：　向左滑动；\                                       
                    `"up"` \|         right： 向右滑动；\                                       
                    `"down"`\> }      up：　 向上滑动；\                                        
                                      down：向下滑动；                                          
  ---------------------------------------------------------------------------------------------------------------

## [\#](events.html#事件对象){.header-anchor} 事件对象

### [\#](events.html#_1、touchevent-类型说明){.header-anchor} 1、TouchEvent 类型说明： {#_1、touchevent-类型说明}

  ----------------------------------------------------------------------------------------------------------------------------------------------
  属性                    类型                    说明
  ----------------------- ----------------------- ----------------------------------------------------------------------------------------------
  touches                 TouchList               触摸事件，当前停留在屏幕中的触摸点信息的数组

  changedTouches          TouchList               触摸事件，当前变化的触摸点信息的数组。changedTouches 数据格式同 touches，
                                                  表示有变化的触摸点，如从无变有（touchstart），位置变化（touchmove），从有变无（touchend），\
                                                  比如用户手指离开屏幕时，touches 数组中无数据，而 changedtouches 则会保存离开前的数据
  ----------------------------------------------------------------------------------------------------------------------------------------------

**其中，TouchList 是 Touch 对象的集合。**

### [\#](events.html#_2、touch-类型说明){.header-anchor} 2、Touch 类型说明 {#_2、touch-类型说明}

  --------------------------------------------------------------------------------------------------------------------------------------------------------------
  属性                    类型                    说明
  ----------------------- ----------------------- --------------------------------------------------------------------------------------------------------------
  identifier              number                  触摸点的标识符。对于多点同时触摸则是 \[0,1,2,3,\...\]，分别表示第一个手指、第二个手指\...\
                                                  一次触摸动作(手指按下到手指离开的过程)，在整个屏幕移动过程中，该标识符不变，可以用来判断是否是同一次触摸过程

  clientX                 number                  距离可见区域左边沿的 X 轴坐标，不包含任何滚动偏移

  clientY                 number                  距离可见区域上边沿的 Y 轴坐标，不包含任何滚动偏移以及状态栏和 titlebar 的高度

  pageX                   number                  距离可见区域左边沿的 X 轴坐标，包含任何滚动偏移

  pageY                   number                  距离可见区域上边沿的 Y 轴坐标，包含任何滚动偏移。（不包含状态栏和 titlebar 的高度）

  offsetX                 number                  距离事件触发对象左边沿 X 轴的距离

  offsetY                 number                  距离事件触发对象上边沿 Y 轴的距离
  --------------------------------------------------------------------------------------------------------------------------------------------------------------

### [\#](events.html#_3、mouseevent-类型说明){.header-anchor} 3、MouseEvent 类型说明 {#_3、mouseevent-类型说明}

  属性      类型     说明
  --------- -------- -------------------------------------------------------------------------------------
  clientX   number   距离可见区域左边沿的 X 轴坐标，不包含任何滚动偏移
  clientY   number   距离可见区域上边沿的 Y 轴坐标，不包含任何滚动偏移以及状态栏和 titlebar 的高度
  pageX     number   距离可见区域左边沿的 X 轴坐标，包含任何滚动偏移
  pageY     number   距离可见区域上边沿的 Y 轴坐标，包含任何滚动偏移。（不包含状态栏和 titlebar 的高度）
  offsetX   number   距离事件触发对象左边沿 X 轴的距离
  offsetY   number   距离事件触发对象上边沿 Y 轴的距离

## [\#](events.html#示例){.header-anchor} 示例

如下，在 div 上绑定了 click 和 touchmove
事件，触发事件时将事件打印出来。

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="root-page">
    <div class="touch-region" onclick="click" ontouchmove="move"></div>
  </div>
</template>

<style>
  .root-page {
    flex-direction: column;
    align-items: center;
  }

  .touch-region {
    width: 80%;
    height: 20%;
    background-color: #444444;
  }

</style>

<script>
  export default {
    private: {},
    click(event) {
      console.log("click event fired")
    },
    move(event) {
      console.log("move event touches:" + JSON.stringify(event.touches))
      console.log("move event changedTouches:" + JSON.stringify(event.changedTouches))
    }
  }

</script>
```
:::

**打印结果如下，click 事件：**

::: {.language-js .extra-class}
``` language-js
move event touches:[
  {
    "offsetX": 296,
    "identifier": 0,
    "offsetY": 113.48148345947266,
    "clientY": 113.48148345947266,
    "clientX": 360,
    "pageY": 113.48148345947266,
    "pageX": 360
  }
]
```
:::

::: {.language-js .extra-class}
``` language-js
move event changedTouches:[
  {
    "offsetX": 296,
    "identifier": 0,
    "offsetY": 113.48148345947266,
    "clientY": 113.48148345947266,
    "clientX": 360,
    "pageY": 113.48148345947266,
    "pageX": 360
  }
]
```
:::

::: {.language- .extra-class}
``` language-text
click event fired
```
:::
:::

::: page-nav
[ ← [通用属性](properties.html){.prev} ]{.prev} [
[通用方法](methods.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[示例代码](events.html#示例代码 "示例代码")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[通用事件列表](events.html#通用事件列表 "通用事件列表")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件对象](events.html#事件对象 "事件对象")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[1、TouchEvent
类型说明：](events.html#_1、touchevent-类型说明 "1、TouchEvent 类型说明：")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[2、Touch 类型说明](events.html#_2、touch-类型说明 "2、Touch 类型说明")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[3、MouseEvent
类型说明](events.html#_3、mouseevent-类型说明 "3、MouseEvent 类型说明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例](events.html#示例 "示例")
:::
:::
:::

::: global-ui
:::
:::
