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
    -   [list](list.html){.active .sidebar-link aria-current="page"}
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
# [\#](list.html#list){.header-anchor} list

## [\#](list.html#概述){.header-anchor} 概述

列表视图容器，包含一系列相同结构的列表项，连续、多行呈现同类数据。

## [\#](list.html#子组件){.header-anchor} 子组件

仅支持[`<list-item>`](list-item.html)

## [\#](list.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

  名称      类型          默认值   必填   描述
  --------- ------------- -------- ------ --------------
  bounces   `<boolean>`   false    否     是否边界回弹

## [\#](list.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

使用时需要显式地设置高度。

## [\#](list.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

  --------------------------------------------------------------------------------
  名称                    参数                    描述
  ----------------------- ----------------------- --------------------------------
  scroll                  {scrollX: `<number>`,   列表滑动；\
                          scrollY: `<number>`,    stateValue 取值说明：\
                          scrollState:            0：list停止滑动\
                          `<stateValue>`}         1：list正在通过用户的手势滑动\
                                                  2：list正在滑动，用户已松手

  scrollbottom            \-                      列表滑动到底部

  scrolltop               \-                      列表滑动到顶部

  scrollend               \-                      列表滑动结束

  scrolltouchup           \-                      列表滑动过程中手指抬起
  --------------------------------------------------------------------------------

## [\#](list.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <list class="list" bounces="true" 
      onscroll="onScroll" 
      onscrolltop="onScrollTop" 
      onscrollbottom="onScrollBottom"
      onscrolltouchup="onScrollTouchup">
      <list-item for="{{productList}}" class="item" type="item">
        <text>{{$item.name}}: {{$item.price}}</text>
      </list-item>
    </list>
  </div>
</template>

<script>
  export default {
    private: {
      productList: [
        { name: '衣服', price: '100' },
        { name: '裤子', price: '200' },
        { name: '鞋子', price: '300' },
        { name: '帽子', price: '60' },
        { name: '雨伞', price: '300' },
        { name: '书包', price: '60' },
        { name: '书本', price: '30' }
      ],
    },
    onScroll(e) {
      console.log('### list onScroll evt: ', e)
    },
    onScrollTop(e) {
      console.log('### list onScrollTop evt: ', e)
    },
    onScrollBottom(e) {
      console.log('### list onScrollBottom evt: ', e)
    },
    onScrollTouchup(e) {
      console.log('### list onScrollTouchup evt: ', e)
    }
  }
</script>

<style>
  .page {
    justify-content: center;
    align-items: center;
    background-color: #000;
  }

  .list {
    width: 300px;
    height: 200px;
    border: 1px solid #fff;
  }

  text {
   color: #fff;
  }
  .item {
    height: 40px;
    width: 100%;
    align-items: center;
    justify-content: center;
    border: 1px solid #fff;
  }
</style>
```
:::

### [\#](list.html#效果展示){.header-anchor} 效果展示

![](../../../assets/img/list-methods.c5e943f3.jpeg)

## [\#](list.html#方法){.header-anchor} 方法

  名称       参数     描述
  ---------- -------- ----------------------------
  scrollTo   Object   list 滚动到指定 item 位置
  scrollBy   Object   使 list 的内容滑动一定距离

**scrollTo 的参数说明：**

  名称       类型                      默认值   必填   描述
  ---------- ------------------------- -------- ------ -----------------------------------------------------------------------------------------------
  index      number                    0        否     list 滚动的目标 item 位置
  behavior   smooth / instant / auto   auto     否     是否平滑滑动，支持参数 smooth (平滑滚动)，instant (瞬间滚动)，默认值 auto，效果等同于 instant

**scrollBy 的参数说明：**

  名称       类型                      默认值   必填   描述
  ---------- ------------------------- -------- ------ ----------------------------------------------------------------------------------------------------------------------------
  left       number                    0        否     从当前位置水平方向滑动距离，单位 px。值为正时向左滑动，为负时向右滑动。flex-direction 为 column 或 column-reverse 时不生效
  top        number                    0        否     从当前位置垂直方向滑动距离，单位 px。值为正时向上滑动，为负时向下滑动。flex-direction 为 row 或 row-reverse 时不生效
  behavior   smooth / instant / auto   auto     否     是否平滑滑动，支持参数 smooth (平滑滚动)，instant (瞬间滚动)，默认值 auto，效果等同于 instant
:::

::: page-nav
[ ← [div](div.html){.prev} ]{.prev} [ [list-item](list-item.html) →
]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](list.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](list.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](list.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](list.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](list.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](list.html#示例代码 "示例代码")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[效果展示](list.html#效果展示 "效果展示")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[方法](list.html#方法 "方法")
:::
:::
:::

::: global-ui
:::
:::
