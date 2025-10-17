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
    [安全](index.html){.sidebar-heading .clickable .router-link-active
    .open}
    -   [密码算法 crypto](crypto.html){.active .sidebar-link
        aria-current="page"}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [其他](../other/index.html){.sidebar-heading .clickable}
    -   [音频 audio](../other/audio.html){.sidebar-link}
    -   [弹窗 prompt](../other/prompt.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](crypto.html#密码算法-crypto){.header-anchor} 密码算法 crypto

## [\#](crypto.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.crypto" }
```
:::

## [\#](crypto.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import crypto from '@system.crypto' 
// 或 
const crypto = require('@system.crypto')
```
:::

## [\#](crypto.html#接口定义){.header-anchor} 接口定义

### [\#](crypto.html#crypto-hashdigest-object){.header-anchor} crypto.hashDigest(OBJECT) {#crypto-hashdigest-object}

创建数据的哈希摘要

#### [\#](crypto.html#参数){.header-anchor} 参数：

  ----------------------------------------------------------------------------------------------
  参数名            类型                必填              说明
  ----------------- ------------------- ----------------- --------------------------------------
  data              String/Uint8Array   否                待计算内容，和uri二者必须有一个

  uri               String              否                待计算文件地址，和data二者必须有一个

  algo              String              否                算法 默认： SHA256\
                                                          可选：MD5， SHA1，SHA256，SHA512
  ----------------------------------------------------------------------------------------------

#### [\#](crypto.html#返回值){.header-anchor} 返回值：

  类型     说明
  -------- ------------------------
  String   经过计算生成的摘要内容

#### [\#](crypto.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
const digest = crypto.hashDigest({
  data: 'hello',
  algo: 'MD5'
})
```
:::

### [\#](crypto.html#crypto-hmacdigest-object){.header-anchor} crypto.hmacDigest(OBJECT) {#crypto-hmacdigest-object}

创建加密 HMAC 摘要

#### [\#](crypto.html#参数-2){.header-anchor} 参数： {#参数-2}

  ----------------------------------------------------------------------------
  参数名            类型              必填              说明
  ----------------- ----------------- ----------------- ----------------------
  data              String            是                待计算数据

  algo              String            否                算法 默认： SHA256\
                                                        可选：MD5，
                                                        SHA1，SHA256，SHA512

  key               String            是                密钥

  success           Function          否                成功回调

  fail              Function          否                失败回调

  complete          Function          否                完成回调
  ----------------------------------------------------------------------------

#### [\#](crypto.html#success-返回值-object){.header-anchor} success 返回值 Object：

  参数值   类型     说明
  -------- -------- ------
  data     String   摘要

#### [\#](crypto.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
crypto.hmacDigest({
  data: 'hello',
  algo: 'SHA256',
  key: 'a secret',
  success: function(res) {
    console.log(`### crypto.hmacDigest success:`, res.data)
  },
  fail: function(data, code) {
    console.log(`### crypto.hmacDigest fail ### ${code}: ${data}`)
  }
})
```
:::

### [\#](crypto.html#crypto-sign-object){.header-anchor} crypto.sign(OBJECT) {#crypto-sign-object}

用于生成签名

#### [\#](crypto.html#参数-3){.header-anchor} 参数： {#参数-3}

  ----------------------------------------------------------------------------------------------
  参数名            类型                必填              说明
  ----------------- ------------------- ----------------- --------------------------------------
  data              String/Uint8Array   否                被签名文本，和uri二者必须有一个

  uri               String              否                被签名文件地址，和data二者必须有一个

  algo              String              否                签名算法，默认：\'RSA-SHA256\'\
                                                          可选：RSA-MD5，
                                                          RSA-SHA1，RSA-SHA256，RSA-SHA512

  privateKey        String              是                私钥

  success           Function            否                成功回调

  fail              Function            否                失败回调

  complete          Function            否                完成回调
  ----------------------------------------------------------------------------------------------

#### [\#](crypto.html#success-返回值-object-2){.header-anchor} success 返回值 Object： {#success-返回值-object-2}

  参数值   类型                说明
  -------- ------------------- -------------------------------------------------------------------------------------------------
  data     String/Uint8Array   如果输入为字符串，则返回经过base64编码的字符串；否则返回Uint8Array；如果只传uri，默认返回string

#### [\#](crypto.html#示例-3){.header-anchor} 示例： {#示例-3}

::: {.language-javascript .extra-class}
``` language-javascript
crypto.sign({
  data: 'hello',
  algo: 'RSA-SHA256',
  privateKey: 'a secret',
  success: function(res) {
    console.log(`### crypto.sign success:`, res.data)
  },
  fail: function(data, code) {
    console.log(`### crypto.sign fail ### ${code}: ${data}`)
  }
})
```
:::

### [\#](crypto.html#crypto-verify-object){.header-anchor} crypto.verify(OBJECT) {#crypto-verify-object}

用于验证签名

#### [\#](crypto.html#参数-4){.header-anchor} 参数： {#参数-4}

  ----------------------------------------------------------------------------------------------
  参数名            类型                必填              说明
  ----------------- ------------------- ----------------- --------------------------------------
  data              String/Uint8Array   否                被签名文本，和uri二者必须有一个

  uri               String              否                被签名文件地址，和data二者必须有一个

  algo              String              否                签名算法，默认：\'RSA-SHA256\'\
                                                          可选：RSA-MD5，
                                                          RSA-SHA1，RSA-SHA256，RSA-SHA512

  signature         String/Uint8Array   是                签名

  publicKey         String              是                公钥

  success           Function            否                成功回调

  fail              Function            否                失败回调

  complete          Function            否                完成回调
  ----------------------------------------------------------------------------------------------

#### [\#](crypto.html#success-返回值-boolean){.header-anchor} success 返回值 Boolean：

  类型      说明
  --------- -------------------------------------
  Boolean   校验结果，通过为true，不通过为false

#### [\#](crypto.html#示例-4){.header-anchor} 示例： {#示例-4}

::: {.language-javascript .extra-class}
``` language-javascript
crypto.verify({
  data: 'hello',
  algo: 'RSA-SHA256',
  publicKey: 'public key',
  signature: 'signature',
  success: function(data) {
    console.log(`### crypto.verify success:`, data)
  },
  fail: function(data, code) {
    console.log(`### crypto.verify fail ### ${code}: ${data}`)
  }
})
```
:::

### [\#](crypto.html#crypto-encrypt-object){.header-anchor} crypto.encrypt(OBJECT) {#crypto-encrypt-object}

加密

#### [\#](crypto.html#参数-5){.header-anchor} 参数： {#参数-5}

  --------------------------------------------------------------------------------
  参数名            类型                必填              说明
  ----------------- ------------------- ----------------- ------------------------
  data              String/Uint8Array   是                待加密数据

  algo              String              否                加密算法 默认： RSA\
                                                          可选：RSA， AES

  key               String              是                加密使用到的密钥，经过
                                                          base64
                                                          编码后生成的字符串

  options           Object              否                加密参数

  success           Function            否                成功回调

  fail              Function            否                失败回调

  complete          Function            否                完成回调
  --------------------------------------------------------------------------------

#### [\#](crypto.html#rsa-参数options){.header-anchor} RSA 参数options：

  参数名           类型     必填   说明
  ---------------- -------- ------ -------------------------------------------------------------
  transformation   String   否     RSA 算法的加密模式和填充项，默认为\"RSA/None/PKCS1Padding\"

#### [\#](crypto.html#aes-参数options){.header-anchor} AES 参数options：

  参数名           类型     必填   说明
  ---------------- -------- ------ -------------------------------------------------------------------
  transformation   String   否     AES 算法的加密模式和填充项，默认为\"AES/CBC/PKCS7Padding\"
  iv               String   否     AES 加解密的初始向量，经过 base64 编码后的字符串，默认值为 key 值
  ivOffset         Number   否     AES 加解密的初始向量偏移，整数，默认值为 0
  ivLen            Number   否     AES 加解密的初始向量字节长度，整数，默认值为 16

#### [\#](crypto.html#success-返回值-object-3){.header-anchor} success 返回值 Object： {#success-返回值-object-3}

  参数值   类型                说明
  -------- ------------------- --------------------------------------------------------------------
  data     String/Uint8Array   如果输入为字符串，则返回经过base64编码的字符串；否则返回Uint8Array

#### [\#](crypto.html#示例-5){.header-anchor} 示例： {#示例-5}

::: {.language-javascript .extra-class}
``` language-javascript
crypto.encrypt({
  //待加密的文本内容
  data: 'hello',
  //base64编码后的加密公钥
  key: crypto.btoa('KEYKEYKEYKEYKEYK'),
  algo: 'AES',
  success: function(res) {
    console.log(`### crypto.encrypt success:`, res.data)
  },
  fail: function(data, code) {
    console.log(`### crypto.encrypt fail ### ${code}: ${data}`)
  }
})
```
:::

### [\#](crypto.html#crypto-decrypt-object){.header-anchor} crypto.decrypt(OBJECT) {#crypto-decrypt-object}

解密

#### [\#](crypto.html#参数-6){.header-anchor} 参数： {#参数-6}

  --------------------------------------------------------------------------------------
  参数名            类型                必填              说明
  ----------------- ------------------- ----------------- ------------------------------
  data              String/Uint8Array   是                待解密数据

  algo              String              否                解密算法 默认： RSA\
                                                          可选：RSA， AES

  key               String              是                加密或解密使用到的密钥，经过
                                                          base64 编码后生成的字符串

  options           Object              否                解密参数

  success           Function            否                成功回调

  fail              Function            否                失败回调

  complete          Function            否                完成回调
  --------------------------------------------------------------------------------------

#### [\#](crypto.html#rsa-参数options-2){.header-anchor} RSA 参数options： {#rsa-参数options-2}

  参数名           类型     必填   说明
  ---------------- -------- ------ -------------------------------------------------------------
  transformation   String   否     RSA 算法的加密模式和填充项，默认为\"RSA/None/PKCS1Padding\"

#### [\#](crypto.html#aes-参数options-2){.header-anchor} AES 参数options： {#aes-参数options-2}

  参数名           类型     必填   说明
  ---------------- -------- ------ -------------------------------------------------------------------
  transformation   String   否     AES 算法的加密模式和填充项，默认为\"AES/CBC/PKCS7Padding\"
  iv               String   否     AES 加解密的初始向量，经过 base64 编码后的字符串，默认值为 key 值
  ivOffset         Number   否     AES 加解密的初始向量偏移，整数，默认值为 0
  ivLen            Number   否     AES 加解密的初始向量字节长度，整数，默认值为 16

#### [\#](crypto.html#success-返回值-object-4){.header-anchor} success 返回值 Object： {#success-返回值-object-4}

  参数值   类型                说明
  -------- ------------------- --------------------------------------------------------------------
  data     String/Uint8Array   如果输入为字符串，则返回经过base64编码的字符串；否则返回Uint8Array

#### [\#](crypto.html#示例-6){.header-anchor} 示例： {#示例-6}

::: {.language-javascript .extra-class}
``` language-javascript
crypto.decrypt({
  //待解密的内容
  data: 'WB96uM08PfYIHu5G1p6YwA==',
  //base64编码后的加密公钥
  key: crypto.btoa('KEYKEYKEYKEYKEYK'),
  algo: 'AES',
  success: function(res) {
    console.log(`### crypto.decrypt success:`, res.data)
  },
  fail: function(data, code) {
    console.log(`### crypto.decrypt fail ### ${code}: ${data}`)
  }
})
```
:::

### [\#](crypto.html#crypto-btoa-string){.header-anchor} crypto.btoa(STRING) {#crypto-btoa-string}

从String对象中创建一个 base-64 编码的 ASCII
字符串，其中字符串中的每个字符都被视为一个二进制数据字节

#### [\#](crypto.html#参数-7){.header-anchor} 参数： {#参数-7}

  类型     必填   说明
  -------- ------ ------------
  String   是     待编码文本

#### [\#](crypto.html#返回值-string){.header-anchor} 返回值 String：

  类型     说明
  -------- --------------------
  String   经过编码之后的结果

#### [\#](crypto.html#示例-7){.header-anchor} 示例： {#示例-7}

::: {.language-javascript .extra-class}
``` language-javascript
const encodeData = crypto.btoa('hello')
```
:::

### [\#](crypto.html#crypto-atob-string){.header-anchor} crypto.atob(STRING) {#crypto-atob-string}

对经过 base-64 编码的字符串进行解码

#### [\#](crypto.html#参数-8){.header-anchor} 参数： {#参数-8}

  类型     必填   说明
  -------- ------ ------------
  String   是     待解码文本

#### [\#](crypto.html#返回值-string-2){.header-anchor} 返回值 String： {#返回值-string-2}

  类型     说明
  -------- --------------------
  String   经过解码之后的结果

#### [\#](crypto.html#示例-8){.header-anchor} 示例： {#示例-8}

::: {.language-javascript .extra-class}
``` language-javascript
const encodeString = crypto.btoa('hello')
const res = crypto.atob(encodeString)
```
:::

## [\#](crypto.html#支持明细){.header-anchor} 支持明细

  设备产品                   说明
  -------------------------- --------
  小米 S1 Pro 运动健康手表   不支持
  小米手环 8 Pro             不支持
  Xiaomi Watch S3            支持
  Redmi Watch 4              不支持
  小米腕部心电血压记录仪     不支持
  Xiaomi Watch S4            支持
  REDMI Watch 5              支持
:::

::: page-nav
[ ← [解压缩 zip](../system/zip.html){.prev} ]{.prev} [ [音频
audio](../other/audio.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](crypto.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](crypto.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](crypto.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.hashDigest(OBJECT)](crypto.html#crypto-hashdigest-object "crypto.hashDigest(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.hmacDigest(OBJECT)](crypto.html#crypto-hmacdigest-object "crypto.hmacDigest(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.sign(OBJECT)](crypto.html#crypto-sign-object "crypto.sign(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.verify(OBJECT)](crypto.html#crypto-verify-object "crypto.verify(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.encrypt(OBJECT)](crypto.html#crypto-encrypt-object "crypto.encrypt(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.decrypt(OBJECT)](crypto.html#crypto-decrypt-object "crypto.decrypt(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.btoa(STRING)](crypto.html#crypto-btoa-string "crypto.btoa(STRING)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[crypto.atob(STRING)](crypto.html#crypto-atob-string "crypto.atob(STRING)")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[支持明细](crypto.html#支持明细 "支持明细")
:::
:::
:::

::: global-ui
:::
:::
