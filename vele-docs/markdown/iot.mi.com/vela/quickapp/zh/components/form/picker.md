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

-   [简体中文](picker.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/form/picker.html){.nav-link}
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

-   [简体中文](picker.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/form/picker.html){.nav-link}
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
    -   [picker](picker.html){.active .sidebar-link aria-current="page"}
    -   [switch](switch.html){.sidebar-link}
    -   [slider](slider.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](picker.html#picker){.header-anchor} picker

## [\#](picker.html#概述){.header-anchor} 概述

滚动选择器，目前支持两种选择器，普通选择器，时间选择器。默认为普通选择器。

## [\#](picker.html#子组件){.header-anchor} 子组件

不支持

## [\#](picker.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

**普通选择器**

  名称       类型              默认值   必填   描述
  ---------- ----------------- -------- ------ ---------------------------------------
  type       text              \-       是     不支持动态修改
  range      `Array<string>`   \-       否     选择器的取值范围
  selected   `<number>`        0        否     选择器的默认取值，取值为 range 的索引

**时间选择器**

  名称       类型         默认值     必填   描述
  ---------- ------------ ---------- ------ --------------------------------
  type       time         \-         是     不支持动态修改
  selected   `<string>`   当前时间   否     选择器的默认取值，格式为 hh:mm

## [\#](picker.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

  名称                        类型         默认值    必填   描述
  --------------------------- ------------ --------- ------ ------------------------
  color                       `<color>`    主题色    否     候选项字体颜色
  font-size                   `<length>`   30px      否     候选项字体尺寸，单位px
  selected-color              `<length>`   #ffffff   否     选中项字体颜色
  selected-font-size          `<length>`   20px      否     选中项字体尺寸，单位px
  selected-background-color   `<color>`    \-        否     选中项背景颜色

## [\#](picker.html#事件){.header-anchor} 事件

**普通选择器**

  名称     参数                                           描述
  -------- ---------------------------------------------- ----------------------------------------------------
  change   {newValue:newValue, newSelected:newSelected}   滚动选择器选择值后确定时触发（newSelected 为索引）

**时间选择器**

  名称     参数                         描述
  -------- ---------------------------- ------------------------------
  change   {hour:hour, minute:minute}   滚动选择器选择值后确定时触发

## [\#](picker.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <text class="title">普通picker</text>
    <picker 
      class="picker" 
      type="text" 
      range="{{pickerList}}" 
      selected="1" 
      onchange="onPickerChange">
    </picker>
    <text class="value">选择的值：{{v1}}</text>

    <text class="title">时间picker</text>
    <picker 
      class="picker" 
      type="time"
      selected="12:00" 
      onchange="onTimePickerChange">
    </picker>
    <text class="value">选择的值：{{v2}}</text>
  </div>
</template>

<script>
  export default {
    private: {
      pickerList: ['apple', 'peach', 'pear', 'banana'],
      v1: 'peach',
      v2: '12:00'
    },
    onPickerChange(e) {
      this.v1 = e.newValue;
    },
    onTimePickerChange(e) {
      this.v2 = e.hour + ':' + e.minute;
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
    color: #000;
  }

  .value {
    margin-top: 5px;
    margin-bottom: 30px;
    color: #090;
  }

  .picker {
    font-size: 25px;
    color: #000;
    selected-font-size: 30px;
    selected-color: #09f;
    selected-background-color: #ccc;
  }
</style>
```
:::

![](../../../images/components/picker.gif)
:::

::: page-nav
[ ← [input](input.html){.prev} ]{.prev} [ [switch](switch.html) →
]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](picker.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](picker.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](picker.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](picker.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](picker.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](picker.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
