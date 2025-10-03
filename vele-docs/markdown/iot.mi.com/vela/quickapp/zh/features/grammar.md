::: {#app server-rendered="true"}
::: theme-container
::: navbar
::: sidebar-button
![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiByb2xlPSJpbWciIHZpZXdib3g9IjAgMCA0NDggNTEyIiBjbGFzcz0iaWNvbiI+PHBhdGggZmlsbD0iY3VycmVudENvbG9yIiBkPSJNNDM2IDEyNEgxMmMtNi42MjcgMC0xMi01LjM3My0xMi0xMlY4MGMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6bTAgMTYwSDEyYy02LjYyNyAwLTEyLTUuMzczLTEyLTEydi0zMmMwLTYuNjI3IDUuMzczLTEyIDEyLTEyaDQyNGM2LjYyNyAwIDEyIDUuMzczIDEyIDEydjMyYzAgNi42MjctNS4zNzMgMTItMTIgMTJ6Ij48L3BhdGg+PC9zdmc+){.icon}
:::

[![Xiaomi Vela JS 应用开发文档](../../logo.png){.logo} [Xiaomi Vela JS
应用开发文档]{.site-name
.can-hide}](https://iot.mi.com/vela/quickapp/){.home-link
.router-link-active}

::: links
::: search-box
:::

::: nav-item
[教程](../guide/version/APILevel4.html){.nav-link}
:::

::: nav-item
[组件](../components/index.html){.nav-link}
:::

::: nav-item
[JS接口](index.html){.nav-link .router-link-active}
:::

::: nav-item
[编程示例](../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../tools/index.html){.nav-link}
:::
:::
:::

::: sidebar-mask
:::

::: nav-item
[教程](../guide/version/APILevel4.html){.nav-link}
:::

::: nav-item
[组件](../components/index.html){.nav-link}
:::

::: nav-item
[JS接口](index.html){.nav-link .router-link-active}
:::

::: nav-item
[编程示例](../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../tools/index.html){.nav-link}
:::

-   [通用规范](grammar.html){.active .sidebar-link aria-current="page"}
    -   [接口声明](grammar.html#接口声明){.sidebar-link}
    -   [导入模块](grammar.html#导入模块){.sidebar-link}
    -   [接口 api 调用](grammar.html#接口-api-调用){.sidebar-link}
    -   [通用错误码](grammar.html#通用错误码){.sidebar-link}

-   ::: {.section .sidebar-group .depth-0}
    [基本功能](basic/index.html){.sidebar-heading .clickable}
    -   [应用上下文 app](basic/app.html){.sidebar-link}
    -   [设备信息 device](basic/device.html){.sidebar-link}
    -   [页面路由 router](basic/router.html){.sidebar-link}
    -   [应用配置
        configuration](basic/configuration.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [网络访问](network/index.html){.sidebar-heading .clickable}
    -   [数据请求 fetch](network/fetch.html){.sidebar-link}
    -   [设备通信
        interconnect](network/interconnect.html){.sidebar-link}
    -   [下载 request](network/request.html){.sidebar-link}
    -   [上传 uploadtask](network/uploadtask.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [数据文件](data/index.html){.sidebar-heading .clickable}
    -   [数据存储 storage](data/storage.html){.sidebar-link}
    -   [文件存储 file](data/file.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [系统能力](system/index.html){.sidebar-heading .clickable}
    -   [网络信息 network](system/network.html){.sidebar-link}
    -   [振动 vibrator](system/vibrator.html){.sidebar-link}
    -   [屏幕亮度 brightness](system/brightness.html){.sidebar-link}
    -   [录音 record](system/record.html){.sidebar-link}
    -   [地理位置 geolocation](system/geolocation.html){.sidebar-link}
    -   [传感器 sensor](system/sensor.html){.sidebar-link}
    -   [事件 event](system/event.html){.sidebar-link}
    -   [电量信息 battery](system/battery.html){.sidebar-link}
    -   [解压缩 zip](system/zip.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [安全](security/index.html){.sidebar-heading .clickable}
    -   [密码算法 crypto](security/crypto.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [其他](other/index.html){.sidebar-heading .clickable}
    -   [音频 audio](other/audio.html){.sidebar-link}
    -   [弹窗 prompt](other/prompt.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](grammar.html#通用语法){.header-anchor} 通用语法

框架提供各种接口来获取应用的基本信息或者调用系统能力，每个接口包含若干
api
来执行具体的任务。接口使用前需要进行接口声明、模块导入，然后才能调用该接口下定义的若干
api。

## [\#](grammar.html#接口声明){.header-anchor} 接口声明

在 manifest.json 文件的 features 字段下进行声明，例如：

::: {.language-javascript .extra-class}
``` language-javascript
[{ "name": "system.network" }]
```
:::

## [\#](grammar.html#导入模块){.header-anchor} 导入模块

使用接口前，需要在代码里导入接口模块，例如：

::: {.language-javascript .extra-class}
``` language-javascript
import network from '@system.network'
// 或
const network = require('@system.network')
```
:::

## [\#](grammar.html#接口-api-调用){.header-anchor} 接口 api 调用

接口提供的 api 的调用方式大概有以下几种：

-   同步 api
-   异步 api
-   订阅类 api

### [\#](grammar.html#同步-api-调用){.header-anchor} 同步 api 调用

如果 api 没有返回值，一般会定义成同步 api，直接调用即可，例如：

::: {.language-javascript .extra-class}
``` language-javascript
audio.play()
```
:::

### [\#](grammar.html#异步-api-调用){.header-anchor} 异步 api 调用

如果 api 有返回值，一般会定义成异步 api 的形式，这类 api
除了普通参数，还有"success \\ fail \\
complete"这三个通用参数------分别是 api 执行"成功 \\ 失败 \\
完成"后的回调方法，调用时可以传入这三个参数来获取 api
执行成功的返回值或进行执行失败 \\
完成后的处理，这三个通用参数的说明如下：

  名称       方法参数   参数类型   参数值                                                                                         说明
  ---------- ---------- ---------- ---------------------------------------------------------------------------------------------- --------------------
  success    data       any        api 执行的返回值，详见接口使用文档                                                             api 执行成功后触发
  fail       data       any        api 执行错误信息内容，一般是字符串，也可能是其他类型，详见接口使用文档                         api 执行失败后触发
             code       number     api 执行错误码，详见[通用错误码](grammar.html#%E9%80%9A%E7%94%A8%E9%94%99%E8%AF%AF%E7%A0%81)   
  complete   \-         \-         \-                                                                                             api 执行完成后触发

代码示例：

::: {.language-javascript .extra-class}
``` language-javascript
storage.get({
  key: 'A1',
  success: function(data) {
    console.log('handling success')
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

### [\#](grammar.html#订阅-取消订阅-api){.header-anchor} 订阅 / 取消订阅 api

订阅类 api 不会立即返回结果，这类 api
需要开发者传入回调函数作为参数，该回调函数会在 api
完成时或者事件变化时被触发，可以执行多次。该通用回调函数参数说明如下：

  名称      方法参数   参数类型   参数值                                                                                         说明
  --------- ---------- ---------- ---------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------
  success   data       any        api 执行的返回值，详见接口使用文档                                                             api 调用成功或事件变更时触发，可能会触发多次
  fail      data       any        错误信息内容，一般是字符串，也可能是其他类型，详见接口使用文档                                 api 执行失败时触发。一旦触发该回调函数，success不会再次被调用，接口调用结束
            code       number     api 执行错误码，详见[通用错误码](grammar.html#%E9%80%9A%E7%94%A8%E9%94%99%E8%AF%AF%E7%A0%81)   

代码示例：

::: {.language-javascript .extra-class}
``` language-javascript
geolocation.subscribe({
  success: function(data) {
    console.log(
      `handling success: longitude = ${data.longitude}, latitude = ${
        data.latitude
      }`
    )
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

## [\#](grammar.html#通用错误码){.header-anchor} 通用错误码

所有接口的 api 在执行出现错误时，会返回统一定义的通用错误码或者 api
自己定义的特殊错误码。这里对通用错误码进行说明如下：

  code   定义
  ------ ----------------------------------------------------------------------
  200    系统通用错误，所有系统未知异常发生时抛出。比如框架申请内存空间失败等
  202    参数错误，调用时未按照 api 定义进行正确的传参
  203    该功能不支持
  204    请求超时
  300    I/O 错误
:::

::: page-nav
[ [应用上下文 app](basic/app.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](grammar.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](grammar.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口 api 调用](grammar.html#接口-api-调用 "接口 api 调用")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[同步 api 调用](grammar.html#同步-api-调用 "同步 api 调用")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[异步 api 调用](grammar.html#异步-api-调用 "异步 api 调用")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[订阅 / 取消订阅
api](grammar.html#订阅-取消订阅-api "订阅 / 取消订阅 api")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[通用错误码](grammar.html#通用错误码 "通用错误码")
:::
:::
:::

::: global-ui
:::
:::
