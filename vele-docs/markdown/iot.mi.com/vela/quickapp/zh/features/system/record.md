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
    -   [录音 record](record.html){.active .sidebar-link
        aria-current="page"}
    -   [地理位置 geolocation](geolocation.html){.sidebar-link}
    -   [传感器 sensor](sensor.html){.sidebar-link}
    -   [事件 event](event.html){.sidebar-link}
    -   [电量信息 battery](battery.html){.sidebar-link}
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
# [\#](record.html#录音-record){.header-anchor} 录音 record

## [\#](record.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.record" }
```
:::

## [\#](record.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import record from '@system.record' 
// 或 
const record = require('@system.record')
```
:::

## [\#](record.html#接口定义){.header-anchor} 接口定义

### [\#](record.html#record-start-object){.header-anchor} record.start(OBJECT) {#record-start-object}

开始录音

#### [\#](record.html#参数){.header-anchor} 参数：

  参数名             类型       必填   说明
  ------------------ ---------- ------ ------------------------------------------------------------------------------------------------------
  duration           Number     否     录音时长，单位为 ms。如果 duration 为有效值将在达到指定值时停止录音
  sampleRate         Number     否     采样率。不同的音频格式所支持的采样率范围不同。默认设置为 8000，建议使用 8000/16000/32000/44100/48000
  numberOfChannels   Number     否     录音通道数，有效值 1/2
  encodeBitRate      Number     否     编码码率。编码码率的取值与采样率和音频格式有关
  format             String     否     音频格式，有效值 pcm/opus/wav。缺省为 pcm
  success            Function   否     成功回调
  fail               Function   否     失败回调
  complete           Function   否     执行结束后的回调

#### [\#](record.html#success-返回值){.header-anchor} success 返回值：

  参数名   类型     说明
  -------- -------- ----------------------------------------
  uri      String   录音文件的存储路径，在应用的缓存目录中

#### [\#](record.html#fail-返回错误码){.header-anchor} fail 返回错误码：

  错误码   说明
  -------- ----------------
  205      录音已在进行中
  202      参数错误

#### [\#](record.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
record.start({
  duration: 10000,
  sampleRate: 8000,
  numberOfChannels: 1,
  encodeBitRate: 128000,
  format: 'pcm',
  success: function(data) {
    console.log(`handling success: ${data.uri}`)
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

### [\#](record.html#record-stop){.header-anchor} record.stop() {#record-stop}

停止录音

#### [\#](record.html#参数-2){.header-anchor} 参数： {#参数-2}

无

#### [\#](record.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
record.stop()
```
:::
:::

::: page-nav
[ ← [屏幕亮度 brightness](brightness.html){.prev} ]{.prev} [ [地理位置
geolocation](geolocation.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](record.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](record.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](record.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[record.start(OBJECT)](record.html#record-start-object "record.start(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[record.stop()](record.html#record-stop "record.stop()")
:::
:::
:::

::: global-ui
:::
:::
