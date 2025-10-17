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
    -   [页面路由 router](router.html){.active .sidebar-link
        aria-current="page"}
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
# [\#](router.html#页面路由-router){.header-anchor} 页面路由 router

## [\#](router.html#接口声明){.header-anchor} 接口声明

无需声明

## [\#](router.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import router from '@system.router' 
// 或 
const router = require('@system.router')
```
:::

## [\#](router.html#接口定义){.header-anchor} 接口定义

### [\#](router.html#router-push-object){.header-anchor} router.push(OBJECT) {#router-push-object}

跳转到应用内的某个页面

#### [\#](router.html#参数){.header-anchor} 参数：

  -------------------------------------------------------------------------------------------------------------------------------------
  参数              类型              必填              说明
  ----------------- ----------------- ----------------- -------------------------------------------------------------------------------
  uri               String            是                要跳转到的 uri，可以是下面的格式：\
                                                        1、包含 schema 的完整 uri；\
                                                        2、以'/'开头的应用内页面的路径；例：/about\
                                                        3、以非'/'开头的应用内页面的名称；例：About\
                                                        4、特殊的，如果 uri 的值是\"/\"，则跳转到 path 为\"/\"的页，没有则跳转到首页\
                                                        \
                                                        支持包含 schema 的完整 uri。对于带有 schema 的 uri，处理流程如下：\
                                                        如果 schema 是 hap （参见 [hap
                                                        链接](../../guide/framework/other/hap-schema.html)），会跳转到 hap
                                                        链接所支持的类型

  params            Object            否                跳转时需要传递的数据，参数可以在目标页面中通过`this.param1`的方式使用，param1
                                                        为 json 中的参数名，param1 对应的值会统一转换为 String
                                                        类型。使用`this.param1`变量时，需要在目标页面中在 `public`（应用外传参）或
                                                        `protected` (应用内传参)下定义 key 名相同的属性
  -------------------------------------------------------------------------------------------------------------------------------------

#### [\#](router.html#params参数){.header-anchor} params参数：

  参数                            类型     必填   说明
  ------------------------------- -------- ------ --------------------------------------------------------------------------------------------------------------------------------------------------------
  \_\_\_PARAM_LAUNCH_FLAG\_\_\_   String   否     JS 应用启动参数，目前仅支持\"clearTask\"，在启动目标页面时会清除除此页面外的其他页面。详见[页面启动模式](../../guide/framework/other/launch-mode.html)

#### [\#](router.html#示例){.header-anchor} 示例：

-   应用内切换页面

    -   path 切换

        ::: {.language-javascript .extra-class}
        ``` language-javascript
        router.push({
          uri: '/about',
          params: {
            testId: '1'
          }
        })
        ```
        :::
    -   name 切换

        ::: {.language-javascript .extra-class}
        ``` language-javascript
        // open page by name
        router.push({
          uri: 'About',
          params: {
            testId: '1'
          }
        })
        ```
        :::
    -   切换页面并清除其他页面

        ::: {.language-javascript .extra-class}
        ``` language-javascript
        router.push({
          uri: '/about',
          params: {
            ___PARAM_LAUNCH_FLAG___: 'clearTask'
          }
        })
        ```
        :::

### [\#](router.html#router-replace-object){.header-anchor} router.replace(OBJECT) {#router-replace-object}

用应用内的某个页面替换当前页面，并销毁被替换的页面

#### [\#](router.html#参数-2){.header-anchor} 参数： {#参数-2}

+-----------------+-----------------+-----------------+-----------------+
| 参数            | 类型            | 必填            | 说明            |
+=================+=================+=================+=================+
| uri             | String          | 是              | 要跳转到的      |
|                 |                 |                 | uri，可以       |
|                 |                 |                 | 是下面的格式：  |
|                 |                 |                 |                 |
|                 |                 |                 | 1.              |
|                 |                 |                 |   以\"/\"开头的 |
|                 |                 |                 | 应用内页面的路  |
|                 |                 |                 | 径；例：/about  |
|                 |                 |                 | 2.              |
|                 |                 |                 |   以非\"/\"开头 |
|                 |                 |                 | 的应用内页面的  |
|                 |                 |                 | 名称；例：About |
|                 |                 |                 | 3               |
|                 |                 |                 | .  特殊的，如果 |
|                 |                 |                 |     uri         |
|                 |                 |                 |     的值是      |
|                 |                 |                 | \"/\"，则跳转到 |
|                 |                 |                 |     path        |
|                 |                 |                 |                 |
|                 |                 |                 | 为\"/\"的页，没 |
|                 |                 |                 | 有则跳转到首页  |
+-----------------+-----------------+-----------------+-----------------+
| params          | Object          | 否              | 跳转时          |
|                 |                 |                 | 需要传递的数据  |
|                 |                 |                 | ，参数可以在目  |
|                 |                 |                 | 标页面中通过`t  |
|                 |                 |                 | his.param1`的方 |
|                 |                 |                 | 式使用，param1  |
|                 |                 |                 | 为 json         |
|                 |                 |                 | 中的            |
|                 |                 |                 | 参数名，param1  |
|                 |                 |                 | 对应的          |
|                 |                 |                 | 值会统一转换为  |
|                 |                 |                 | String          |
|                 |                 |                 | 类型。          |
|                 |                 |                 | 使用`this.para  |
|                 |                 |                 | m1`变量时，需要 |
|                 |                 |                 | 在目标页面中在  |
|                 |                 |                 | `public`（      |
|                 |                 |                 | 应用外传参）或  |
|                 |                 |                 | `protected`     |
|                 |                 |                 | (应             |
|                 |                 |                 | 用内传参)下定义 |
|                 |                 |                 | key             |
|                 |                 |                 | 名相同的属性    |
+-----------------+-----------------+-----------------+-----------------+

#### [\#](router.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
router.replace({
  uri: '/test',
  params: {
    testId: '1'
  }
})
```
:::

