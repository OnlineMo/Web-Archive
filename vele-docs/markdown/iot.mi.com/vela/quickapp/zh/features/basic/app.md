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
    [基本功能](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [应用上下文 app](app.html){.active .sidebar-link
        aria-current="page"}
    -   [设备信息 device](device.html){.sidebar-link}
    -   [页面路由 router](router.html){.sidebar-link}
    -   [应用配置 configuration](configuration.html){.sidebar-link}
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
# [\#](app.html#应用上下文-app){.header-anchor} 应用上下文 app

## [\#](app.html#接口声明){.header-anchor} 接口声明

无需声明

## [\#](app.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import app from '@system.app' 
// 或 
const app = require('@system.app')
```
:::

## [\#](app.html#接口定义){.header-anchor} 接口定义

### [\#](app.html#app-getinfo){.header-anchor} app.getInfo() {#app-getinfo}

获取当前应用信息

#### [\#](app.html#参数){.header-anchor} 参数：

无

#### [\#](app.html#返回值){.header-anchor} 返回值：

  参数名        类型      说明
  ------------- --------- --------------
  packageName   String    应用包名
  icon          String    应用图标路径
  name          String    应用名称
  versionName   String    应用版本名称
  versionCode   Integer   应用版本号
  logLevel      String    log 级别
  source        Object    应用来源

#### [\#](app.html#source){.header-anchor} source

  参数名        类型     说明
  ------------- -------- ------------------------------------------------------------------------------
  packageName   String   来源 app 的包名，一级来源
  type          String   来源类型，二级来源，值为 shortcut、push、url、barcode、nfc、bluetooth、other

#### [\#](app.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
console.log(JSON.stringify(app.getInfo()))
```
:::

::: {.language-json .extra-class}
``` language-json
// console 值打印
{
  // 应用包名
  "packageName": "com.example.demo",
  // 应用名称
  "name": "demo",
  // 应用版本名称
  "versionName": "1.0.0",
  // 应用版本号
  "versionCode": 1,
  // 应用图片
  "icon": "/common/logo.png",
  // log 级别
  "logLevel": "debug",
  // 应用来源
  "source": {
    // 来源app的包名
    "packageName": "",
    // 来源类型
    "type": "shortcut"
  }
}
```
:::

### [\#](app.html#app-terminate){.header-anchor} app.terminate() {#app-terminate}

退出当前应用

#### [\#](app.html#参数-2){.header-anchor} 参数： {#参数-2}

无

#### [\#](app.html#返回值-2){.header-anchor} 返回值： {#返回值-2}

无

#### [\#](app.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
app.terminate()
```
:::

### [\#](app.html#app-caniuse){.header-anchor} app.canIUse()[[3+]{.badge .apilevel style="vertical-align:top;" v-15b7b770=""}](../../guide/version/APILevel3.html){.apilevel-a} {#app-caniuse}

#### [\#](app.html#参数-3){.header-anchor} 参数： {#参数-3}

  类型     描述
  -------- --------------------------
  String   要查询的能力，格式见下方

#### [\#](app.html#返回值-3){.header-anchor} 返回值： {#返回值-3}

  类型      描述
  --------- --------------------
  Boolean   查询的能力是否支持

### [\#](app.html#入参格式){.header-anchor} 入参格式

#### [\#](app.html#查询接口){.header-anchor} 查询接口

::: {.language-javascript .extra-class}
``` language-javascript
// 查询feature下的方法是否支持
'@${featureName}.${method}'
// 查询某个feature是否支持
'@${featureName}'
```
:::

**示例**

::: {.language-javascript .extra-class}
``` language-javascript
import app from '@system.app';

if (app.canIUse('@system.router.push')) {
  // 可以使用方法@system.router.push
}
if (app.canIUse('@system.router')) {
  // 可以使用@system.router接口
}
```
:::

#### [\#](app.html#查询组件){.header-anchor} 查询组件

type取值可以是`'attr'`、`'style'`、`'method'`，分别对应组件的属性、样式、方法。

::: {.language-javascript .extra-class}
``` language-javascript
// 查询组件下的属性、样式、方法是否支持
`${componentName}.${type}.${name}`
// 查询组件是否支持
`${componentName}`
```
:::

**示例**

::: {.language-javascript .extra-class}
``` language-javascript
import app from '@system.app';

if (app.canIUse('scroll')) {
  // 可以使用scroll组件
}
if (app.canIUse('scroll.attr.scroll-x')) {
  // 可以使用scroll组件的scroll-x属性
}
```
:::
:::

::: page-nav
[ ← [通用规范](../grammar.html){.prev} ]{.prev} [ [设备信息
device](device.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](app.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](app.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](app.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[app.getInfo()](app.html#app-getinfo "app.getInfo()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[app.terminate()](app.html#app-terminate "app.terminate()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[app.canIUse()](app.html#app-caniuse "app.canIUse()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[入参格式](app.html#入参格式 "入参格式")
:::
:::
:::

::: global-ui
:::
:::
