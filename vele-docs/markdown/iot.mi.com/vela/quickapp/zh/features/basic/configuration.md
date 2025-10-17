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
    -   [应用上下文 app](app.html){.sidebar-link}
    -   [设备信息 device](device.html){.sidebar-link}
    -   [页面路由 router](router.html){.sidebar-link}
    -   [应用配置 configuration](configuration.html){.active
        .sidebar-link aria-current="page"}
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
    -   [系统音量 volume](../system/volume.html){.sidebar-link}
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
# [\#](configuration.html#应用配置-configuration){.header-anchor} 应用配置 configuration

## [\#](configuration.html#接口声明){.header-anchor} 接口声明

无需声明

## [\#](configuration.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import configuration from '@system.configuration' 
// 或 
const configuration = require('@system.configuration')
```
:::

## [\#](configuration.html#接口定义){.header-anchor} 接口定义

### [\#](configuration.html#configuration-getlocale){.header-anchor} configuration.getLocale() {#configuration-getlocale}

获取应用当前的语言环境。默认使用系统的语言环境，会因为设置或系统语言环境改变而发生变化

#### [\#](configuration.html#参数){.header-anchor} 参数：

无

#### [\#](configuration.html#返回值){.header-anchor} 返回值：

  参数名            类型     说明
  ----------------- -------- ------------
  language          String   语言
  countryOrRegion   String   国家或地区

#### [\#](configuration.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
const locale = configuration.getLocale()
console.log(locale.language)
```
:::
:::

::: page-nav
[ ← [页面路由 router](router.html){.prev} ]{.prev} [ [数据请求
fetch](../network/fetch.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](configuration.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](configuration.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](configuration.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[configuration.getLocale()](configuration.html#configuration-getlocale "configuration.getLocale()")
:::
:::
:::

::: global-ui
:::
:::