### [\#](router.html#router-back-object){.header-anchor} router.back(OBJECT) {#router-back-object}

返回指定页面

#### [\#](router.html#参数-3){.header-anchor} 参数： {#参数-3}

+-----------------+-----------------+-----------------+-----------------+
| 参数            | 类型            | 必填            | 说明            |
+=================+=================+=================+=================+
| path            | String          | 否              | 返回目标页面    |
|                 |                 |                 | 的路径，可以是  |
|                 |                 |                 | 以下几种取值：  |
|                 |                 |                 |                 |
|                 |                 |                 | 1.  不传该参数  |
|                 |                 |                 | ，返回上一页面  |
|                 |                 |                 | 2.  以\"        |
|                 |                 |                 | /\"开头的应用内 |
|                 |                 |                 | 已打开页面的路  |
|                 |                 |                 | 径；例：/about  |
|                 |                 |                 | 3               |
|                 |                 |                 | .  特殊的，如果 |
|                 |                 |                 |     path        |
|                 |                 |                 |                 |
|                 |                 |                 | 的值是\"/\"，则 |
|                 |                 |                 | 跳转到页面名称  |
|                 |                 |                 | 为\"/\"的页，没 |
|                 |                 |                 | 有则跳转到首页  |
|                 |                 |                 |                 |
|                 |                 |                 | 注意点：        |
|                 |                 |                 |                 |
|                 |                 |                 | 1.  path        |
|                 |                 |                 |     需要是以    |
|                 |                 |                 | \"/\"开头的当前 |
|                 |                 |                 | 应用已经打开的  |
|                 |                 |                 | 页面路径，否则  |
|                 |                 |                 | 均视为无效参数  |
|                 |                 |                 | ，返回上一页面  |
|                 |                 |                 | 2.  若根据 path |
|                 |                 |                 |     未匹配到    |
|                 |                 |                 | 已经打开的页面  |
|                 |                 |                 | ，返回上一页面  |
|                 |                 |                 | 3.  若根据 path |
|                 |                 |                 |                 |
|                 |                 |                 |    参数匹配到多 |
|                 |                 |                 | 个页面，返回至  |
|                 |                 |                 | 最后打开的页面  |
+-----------------+-----------------+-----------------+-----------------+

