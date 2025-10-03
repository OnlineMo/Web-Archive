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
    -   [振动 vibrator](vibrator.html){.active .sidebar-link
        aria-current="page"}
    -   [屏幕亮度 brightness](brightness.html){.sidebar-link}
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
# [\#](vibrator.html#振动-vibrator){.header-anchor} 振动 vibrator

## [\#](vibrator.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.vibrator" }
```
:::

## [\#](vibrator.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import vibrator from '@system.vibrator' 
// 或 
const vibrator = require('@system.vibrator')
```
:::

## [\#](vibrator.html#接口定义){.header-anchor} 接口定义

### [\#](vibrator.html#vibrator-vibrate-object){.header-anchor} vibrator.vibrate(OBJECT) {#vibrator-vibrate-object}

触发振动

#### [\#](vibrator.html#参数){.header-anchor} 参数：

  参数   类型     必填   说明
  ------ -------- ------ ----------------------------------------------------------------
  mode   String   否     振动模式，\"long\"表示长振动，\"short\"表示短振动。默认为 long

#### [\#](vibrator.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
vibrator.vibrate({
  mode: 'long'
})
```
:::

### [\#](vibrator.html#vibrator-start-object){.header-anchor} vibrator.start(OBJECT) {#vibrator-start-object}

开始振动

#### [\#](vibrator.html#参数-2){.header-anchor} 参数： {#参数-2}

  参数       类型       必填   说明
  ---------- ---------- ------ -------------------------------------
  duration   Number     是     振动持续时间(单位 ms)，必须为正整数
  interval   Number     是     振动间隔时间(单位 ms)，必须为正整数
  count      Number     是     振动次数，必须为正整数
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](vibrator.html#success-返回值){.header-anchor} success 返回值：

  参数名   类型     说明
  -------- -------- -------------------------
  id       Number   唯一的 ID，标识振动任务

#### [\#](vibrator.html#fail-返回值){.header-anchor} fail 返回值：

  错误码   说明
  -------- ------------
  205      任务已存在
  202      参数错误

#### [\#](vibrator.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
vibrator.start({
  duration: 1000,
  interval: 1000,
  count: 10,
  success: function (data) {
    console.log(`handling success, id = ${data.id}`)
  },
  fail: function(data, code) {
    console.log(`handling fail, code = ${code}, errorMsg=${data}`)
  },
  complete: function () {
    console.log(`handling complete`)
  }
})
```
:::

### [\#](vibrator.html#vibrator-stop-number){.header-anchor} vibrator.stop(Number) {#vibrator-stop-number}

停止振动

#### [\#](vibrator.html#参数-3){.header-anchor} 参数： {#参数-3}

  类型     必填   说明
  -------- ------ -------------
  Number   是     振动任务 ID

#### [\#](vibrator.html#返回值){.header-anchor} 返回值：

  类型      说明
  --------- -------------------------
  Boolean   true：成功；false：失败

#### [\#](vibrator.html#示例-3){.header-anchor} 示例： {#示例-3}

::: {.language-javascript .extra-class}
``` language-javascript
vibrator.stop(1)
```
:::

### [\#](vibrator.html#vibrator-getsystemdefaultmode){.header-anchor} vibrator.getSystemDefaultMode() {#vibrator-getsystemdefaultmode}

获取系统默认振动模式

#### [\#](vibrator.html#参数-4){.header-anchor} 参数： {#参数-4}

无

#### [\#](vibrator.html#返回值-2){.header-anchor} 返回值： {#返回值-2}

  类型     说明
  -------- ---------------------------------------
  Number   0：关闭振动；1：标准振动；2：加强振动

#### [\#](vibrator.html#示例-4){.header-anchor} 示例： {#示例-4}

::: {.language-javascript .extra-class}
``` language-javascript
vibrator.getSystemDefaultMode()
```
:::

## [\#](vibrator.html#支持明细){.header-anchor} 支持明细

  接口                   已支持设备产品                                                                                                                                          不支持设备产品
  ---------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------- -------------------------------------------------------------------------------------------------------------------------------------------------------
  vibrate                小米 S1 Pro 运动健康手表、小米手环 8 Pro、小米手环 9、Redmi Watch 4、Xiaomi Watch H1、Xiaomi Watch S3、小米手环 9 Pro、Xiaomi Watch S4、REDMI Watch 5   \-
  start                  \-                                                                                                                                                      Xiaomi Watch S3、小米手环 9 Pro、Xiaomi Watch S4、REDMI Watch 5、小米 S1 Pro 运动健康手表、小米手环 8 Pro、小米手环 9、Redmi Watch 4、Xiaomi Watch H1
  stop                   \-                                                                                                                                                      Xiaomi Watch S3、小米手环 9 Pro、Xiaomi Watch S4、REDMI Watch 5、小米 S1 Pro 运动健康手表、小米手环 8 Pro、小米手环 9、Redmi Watch 4、Xiaomi Watch H1
  getSystemDefaultMode   \-                                                                                                                                                      Xiaomi Watch S3、小米手环 9 Pro、Xiaomi Watch S4、REDMI Watch 5、小米 S1 Pro 运动健康手表、小米手环 8 Pro、小米手环 9、Redmi Watch 4、Xiaomi Watch H1
:::

::: page-nav
[ ← [网络信息 network](network.html){.prev} ]{.prev} [ [屏幕亮度
brightness](brightness.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](vibrator.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](vibrator.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](vibrator.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[vibrator.vibrate(OBJECT)](vibrator.html#vibrator-vibrate-object "vibrator.vibrate(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[vibrator.start(OBJECT)](vibrator.html#vibrator-start-object "vibrator.start(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[vibrator.stop(Number)](vibrator.html#vibrator-stop-number "vibrator.stop(Number)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[vibrator.getSystemDefaultMode()](vibrator.html#vibrator-getsystemdefaultmode "vibrator.getSystemDefaultMode()")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[支持明细](vibrator.html#支持明细 "支持明细")
:::
:::
:::

::: global-ui
:::
:::
