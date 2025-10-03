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
    -   [input](input.html){.active .sidebar-link aria-current="page"}
    -   [picker](picker.html){.sidebar-link}
    -   [switch](switch.html){.sidebar-link}
    -   [slider](slider.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](input.html#input){.header-anchor} input

## [\#](input.html#概述){.header-anchor} 概述

提供可交互的界面，接收用户的输入。

## [\#](input.html#子组件){.header-anchor} 子组件

不支持

## [\#](input.html#属性){.header-anchor} 属性

支持[通用属性](../general/properties.html)

  名称      类型                             默认值   必填   描述
  --------- -------------------------------- -------- ------ ---------------------------------------------------------------------------------------------------
  type      button \| checkbox \| radio \|   button   否     支持动态修改
  checked   `<boolean>`                      false    否     当前组件的 checked 状态，type 为 checkbox 时生效，可触发 checked 伪类（checked 伪类样式还未支持）
  name      `<string>`                       \-       否     input 组件名称
  value     `<string>`                       \-       否     input 组件的值

## [\#](input.html#样式){.header-anchor} 样式

支持[通用样式](../general/style.html)

  名称        类型                           默认值                必填   描述
  ----------- ------------------------------ --------------------- ------ -----------------------------------
  color       `<color>`                      rgba(0, 0, 0, 0.87)   否     文本颜色
  font-size   `<length>`                     37.5px                否     文本尺寸
  width       `<length>` \| `<percentage>`   \-                    否     type 为 button 时，默认值为 128px
  height      `<length>` \| `<percentage>`   \-                    否     type 为 button 时，默认值为 70px

## [\#](input.html#事件){.header-anchor} 事件

支持[通用事件](../general/events.html)

  名称     参数                                             描述
  -------- ------------------------------------------------ ---------------------------------------------------------------------
  change   不同 type 参数不同，具体见下方 change 事件参数   input 组件的值、状态发生改变时触发，type 为 button 时无 change 事件

### [\#](input.html#change-事件参数){.header-anchor} change 事件参数

  参数      checkbox   radio   备注
  --------- ---------- ------- ------
  name      √          √       \-
  value     √          √       \-
  checked   √          \-      \-

## [\#](input.html#方法){.header-anchor} 方法

  名称    参数                                         描述
  ------- -------------------------------------------- ---------------------------------------------------------------------
  focus   {focus:true\|false}，focus 不传默认为 true   使组件获得或者失去焦点，可触发 focus 伪类（focus 伪类样式还未支持）

## [\#](input.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div class="page">
    <div class="section">
      <text class="title">input-button 组件</text>
      <input class="button" type="button" value="按钮" @click="onButtonClick" />
      <text>{{ buttonText }}</text>
    </div>
    <div class="section">
      <text class="title">input-checkbox 组件</text>
      <input class="checkbox" type="checkbox" checked="{{ checkboxChecked }}" @change="onCheckboxChange" />
      <text>我的勾选状态: {{ checkboxChecked }}</text>
    </div>
    <div class="section">
      <text class="title">input-radio 组件</text>
      <div>
        <input class="radio" type="radio" name="radio" value="1" checked="{{radioValue === '1'}}" @change="onRadioChange" />
        <input class="radio" type="radio" name="radio" value="2" checked="{{radioValue === '2'}}" @change="onRadioChange" />
        <input class="radio" type="radio" name="radio" value="3" checked="{{radioValue === '3'}}" @change="onRadioChange" />
      </div>
      <text>当前选中第{{ radioValue }}个</text>
    </div>
  </div>
</template>

<script>
  export default {
    private: {
      buttonText: '',
      checkboxChecked: true,
      radioValue: '1'
    },
    onTextChange(e) {
      this.textValue = e.value
    },
    onButtonClick() {
      this.buttonText = '按钮被点击了'
    },
    onCheckboxChange(e) {
      this.checkboxChecked = e.checked
    },
    onRadioChange(e) {
      this.radioValue = e.value
    }
  }
</script>

<style>
  .page {
    flex-direction: column;
    padding: 30px;
    background-color: #ffffff;
  }

  .section {
    flex-direction: column;
    margin-bottom: 30px;
  }

  .title {
    font-weight: bold;
  }

  .button {
    width: 140px;
    height: 50px;
    font-size: 25px;
    color: white;
  }

  .checkbox, .radio {
    width: 40px;
    height: 40px;
    margin-right: 10px;
  }
</style>
```
:::

![](../../../assets/img/input.ad1a9272.gif)
:::

::: page-nav
[ ← [barcode](../basic/barcode.html){.prev} ]{.prev} [
[picker](picker.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[概述](input.html#概述 "概述")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[子组件](input.html#子组件 "子组件")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](input.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[样式](input.html#样式 "样式")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](input.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[change 事件参数](input.html#change-事件参数 "change 事件参数")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[方法](input.html#方法 "方法")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[示例代码](input.html#示例代码 "示例代码")
:::
:::
:::

::: global-ui
:::
:::
