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
    -   [设备通信 interconnect](interconnect.html){.active .sidebar-link
        aria-current="page"}
    -   [下载 request](request.html){.sidebar-link}
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
# [\#](interconnect.html#设备通信-interconnect){.header-anchor} 设备通信 interconnect

用于和搭配使用的手机 app 进行通信，收发手机 app 数据。
通信连接会自动建立，应用内不用关心连接的创建和销毁，但是可以注册回调函数来接收连接状态改变的信息，以便于进行相应处理，例如对用户进行提示。

## [\#](interconnect.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.interconnect" }
```
:::

## [\#](interconnect.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import interconnect from '@system.interconnect'
// 或
const interconnect = require('@system.interconnect')
```
:::

## [\#](interconnect.html#接口定义){.header-anchor} 接口定义

### [\#](interconnect.html#interconnect-instance){.header-anchor} interconnect.instance() {#interconnect-instance}

获取连接对象，在 app
中以单例形式存在，后续的数据收发都是基于这个连接对象

#### [\#](interconnect.html#参数){.header-anchor} 参数：

无

#### [\#](interconnect.html#返回值){.header-anchor} 返回值：

interconnect 的链接实例 connect 对象

#### [\#](interconnect.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
const connect = interconnect.instance()
```
:::

### [\#](interconnect.html#connect-getreadystate-object){.header-anchor} connect.getReadyState(OBJECT) {#connect-getreadystate-object}

获取 App 连接状态

#### [\#](interconnect.html#object参数){.header-anchor} OBJECT参数：

  参数名    类型       必填   说明
  --------- ---------- ------ ----------
  success   Function   否     成功回调
  fail      Function   否     失败回调

#### [\#](interconnect.html#success-返回值){.header-anchor} success 返回值：

  属性值   类型     说明
  -------- -------- --------------------------
  status   Number   1：连接成功，2：连接断开

#### [\#](interconnect.html#fail-返回值){.header-anchor} fail 返回值：

  参数值   类型     说明
  -------- -------- ----------
  data     String   错误信息
  code     Number   错误码

#### [\#](interconnect.html#错误码说明){.header-anchor} 错误码说明：

[支持通用错误码](../grammar.html#通用错误码)

  错误码   说明
  -------- ----------
  1006     连接断开

#### [\#](interconnect.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
connect.getReadyState({
  success: (data) => {
    if (data.status === 1) {
      console.log('连接成功')
    } else if (data.status === 2) {
      console.log('连接失败')
    }
  },
  fail: (data, code) => {
    console.log(`handling fail, code = ${code}`)
  }
})
```
:::

### [\#](interconnect.html#connect-diagnosis-object){.header-anchor} connect.diagnosis(OBJECT) {#connect-diagnosis-object}

诊断手表应用和对端应用的连接情况，如果连接成功则返回ok，连接失败则返回失败原因。如果调用时正在连接则等待连接结束后再返回最终状态。

#### [\#](interconnect.html#obejct参数){.header-anchor} Obejct参数：

  -------------------------------------------------------------------------------------
  属性              类型              必填              说明
  ----------------- ----------------- ----------------- -------------------------------
  timeout           Number            否                等待诊断的超时时间，单位毫秒\
                                                        默认值：10000ms

  success           Function          否                成功回调

  fail              Function          否                失败回调
  -------------------------------------------------------------------------------------

#### [\#](interconnect.html#success-返回值-2){.header-anchor} success 返回值： {#success-返回值-2}

  -----------------------------------------------------------------------
  属性值                  类型                    说明
  ----------------------- ----------------------- -----------------------
  status                  Number                  0: OK 链接成功\
                                                  204：CONNECT_TIMEOUT
                                                  连接超时\
                                                  1001：APP_UNINSTALLED
                                                  对端应用未安装\
                                                  1000：OTHERS
                                                  其他链接错误

  -----------------------------------------------------------------------

#### [\#](interconnect.html#fail-返回值-2){.header-anchor} fail 返回值： {#fail-返回值-2}

  参数值   类型     说明
  -------- -------- ----------
  data     String   错误信息
  code     Number   错误码

#### [\#](interconnect.html#错误码说明-2){.header-anchor} 错误码说明： {#错误码说明-2}

