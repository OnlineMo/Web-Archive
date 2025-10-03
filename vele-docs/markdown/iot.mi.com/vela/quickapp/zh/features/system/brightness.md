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
[组件](../../components/index.html){.nav-link}
:::

::: nav-item
[JS接口](../index.html){.nav-link .router-link-active}
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
[组件](../../components/index.html){.nav-link}
:::

::: nav-item
[JS接口](../index.html){.nav-link .router-link-active}
:::

::: nav-item
[编程示例](../../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../../tools/index.html){.nav-link}
:::

-   [通用规范](../grammar.html){.sidebar-link}

-   ::: {.section .sidebar-group .depth-0}
    [基本功能](../basic/index.html){.sidebar-heading .clickable}
    -   [应用上下文 app](../basic/app.html){.sidebar-link}
    -   [设备信息 device](../basic/device.html){.sidebar-link}
    -   [页面路由 router](../basic/router.html){.sidebar-link}
    -   [应用配置
        configuration](../basic/configuration.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [网络访问](../network/index.html){.sidebar-heading .clickable}
    -   [数据请求 fetch](../network/fetch.html){.sidebar-link}
    -   [设备通信
        interconnect](../network/interconnect.html){.sidebar-link}
    -   [下载 request](../network/request.html){.sidebar-link}
    -   [上传 uploadtask](../network/uploadtask.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [数据文件](../data/index.html){.sidebar-heading .clickable}
    -   [数据存储 storage](../data/storage.html){.sidebar-link}
    -   [文件存储 file](../data/file.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [系统能力](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [网络信息 network](network.html){.sidebar-link}
    -   [振动 vibrator](vibrator.html){.sidebar-link}
    -   [屏幕亮度 brightness](brightness.html){.active .sidebar-link
        aria-current="page"}
    -   [录音 record](record.html){.sidebar-link}
    -   [地理位置 geolocation](geolocation.html){.sidebar-link}
    -   [传感器 sensor](sensor.html){.sidebar-link}
    -   [事件 event](event.html){.sidebar-link}
    -   [电量信息 battery](battery.html){.sidebar-link}
    -   [解压缩 zip](zip.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [安全](../security/index.html){.sidebar-heading .clickable}
    -   [密码算法 crypto](../security/crypto.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [其他](../other/index.html){.sidebar-heading .clickable}
    -   [音频 audio](../other/audio.html){.sidebar-link}
    -   [弹窗 prompt](../other/prompt.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](brightness.html#屏幕亮度-brightness){.header-anchor} 屏幕亮度 brightness

## [\#](brightness.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.brightness" }
```
:::

## [\#](brightness.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import brightness from '@system.brightness' 
// 或 
const brightness = require('@system.brightness')
```
:::

## [\#](brightness.html#接口定义){.header-anchor} 接口定义

### [\#](brightness.html#brightness-getvalue-object){.header-anchor} brightness.getValue(OBJECT) {#brightness-getvalue-object}

获得当前屏幕亮度值

#### [\#](brightness.html#参数){.header-anchor} 参数：

  参数名     类型       必填   说明
  ---------- ---------- ------ ------------------
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](brightness.html#success-返回值){.header-anchor} success 返回值：

  参数值   类型      说明
  -------- --------- --------------------------
  value    Integer   屏幕亮度，取值范围 0-255

#### [\#](brightness.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
brightness.getValue({
  success: function(data) {
    console.log(`handling success, value = ${data.value}`)
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

### [\#](brightness.html#brightness-setvalue-object){.header-anchor} brightness.setValue(OBJECT) {#brightness-setvalue-object}

设置当前屏幕亮度值

#### [\#](brightness.html#参数-2){.header-anchor} 参数： {#参数-2}

  参数名     类型       必填   说明
  ---------- ---------- ------ --------------------------
  value      Integer    是     屏幕亮度，取值范围 0-255
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](brightness.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
brightness.setValue({
  value: 100,
  success: function() {
    console.log('handling success')
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

### [\#](brightness.html#brightness-getmode-object){.header-anchor} brightness.getMode(OBJECT) {#brightness-getmode-object}

获得当前屏幕亮度模式

#### [\#](brightness.html#参数-3){.header-anchor} 参数： {#参数-3}

  参数名     类型       必填   说明
  ---------- ---------- ------ ------------------
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](brightness.html#success-返回值-2){.header-anchor} success 返回值： {#success-返回值-2}

  参数值   类型      说明
  -------- --------- --------------------------------------------
  mode     Integer   0 为手动调节屏幕亮度，1 为自动调节屏幕亮度

#### [\#](brightness.html#示例-3){.header-anchor} 示例： {#示例-3}

::: {.language-javascript .extra-class}
``` language-javascript
brightness.getMode({
  success: function(data) {
    console.log(`handling success, mode = ${data.mode}`)
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

### [\#](brightness.html#brightness-setmode-object){.header-anchor} brightness.setMode(OBJECT) {#brightness-setmode-object}

设置当前屏幕亮度模式

#### [\#](brightness.html#参数-4){.header-anchor} 参数： {#参数-4}

  参数名     类型       必填   说明
  ---------- ---------- ------ --------------------------------------------
  mode       Integer    是     0 为手动调节屏幕亮度，1 为自动调节屏幕亮度
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](brightness.html#示例-4){.header-anchor} 示例： {#示例-4}

::: {.language-javascript .extra-class}
``` language-javascript
brightness.setMode({
  mode: 1,
  success: function() {
    console.log('handling success')
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

### [\#](brightness.html#brightness-setkeepscreenon-object){.header-anchor} brightness.setKeepScreenOn(OBJECT) {#brightness-setkeepscreenon-object}

设置是否保持常亮状态

#### [\#](brightness.html#参数-5){.header-anchor} 参数： {#参数-5}

  参数名         类型       必填   说明
  -------------- ---------- ------ ------------------
  keepScreenOn   Boolean    是     是否保持屏幕常亮
  success        Function   否     成功回调
  fail           Function   否     失败回调
  complete       Function   否     执行结束后的回调

#### [\#](brightness.html#示例-5){.header-anchor} 示例： {#示例-5}

::: {.language-javascript .extra-class}
``` language-javascript
brightness.setKeepScreenOn({
  keepScreenOn: true,
  success: function() {
    console.log('handling success')
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::
:::

::: page-nav
[ ← [振动 vibrator](vibrator.html){.prev} ]{.prev} [ [录音
record](record.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](brightness.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](brightness.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](brightness.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[brightness.getValue(OBJECT)](brightness.html#brightness-getvalue-object "brightness.getValue(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[brightness.setValue(OBJECT)](brightness.html#brightness-setvalue-object "brightness.setValue(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[brightness.getMode(OBJECT)](brightness.html#brightness-getmode-object "brightness.getMode(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[brightness.setMode(OBJECT)](brightness.html#brightness-setmode-object "brightness.setMode(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[brightness.setKeepScreenOn(OBJECT)](brightness.html#brightness-setkeepscreenon-object "brightness.setKeepScreenOn(OBJECT)")
:::
:::
:::

::: global-ui
:::
:::
