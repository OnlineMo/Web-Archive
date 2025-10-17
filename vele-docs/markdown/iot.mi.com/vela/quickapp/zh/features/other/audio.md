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
    [其他](index.html){.sidebar-heading .clickable .router-link-active
    .open}
    -   [音频 audio](audio.html){.active .sidebar-link
        aria-current="page"}
    -   [弹窗 prompt](prompt.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](audio.html#音频-audio){.header-anchor} 音频 audio

## [\#](audio.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.audio" }
```
:::

## [\#](audio.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import audio from '@system.audio' 
// 或 
const audio = require('@system.audio')
```
:::

## [\#](audio.html#方法){.header-anchor} 方法

### [\#](audio.html#audio-play){.header-anchor} audio.play() {#audio-play}

开始播放音频

#### [\#](audio.html#参数){.header-anchor} 参数

无

#### [\#](audio.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
audio.play()
```
:::

### [\#](audio.html#audio-pause){.header-anchor} audio.pause() {#audio-pause}

暂停播放音频

#### [\#](audio.html#参数-2){.header-anchor} 参数 {#参数-2}

无

#### [\#](audio.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
audio.pause()
```
:::

### [\#](audio.html#audio-stop){.header-anchor} audio.stop() {#audio-stop}

停止音频播放，可以通过 play 重新播放音频

#### [\#](audio.html#参数-3){.header-anchor} 参数 {#参数-3}

无

#### [\#](audio.html#示例-3){.header-anchor} 示例： {#示例-3}

::: {.language-javascript .extra-class}
``` language-javascript
audio.stop()
```
:::

### [\#](audio.html#audio-getplaystate-object){.header-anchor} audio.getPlayState(OBJECT) {#audio-getplaystate-object}

获取当前播放状态数据

#### [\#](audio.html#参数-4){.header-anchor} 参数 {#参数-4}

  参数名     类型       必填   说明
  ---------- ---------- ------ ------------------
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](audio.html#success-返回值){.header-anchor} success 返回值：

  参数值        类型     说明
  ------------- -------- ---------------------------------------------------------------
  state         String   播放状态,分别为\'play\'，\'pause\'，\'stop\'
  src           String   当前播放的音频媒体 uri，停止时返回空字符串
  currentTime   Number   当前音频的当前进度，单位秒，停止时返回-1
  percent       Number   当前播放进度百分比，范围0-100
  autoplay      Boolen   当前音频是否在自动播放
  loop          Boolen   当前音频是否在循环播放
  volume        Number   当前音频的音量，默认当前系统媒体音量，音量变化范围\[0.0,1.0\]
  muted         Boolen   当前音频是否在静音播放
  duration      Number   音频的播放时长，单位秒，未知返回 NaN

#### [\#](audio.html#示例-4){.header-anchor} 示例： {#示例-4}

::: {.language-javascript .extra-class}
``` language-javascript
audio.getPlayState({
  success: function(data) {
    console.log(`handling success: state: ${data.state},src:${data.src},currentTime:${data.currentTime},autoplay:${data.autoplay},loop:${data.loop},volume: ${data.volume},muted:${data.muted},notificationVisible:${data.notificationVisible}`)
  },
  fail: function(data, code) {
    console.log('handling fail, code=' + code)
  }
})
```
:::

## [\#](audio.html#属性){.header-anchor} 属性

  名称          参数类型                                                   是否可读   是否可写   必填   描述
  ------------- ---------------------------------------------------------- ---------- ---------- ------ ------------------------------------------------------------------------------------------------------------------------------------------------
  src           String                                                     是         是         是     播放的音频媒体 uri
  currentTime   Number                                                     是         是         否     音频的当前进度，单位秒，对值设置可以调整播放进度
  duration      Number                                                     是         否         否     音频的播放时长，单位秒，未知返回 NaN
  autoplay      Boolean                                                    是         是         否     音频是否自动播放，默认 false
  loop          Boolean                                                    是         是         否     音频是否循环播放，默认 false
  volume        Number                                                     是         是         否     音频的音量，默认当前系统媒体音量，音量变化范围\[0.0,1.0\]
  muted         Boolean                                                    是         是         否     音频是否静音，默认 false
  streamType    String                                                     是         否         否     使用音频的类型，可能的值有 music、voicecall，值为 music 时使用扬声器播放，voicecall 时使用听筒播放（手表、手环设备不支持此配置），默认为 music
  meta          Object\<{title: string, artist: string, album: string}\>   否         是         否     音频元数据信息，包括歌名、歌手、专辑名

#### [\#](audio.html#示例-5){.header-anchor} 示例： {#示例-5}

::: {.language-javascript .extra-class}
``` language-javascript
// let currentTime = audio.currentTime
audio.currentTime = 5
```
:::

## [\#](audio.html#事件){.header-anchor} 事件

  名称             描述
  ---------------- -----------------------------------------------------------------------------------------------------------------------
  play             在调用 play 方法后或者 autoplay 为 true 时的回调事件。被动触发场景举例：1. 蓝牙耳机控制播放音频
  pause            在调用 pause 方法后的回调事件。被动触发场景举例：1. 音频焦点被抢占，例如：播放音频时收到来电；2. 蓝牙耳机控制暂停音频
  stop             在调用 stop 方法后的回调事件。被动触发场景举例：1. 正在打电话时播放音频
  loadeddata       第一次获取到音频数据的回调事件
  ended            播放结束时的回调事件
  durationchange   播放时长变化时的回调事件
  error            播放发生错误时的回调事件

#### [\#](audio.html#示例-6){.header-anchor} 示例： {#示例-6}

::: {.language-javascript .extra-class}
``` language-javascript
audio.onplay = function() {
  console.log(`audio starts to play`)
}
audio.onplay = null
```
:::
:::

::: page-nav
[ ← [密码算法 crypto](../security/crypto.html){.prev} ]{.prev} [ [弹窗
prompt](prompt.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](audio.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](audio.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[方法](audio.html#方法 "方法")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[audio.play()](audio.html#audio-play "audio.play()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[audio.pause()](audio.html#audio-pause "audio.pause()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[audio.stop()](audio.html#audio-stop "audio.stop()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[audio.getPlayState(OBJECT)](audio.html#audio-getplaystate-object "audio.getPlayState(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[属性](audio.html#属性 "属性")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](audio.html#事件 "事件")
:::
:::
:::

::: global-ui
:::
:::