[支持通用错误码](../grammar.html#通用错误码)

#### [\#](interconnect.html#示例-3){.header-anchor} 示例： {#示例-3}

::: {.language-javascript .extra-class}
``` language-javascript
connect.diagnosis({
  success: function (data) {
    console.log(`handling success, version = ${data.status}`)
  },
  fail: function (data, code) {
    console.log(`handling fail, code = ${code}`)
  },
})
```
:::

### [\#](interconnect.html#connect-send-object){.header-anchor} connect.send(OBJECT) {#connect-send-object}

发送数据到手机 App 端

#### [\#](interconnect.html#object参数-2){.header-anchor} Object参数： {#object参数-2}

  参数名    类型       必填   说明
  --------- ---------- ------ ------------
  data      Object     否     发送的数据
  success   Function   否     成功回调
  fail      Function   否     失败回调

#### [\#](interconnect.html#success-返回值-3){.header-anchor} success 返回值： {#success-返回值-3}

无

#### [\#](interconnect.html#fail-返回值-3){.header-anchor} fail 返回值： {#fail-返回值-3}

  参数值   类型     说明
  -------- -------- ----------
  data     String   错误信息
  code     Number   错误码

#### [\#](interconnect.html#错误码说明-3){.header-anchor} 错误码说明： {#错误码说明-3}

[支持通用错误码](../grammar.html#通用错误码)

  错误码   说明
  -------- ----------
  204      链接超时
  1006     连接断开

#### [\#](interconnect.html#示例-4){.header-anchor} 示例： {#示例-4}

::: {.language-javascript .extra-class}
``` language-javascript
connect.send({
  data: {},
  success: ()=>{
    console.log(`handling success`)
  },
  fail: (data, code)=> {
    console.log(`handling fail, errMsg = ${data.data}, errCode = ${data.code}`)
  }
})
```
:::

## [\#](interconnect.html#事件){.header-anchor} 事件

### [\#](interconnect.html#connect-onmessage){.header-anchor} connect.onmessage {#connect-onmessage}

接收手机 App 端数据

#### [\#](interconnect.html#回调参数){.header-anchor} 回调参数：

  参数名   类型     说明
  -------- -------- ------------
  data     String   接收的数据

#### [\#](interconnect.html#示例-5){.header-anchor} 示例： {#示例-5}

::: {.language-javascript .extra-class}
``` language-javascript
connect.onmessage = (data) => {
  console.log(`received message: ${data.data}`)
}
```
:::

### [\#](interconnect.html#connect-onopen){.header-anchor} connect.onopen {#connect-onopen}

连接打开时的回调函数

#### [\#](interconnect.html#回调参数-2){.header-anchor} 回调参数： {#回调参数-2}

  参数名          类型      说明
  --------------- --------- ----------------
  isReconnected   Boolean   是否是重新连接

#### [\#](interconnect.html#示例-6){.header-anchor} 示例： {#示例-6}

::: {.language-javascript .extra-class}
``` language-javascript
connect.onOpen = function (data) {
  console.log('connection opened isReconnected: ', data.isReconnected)
}
```
:::

### [\#](interconnect.html#connect-onclose){.header-anchor} connect.onclose {#connect-onclose}

连接关闭时的回调函数

#### [\#](interconnect.html#回调参数-3){.header-anchor} 回调参数： {#回调参数-3}

  参数名   类型     说明
  -------- -------- --------------------
  code     Number   链接关闭状态码
  data     String   连接关闭返回的数据

#### [\#](interconnect.html#示例-7){.header-anchor} 示例： {#示例-7}

::: {.language-javascript .extra-class}
``` language-javascript
connect.onclose = (data) => {
  console.log(`connection closed, reason = ${data.data}, code = ${data.code}`)
}
```
:::

### [\#](interconnect.html#connect-onerror){.header-anchor} connect.onerror {#connect-onerror}

连接出错时的回调函数

#### [\#](interconnect.html#回调参数-4){.header-anchor} 回调参数： {#回调参数-4}

  参数名   类型     说明
  -------- -------- ----------------------
  code     Number   错误码，见错误码说明
  data     String   错误信息

#### [\#](interconnect.html#错误码说明-4){.header-anchor} 错误码说明： {#错误码说明-4}

[支持通用错误码](../grammar.html#通用错误码)

  错误码   说明
  -------- -----------------
  1000     未知错误
  1001     手机 APP 未安装
  1006     连接断开

#### [\#](interconnect.html#示例-8){.header-anchor} 示例： {#示例-8}

::: {.language-javascript .extra-class}
``` language-javascript
connect.onerror = (data)=> {
  console.log(`connection error, errMsg = ${data.data}, errCode = ${data.code}`)
}
```
:::

## [\#](interconnect.html#开发注意事项){.header-anchor} 开发注意事项

interconnect
通信前提要保证快应用和三方应用安卓端两者的包名及签名保持一致。

-   保证快应用 manifest.json 里 package 字段与 需要接入的三方app
    安卓端包名一致。
-   快应用签名需要使用三方应用安卓端签名，可以从.jks中提取证书及私钥，方法如下：

1.  先将 jks 转换成
    p12，执行以下命令，输入相应密码后，在同级目录下生成对应的 p12
    格式文件。

::: {.language-shell .extra-class}
``` language-shell
keytool -importkeystore -srckeystore keystore.jks -destkeystore keystore.p12 -srcstoretype jks -deststoretype pkcs12
```
:::

2.  再将 p12 转 pem，执行以下命令，输入上一步设置的 p12
    文件密码后，在同级目录下生成对应的 pem 格式文件。

::: {.language-shell .extra-class}
``` language-shell
openssl pkcs12 -nodes -in keystore.p12 -out keystore.pem
```
:::

3.  从 pem 格式文件中复制出私钥和证书：\
    把\-\-\-\--BEGIN PRIVATE KEY\-\-\-\--到\-\-\-\--END PRIVATE
    KEY\-\-\-\--的内容复制到private.pem中。\
    把\-\-\-\--BEGIN CERTIFICATE\-\-\-\--到\-\-\-\--END
    CERTIFICATE\-\-\-\--的内容复制到certificate.pem中。

-   如果本地没有安装Openssl或想要更简便的操作流程，我们提供了[在线签名生成工具![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
    .outbound} [(opens new
    window)]{.sr-only}](https://cdn.hybrid.xiaomi.com/aiot-ide/signature-generate-tool/v2/index.html){target="_blank"
    rel="noopener noreferrer"}。该工具是一个基于WebAssembly编写的Web应用，它可以在浏览器环境中直接生成
    pem
    格式的私钥和证书，无需将签名文件和密码上传到远程服务器，充分保证了用户的隐私安全。使用在线签名生成工具的步骤如下：

    1.  上传 p12 文件并输入对应的密码；

    2.  点击"生成签名"按钮，等待签名生成成功弹窗出现；

    3.  点击"下载签名"按钮，下载 pem 格式的私钥和证书；

-   快应用需要将上述生成的私钥 private.pem 和证书 certificate.pem
    放在快应用根目录 /sign/debug 和 /sign/release 下出包测试。

-   在真机测试的时候建议先输入包名uninstall老包再安装新包，可以观察桌面图标卸载的话会删除应用图标保证彻底替换。

参考附录

1.  小米穿戴第三方APP能力开放接口文档：[点击下载![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
    .outbound} [(opens new
    window)]{.sr-only}](https://vela-docs.cnbj1.mi-fds.com/vela-docs/files/%E5%B0%8F%E7%B1%B3%E7%A9%BF%E6%88%B4%E7%AC%AC%E4%B8%89%E6%96%B9APP%E8%83%BD%E5%8A%9B%E5%BC%80%E6%94%BE%E6%8E%A5%E5%8F%A3%E6%96%87%E6%A1%A3_1.4.pdf "下载"){target="_blank"
    rel="noopener noreferrer"}
2.  interconnect开发测试demo：[点击下载![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
    .outbound} [(opens new
    window)]{.sr-only}](https://cdn.cnbj3-fusion.fds.api.mi-img.com/quickapp-vela/interconnect_dev_test_demo.zip "下载"){target="_blank"
    rel="noopener noreferrer"}
:::

::: page-nav
[ ← [数据请求 fetch](fetch.html){.prev} ]{.prev} [ [下载
request](request.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](interconnect.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](interconnect.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](interconnect.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[interconnect.instance()](interconnect.html#interconnect-instance "interconnect.instance()")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[connect.getReadyState(OBJECT)](interconnect.html#connect-getreadystate-object "connect.getReadyState(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[connect.diagnosis(OBJECT)](interconnect.html#connect-diagnosis-object "connect.diagnosis(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[connect.send(OBJECT)](interconnect.html#connect-send-object "connect.send(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[事件](interconnect.html#事件 "事件")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[connect.onmessage](interconnect.html#connect-onmessage "connect.onmessage")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[connect.onopen](interconnect.html#connect-onopen "connect.onopen")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[connect.onclose](interconnect.html#connect-onclose "connect.onclose")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[connect.onerror](interconnect.html#connect-onerror "connect.onerror")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[开发注意事项](interconnect.html#开发注意事项 "开发注意事项")
:::
:::
:::

::: global-ui
:::
:::
