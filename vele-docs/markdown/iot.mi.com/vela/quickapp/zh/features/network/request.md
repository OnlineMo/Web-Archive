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
    [网络访问](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [数据请求 fetch](fetch.html){.sidebar-link}
    -   [设备通信 interconnect](interconnect.html){.sidebar-link}
    -   [下载 request](request.html){.active .sidebar-link
        aria-current="page"}
    -   [上传 uploadtask](uploadtask.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [数据文件](../data/index.html){.sidebar-heading .clickable}
    -   [数据存储 storage](../data/storage.html){.sidebar-link}
    -   [文件存储 file](../data/file.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [系统能力](../system/index.html){.sidebar-heading .clickable}
    -   [网络信息 network](../system/network.html){.sidebar-link}
    -   [振动 vibrator](../system/vibrator.html){.sidebar-link}
    -   [屏幕亮度 brightness](../system/brightness.html){.sidebar-link}
    -   [录音 record](../system/record.html){.sidebar-link}
    -   [地理位置
        geolocation](../system/geolocation.html){.sidebar-link}
    -   [传感器 sensor](../system/sensor.html){.sidebar-link}
    -   [事件 event](../system/event.html){.sidebar-link}
    -   [电量信息 battery](../system/battery.html){.sidebar-link}
    -   [解压缩 zip](../system/zip.html){.sidebar-link}
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
# [\#](request.html#下载-request){.header-anchor} 下载 request

## [\#](request.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.request" }
```
:::

## [\#](request.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import request from '@system.request' 
// 或 
const request = require('@system.request')
```
:::

## [\#](request.html#接口定义){.header-anchor} 接口定义

### [\#](request.html#request-download-object){.header-anchor} request.download(OBJECT) {#request-download-object}

下载文件

#### [\#](request.html#参数){.header-anchor} 参数：

  参数名     类型       必填   说明
  ---------- ---------- ------ -------------------------------------------------------
  url        String     是     资源 url
  header     String     否     请求的 header，会将其所有属性设置到请求的 header 部分
  filename   String     否     下载文件名。默认从网络请求或 url 中获取
  success    Function   否     成功返回的回调函数
  fail       Function   否     失败的回调函数
  complete   Function   否     结束的回调函数（调用成功、失败都会执行）

#### [\#](request.html#success-返回值){.header-anchor} success 返回值：

  参数名   类型     说明
  -------- -------- -----------------------------------------
  token    String   下载的 token，根据此 token 获取下载状态

#### [\#](request.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
request.download({
  url: 'http://www.example.com',
  success: function(data) {
    console.log(`handling success${data.token}`)
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

### [\#](request.html#request-ondownloadcomplete-object){.header-anchor} request.onDownloadComplete(OBJECT) {#request-ondownloadcomplete-object}

监听下载任务

#### [\#](request.html#参数-2){.header-anchor} 参数： {#参数-2}

  参数名     类型       必填   说明
  ---------- ---------- ------ ------------------------------------------
  token      String     是     download 接口返回的 token
  success    Function   否     成功返回的回调函数
  fail       Function   否     失败的回调函数
  complete   Function   否     结束的回调函数（调用成功、失败都会执行）

#### [\#](request.html#success-返回值-2){.header-anchor} success 返回值： {#success-返回值-2}

  参数名   类型     说明
  -------- -------- -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  uri      String   下载文件的 Uri（默认情况下该文件处于应用缓存目录。如果文件类型为图片或者视频且要求用户可以在相册等应用内查看，则需要将该文件转存至公共目录，参考media接口中的方法实现即可）

#### [\#](request.html#fail-返回错误代码){.header-anchor} fail 返回错误代码：

  错误码   说明
  -------- ----------------
  1000     下载失败
  1001     下载任务不存在

#### [\#](request.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
request.onDownloadComplete({
  token: '123',
  success: function(data) {
    console.log(`handling success${data.uri}`)
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

## [\#](request.html#支持明细){.header-anchor} 支持明细

  设备产品                   说明
  -------------------------- --------
  小米 S1 Pro 运动健康手表   支持
  小米手环 8 Pro             不支持
  Xiaomi Watch S3            支持
  Redmi Watch 4              不支持
  小米腕部心电血压记录仪     不支持
  Xiaomi Watch S4            支持
  REDMI Watch 5              支持
:::

::: page-nav
[ ← [设备通信 interconnect](interconnect.html){.prev} ]{.prev} [ [上传
uploadtask](uploadtask.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](request.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](request.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](request.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[request.download(OBJECT)](request.html#request-download-object "request.download(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[request.onDownloadComplete(OBJECT)](request.html#request-ondownloadcomplete-object "request.onDownloadComplete(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[支持明细](request.html#支持明细 "支持明细")
:::
:::
:::

::: global-ui
:::
:::
