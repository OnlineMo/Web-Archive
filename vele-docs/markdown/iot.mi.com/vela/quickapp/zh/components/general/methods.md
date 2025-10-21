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

-   [简体中文](methods.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/general/methods.html){.nav-link}
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

-   [简体中文](methods.html){.nav-link .router-link-exact-active
    .router-link-active aria-current="page"}
-   [English](https://iot.mi.com/vela/quickapp/en/components/general/methods.html){.nav-link}
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
    -   [通用事件](events.html){.sidebar-link}
    -   [通用方法](methods.html){.active .sidebar-link
        aria-current="page"}
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
# [\#](methods.html#通用方法){.header-anchor} 通用方法

通用方法，是所有组件都可以调用的方法。在组件使用id标记 id
属性后，开发者可通过this.\$element(\'idName\')获取 dom
节点，再调用通用方法。

通过 this.\$element 获取到的 dom 对象，提供两个 api 供调用：

### [\#](methods.html#getboundingclientrect-object-object){.header-anchor} getBoundingClientRect(Object object)[[2+]{.badge .apilevel style="vertical-align:top;" v-15b7b770=""}](../../guide/version/APILevel2.html){.apilevel-a} {#getboundingclientrect-object-object}

返回元素的大小及其相对于视窗的位置，需要在页面的 onShow
生命周期之后调用。

#### [\#](methods.html#参数){.header-anchor} 参数

Object object

  属性       类型       默认值   必填   描述
  ---------- ---------- -------- ------ --------------------------------------------------
  success    function            否     接口调用成功的回调函数
  fail       function            否     接口调用失败的回调函数
  complete   function            否     接口调用结束的回调函数（调用成功、失败都会执行）

#### [\#](methods.html#object-success-回调函数参数说明){.header-anchor} object.success 回调函数参数说明 {#object-success-回调函数参数说明}

Object rect

  属性     类型     描述
  -------- -------- ------------------
  left     number   元素的左边界坐标
  right    number   元素的右边界坐标
  top      number   元素的上边界坐标
  bottom   number   元素的下边界坐标
  width    number   元素的宽度
  height   number   元素的高度

#### [\#](methods.html#代码示例){.header-anchor} 代码示例

::: {.language-html .extra-class}
``` language-html
<template>
  <div>
    <div id="box1" class="box-normal"></div>
    <div id="box2" class="box-normal"></div>
  </div>
</template>
<script>
  export default {
    onShow(){
      this.$element('box1').getBoundingClientRect({
        success: function(data) {
          const { top, bottom, left, right, width, height } = data;
          console.log(data);
        },
        fail: (errorData, errorCode) => {
          console.log(`错误原因：${JSON.stringify(errorData)}, 错误代码：${errorCode}`)
        },
        complete: function() {
          console.info('complete')
        }
      })
    }
  }
</script>
```
:::

### [\#](methods.html#focus-object-object){.header-anchor} focus(Object object) {#focus-object-object}

使组件获得或者失去焦点的方法

#### [\#](methods.html#参数-2){.header-anchor} 参数 {#参数-2}

  属性    类型      默认值   必填   描述
  ------- --------- -------- ------ -------------------------------------------------------------------------------
  focus   boolean   true     否     使组件获得或者失去焦点，聚焦时可触发 focus 伪类效果（focus 伪类样式还未支持）

#### [\#](methods.html#代码示例-2){.header-anchor} 代码示例 {#代码示例-2}

::: {.language-html .extra-class}
``` language-html
<script>
  // 聚焦效果
  this.$element('box1').focus();
  // 聚焦效果
  this.$element('box2').focus({focus:true});
  // 失焦效果
  this.$element('box3').focus({focus:false});
</script>
```
:::
:::

::: page-nav
[ ← [通用事件](events.html){.prev} ]{.prev} [
[div](../container/div.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h3 .active}
[getBoundingClientRect(Object
object)](methods.html#getboundingclientrect-object-object "getBoundingClientRect(Object object)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[focus(Object
object)](methods.html#focus-object-object "focus(Object object)")
:::
:::
:::

::: global-ui
:::
:::
