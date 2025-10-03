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
    [通用规范](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [通用样式](style.html){.sidebar-link}
    -   [颜色配置](color.html){.sidebar-link}
    -   [动画样式](animation-style.html){.sidebar-link}
    -   [背景图样式](background-img-styles.html){.sidebar-link}
    -   [通用属性](properties.html){.active .sidebar-link
        aria-current="page"}
    -   [通用事件](events.html){.sidebar-link}
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
# [\#](properties.html#通用属性){.header-anchor} 通用属性

通用属性，即所有组件都支持的属性。

开发者可以在所有的组件标签上都使用`通用属性`。

## [\#](properties.html#示例代码){.header-anchor} 示例代码

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
      <text id="text1" class="text-normal">line 1</text>
      <text id="text2" class="text-normal red">line 2</text>
  </div>
</template>
```
:::

## [\#](properties.html#常规属性){.header-anchor} 常规属性

  名称    类型         默认值   描述
  ------- ------------ -------- ------------
  id      `<string>`   \-       唯一标识
  style   `<string>`   \-       样式声明
  class   `<string>`   \-       引用样式表

## [\#](properties.html#渲染属性){.header-anchor} 渲染属性

  名称   类型          默认值   描述
  ------ ------------- -------- ------------------------------------------------------------------------------
  for    `<array>`     \-       根据数据列表，循环展开当前标签
  if     `<boolean>`   \-       根据数据 boolean 值，添加或移除当前标签
  show   `<boolean>`   \-       根据数据 boolean 值，显示或隐藏当前标签，相当于控制{ display: flex \| none }

渲染属性工作方式详见[template
模板](../../guide/framework/template/index.html)。

::: {.custom-block .warning}
注意

属性和样式不能混用，不能在属性字段中进行样式设置。
:::

## [\#](properties.html#data-属性){.header-anchor} data 属性

给组件绑定 data 属性，然后运行时通过 `dataset` 获取，方便进一步判断。

**示例：**

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
    <div id="elNode1" data-person-name="Jack"></div>
  </div>
</template>

<script>
  export default {
    onReady () {
      const el = this.$element('elNode1')
      const elData = el.dataset.personName
      console.info(`输出data属性： ${elData}`)
    }
  }
</script>
```
:::
:::

::: page-nav
[ ← [背景图样式](background-img-styles.html){.prev} ]{.prev} [
[通用事件](events.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[示例代码](properties.html#示例代码 "示例代码")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[常规属性](properties.html#常规属性 "常规属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[渲染属性](properties.html#渲染属性 "渲染属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[data 属性](properties.html#data-属性 "data 属性")
:::
:::
:::

::: global-ui
:::
:::