#### [\#](router.html#示例-3){.header-anchor} 示例： {#示例-3}

::: {.language-javascript .extra-class}
``` language-javascript
// A页面, open page by name
router.push({
  uri: 'B'
})
// B页面, open page by name
router.push({
  uri: 'C'
})
// C页面, open page by name
router.push({
  uri: 'D'
})
// D页面, open page by name
router.push({
  uri: 'E'
})
// E页面不传入页面路径，返回至D页面
router.back()
// D页面不传入页面名称，返回至C页面
router.back()
// C页面传入页面路径，返回至A页面
router.back({
  path: '/A'
})
```
:::

### [\#](router.html#router-clear){.header-anchor} router.clear() {#router-clear}

清空所有历史页面记录，仅保留当前页面

#### [\#](router.html#参数-4){.header-anchor} 参数： {#参数-4}

无

#### [\#](router.html#示例-4){.header-anchor} 示例： {#示例-4}

::: {.language-javascript .extra-class}
``` language-javascript
router.clear()
```
:::

### [\#](router.html#router-getlength){.header-anchor} router.getLength() {#router-getlength}

获取当前页面栈的页面数量

#### [\#](router.html#返回值){.header-anchor} 返回值:

  类型     说明
  -------- ----------
  Number   页面数量

#### [\#](router.html#示例-5){.header-anchor} 示例： {#示例-5}

::: {.language-javascript .extra-class}
``` language-javascript
var length = router.getLength()
console.log(`page's length = ${length}`)
```
:::

### [\#](router.html#router-getstate){.header-anchor} router.getState() {#router-getstate}

获取当前页面状态

#### [\#](router.html#返回参数){.header-anchor} 返回参数：

  参数名   类型     说明
  -------- -------- --------------------------
  index    Number   当前页面在页面栈中的位置
  name     String   当前页面的名称
  path     String   当前页面的路径

#### [\#](router.html#示例-6){.header-anchor} 示例： {#示例-6}

::: {.language-javascript .extra-class}
``` language-javascript
var page = router.getState()
console.log(`page index = ${page.index}`)
console.log(`page name = ${page.name}`)
console.log(`page path = ${page.path}`)
```
:::

### [\#](router.html#router-getpages){.header-anchor} router.getPages() {#router-getpages}

获取当前页面栈列表

#### [\#](router.html#返回值-2){.header-anchor} 返回值： {#返回值-2}

  类型    说明
  ------- ----------------------------------------
  Array   页面栈列表。数组每一项都为 Object 类型

数组每一项构成：

  字段   类型     说明
  ------ -------- ------------
  name   String   页面的名称
  path   String   页面的路径

#### [\#](router.html#示例-7){.header-anchor} 示例： {#示例-7}

::: {.language-javascript .extra-class}
``` language-javascript
var stacks = router.getPages()
console.log('栈底页面名称为：', stacks[0].name) // 如 list、detail 等
console.log('栈底页面路径为：', stacks[0].path) // 如 /list、/detail、/home/preview
```
:::
:::

::: page-nav
[ ← [设备信息 device](device.html){.prev} ]{.prev} [ [应用配置
configuration](configuration.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](router.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](router.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](router.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[router.push(OBJECT)](router.html#router-push-object "router.push(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[router.replace(OBJECT)](router.html#router-replace-object "router.replace(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[router.back(OBJECT)](router.html#router-back-object "router.back(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[router.clear()](router.html#router-clear "router.clear()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[router.getLength()](router.html#router-getlength "router.getLength()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[router.getState()](router.html#router-getstate "router.getState()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[router.getPages()](router.html#router-getpages "router.getPages()")
:::
:::
:::

::: global-ui
:::
:::
