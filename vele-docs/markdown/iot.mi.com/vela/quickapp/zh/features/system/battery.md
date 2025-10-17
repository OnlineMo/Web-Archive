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
    -   [屏幕亮度 brightness](brightness.html){.sidebar-link}
    -   [录音 record](record.html){.sidebar-link}
    -   [地理位置 geolocation](geolocation.html){.sidebar-link}
    -   [传感器 sensor](sensor.html){.sidebar-link}
    -   [事件 event](event.html){.sidebar-link}
    -   [电量信息 battery](battery.html){.active .sidebar-link
        aria-current="page"}
    -   [系统音量 volume](volume.html){.sidebar-link}
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
# [\#](battery.html#电量信息-battery){.header-anchor} 电量信息 battery

## [\#](battery.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.battery" }
```
:::

## [\#](battery.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import battery from '@system.battery' 
// 或 
const battery = require('@system.battery')
```
:::

## [\#](battery.html#接口定义){.header-anchor} 接口定义

### [\#](battery.html#battery-getstatus-object){.header-anchor} battery.getStatus(OBJECT) {#battery-getstatus-object}

获取当前设备的电量信息

#### [\#](battery.html#参数){.header-anchor} 参数：

  参数名     类型       必填   说明
  ---------- ---------- ------ ------------------
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](battery.html#success-返回值){.header-anchor} success 返回值：

  参数名     类型      说明
  ---------- --------- --------------------------
  charging   Boolean   是否正在充电
  level      Number    当前电量，0.0 - 1.0 之间

#### [\#](battery.html#示例){.header-anchor} 示例

::: {.language-javascript .extra-class}
``` language-javascript
battery.getStatus({
  success: function(data) {
      console.log(`handling success: ${data.level}`)
  },
  fail: function(data, code) {
      console.log(`handling fail, code = ${code}`)
  }
})
```
:::

## [\#](battery.html#支持明细){.header-anchor} 支持明细

  设备产品                   说明
  -------------------------- --------
  小米 S1 Pro 运动健康手表   不支持
  小米手环 8 Pro             不支持
  Xiaomi Watch S3            不支持
  Redmi Watch 4              不支持
  小米腕部心电血压记录仪     不支持
  Xiaomi Watch S4            支持
  REDMI Watch 5              支持
:::

::: page-nav
[ ← [事件 event](event.html){.prev} ]{.prev} [ [系统音量
volume](volume.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](battery.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](battery.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](battery.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[battery.getStatus(OBJECT)](battery.html#battery-getstatus-object "battery.getStatus(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[支持明细](battery.html#支持明细 "支持明细")
:::
:::
:::

::: global-ui
:::
:::
