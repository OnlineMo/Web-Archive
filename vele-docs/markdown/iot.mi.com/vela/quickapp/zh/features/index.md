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
[JS接口](index.html){.nav-link .router-link-exact-active
.router-link-active aria-current="page"}
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
[JS接口](index.html){.nav-link .router-link-exact-active
.router-link-active aria-current="page"}
:::

::: nav-item
[编程示例](../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../tools/index.html){.nav-link}
:::

-   [通用规范](grammar.html){.sidebar-link}

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
    -   [系统音量 volume](system/volume.html){.sidebar-link}
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
# [\#](index.html#接口){.header-anchor} 接口

框架提供若干接口供应用调用以实现更多功能，包括以下几种接口：

-   基本功能类接口：用以获取应用信息、平台信息、设备信息等；
-   数据文件类接口：用以获取远程数据、上下载文件、本地数据存储等；
-   系统能力接口：用来调用系统能力，例如获取网络状况、调节屏幕亮度等；
-   媒体类接口：用来播放操作媒体文件，比如播放音乐文件等；

每个接口称为一个 feature，每个 feature 包含若干个实现某具体功能的 api。
:::
:::
:::

::: global-ui
:::
:::
