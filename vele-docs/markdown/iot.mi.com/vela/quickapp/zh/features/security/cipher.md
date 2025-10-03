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
    -   [解压缩 zip](../system/zip.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [安全](index.html){.sidebar-heading .clickable .router-link-active}
    -   [密码算法 crypto](crypto.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [其他](../other/index.html){.sidebar-heading .clickable}
    -   [音频 audio](../other/audio.html){.sidebar-link}
    -   [弹窗 prompt](../other/prompt.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](cipher.html#密码算法-cipher){.header-anchor} 密码算法 cipher

## [\#](cipher.html#接口声明){.header-anchor} 接口声明

::: {.language-json .extra-class}
``` language-json
{ "name": "system.cipher" }
```
:::

## [\#](cipher.html#导入模块){.header-anchor} 导入模块

::: {.language-javascript .extra-class}
``` language-javascript
import cipher from '@system.cipher' 
// 或 
const cipher = require('@system.cipher')
```
:::

## [\#](cipher.html#接口定义){.header-anchor} 接口定义

### [\#](cipher.html#cipher-rsa-object){.header-anchor} cipher.rsa(OBJECT) {#cipher-rsa-object}

RSA 加解密。不支持分段加密，内容超长会出错

#### [\#](cipher.html#参数){.header-anchor} 参数：

  参数名     类型       必填   说明
  ---------- ---------- ------ --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  action     String     是     加解密类型，两个可选值：encrypt：加密，decrypt：解密
  text       String     是     待加密或解密的文本内容。待加密的文本内容应该是一段普通文本，长度不能超过 keySize / 8 - 66，其中 keySize 是秘钥的长度（例如秘钥长度为 1024 时，text 不能超过 62 个字节）。待解密的文本内容应该是经过 base64 编码的一段二进制值。base64 编码使用默认风格，下同
  key        String     是     加密或解密使用到的 RSA 密钥，经过 base64 编码后生成的字符串。加密时 key 为公钥，解密时 key 为私钥
  success    Function   否     成功回调
  fail       Function   否     失败回调
  complete   Function   否     执行结束后的回调

#### [\#](cipher.html#success-返回值){.header-anchor} success 返回值：

  参数名   类型     说明
  -------- -------- -----------------------------------------------------------------------------------------------------------------------------------------------------
  text     String   经过加密或解密后生成的文本内容。加密后内容是经过 base64 编码的一段二进制值，解密后内容是一段普通文本。如果解密后的内容不能转化为 utf-8 字符串会出错

#### [\#](cipher.html#fail-返回错误代码){.header-anchor} fail 返回错误代码：

  错误码   说明
  -------- --------------
  202      输入参数错误

#### [\#](cipher.html#示例){.header-anchor} 示例：

::: {.language-javascript .extra-class}
``` language-javascript
//加密
cipher.rsa({
  action: 'encrypt',
  //待加密的文本内容
  text: 'hello',
  //base64编码后的加密公钥
  key:
    'MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQDc7GR2MrfAoefES+wrs1ns2afT\n' +
    'eJXSfIkEHfPXG9fVFjaws1ho4KcZfsxlA0+SXvc83f2SVGCuzULmM2lxxRCtcUN/\n' +
    'h7SoaYEeluhqFimL2AEjfSwINHCLqObJkcjCfoZpE1JCehPiDOJsyT50Auc08h/4\n' +
    'jHQfanyC1nc62LqUCQIDAQAB',
  success: function(data) {
    console.log(`handling success: ${data.text}`)
  },
  fail: function(data, code) {
    console.log(`### cipher.rsa fail ### ${code}: ${data}`)
  }
})

//解密：
cipher.rsa({
  action: 'decrypt',
  //待解密的内容，是base64编码后的一段二进制值，解密后是文本内容“hello”
  text:
    'CUg3tTxTIdpCfreIxIBdws3uhd5qXLwcrVl3XDnQzZFVHyjVVCDHS16rjopaZ4C5xU2Tc8mSDzt7\n' +
    'gp9vBfSwi7bMtSUvXG18DlncsKJFDkJpS5t0PkpS9YrJXrY80Gpe+ME6+6dN9bjgqMljbitDdBRf\n' +
    'S/ZWNI4Q8Q0suNjNkGU=',
  //base64编码后的解密私钥
  key:
    'MIICdwIBADANBgkqhkiG9w0BAQEFAASCAmEwggJdAgEAAoGBANzsZHYyt8Ch58RL\n' +
    '7CuzWezZp9N4ldJ8iQQd89cb19UWNrCzWGjgpxl+zGUDT5Je9zzd/ZJUYK7NQuYz\n' +
    'aXHFEK1xQ3+HtKhpgR6W6GoWKYvYASN9LAg0cIuo5smRyMJ+hmkTUkJ6E+IM4mzJ\n' +
    'PnQC5zTyH/iMdB9qfILWdzrYupQJAgMBAAECgYEAkibhH0DWR13U0gvYJeD08Lfd\n' +
    'Sw1PMHyquEqIcho9Yv7bF3LOXjOg2EEGPx09mvuwXFgP1Kp1e67XPytr6pQQPzK7\n' +
    'XAPcLPx80R/ZjZs8vNFndDOd1HgD3vSVmYQarNzmKi72tOUWMPevsaFXPHo6Xx3X\n' +
    '8x0wYb7XuBsQguRctTECQQD7GWX3JUiyo562iVrpTDPOXsrUxmzCrgz2OZildxMd\n' +
    'Pp/PkyDrx7mEXTpk4K/XnQJ3GpJNi2iDSxDuPSAeJ/aPAkEA4Tw4+1Z43S/xH3C3\n' +
    'nfulYBNyB4si6KEUuC0krcC1pDJ21Gd12efKo5VF8SaJI1ZUQOzguV+dqNsB/JUY\n' +
    'OFfX5wJAB1dKv9r7MR3Peg6x9bggm5vx2h6i914XSuuMJupASM6X5X2rrLj+F3yS\n' +
    'RHi9K1SPyeOg+1tkBtKfABgRZFBOyQJAbuTivUSe73AqTKuHjB4ZF0ubqgEkJ9sf\n' +
    'Q2rekzm9dOFvxjZGPQo1qALX09qATMi1ZN376ukby8ZAnSafLSZ64wJBAM2V37go\n' +
    'Sj44HF76ksRow8gecuQm48NCTGAGTicXg8riKog2GC9y8pMNHAezoR9wXJF7kk+k\n' +
    'lz5cHyoMZ9mcd30=',
  success: function(data) {
    console.log(`handling success: ${data.text}`)
  },
  fail: function(data, code) {
    console.log(`### cipher.rsa fail ### ${code}: ${data}`)
  }
})
```
:::

### [\#](cipher.html#cipher-aes-object){.header-anchor} cipher.aes(OBJECT) {#cipher-aes-object}

AES 加解密。支持分段加密

#### [\#](cipher.html#参数-2){.header-anchor} 参数： {#参数-2}

  参数名           类型       必填   说明
  ---------------- ---------- ------ -------------------------------------------------------------------------------------------------------------------------------------------------
  action           String     是     加解密类型，两个可选值：encrypt：加密，decrypt：解密
  text             String     是     待加密或解密的文本内容。待加密的文本内容应该是一段普通文本。待解密的文本内容应该是经过 base64 编码的一段二进制值。base64 编码使用默认风格，下同
  key              String     是     加密或解密使用到的密钥，经过 base64 编码后生成的字符串
  transformation   String     否     AES 算法的加密模式和填充项，默认为\"AES/CBC/PKCS5Padding\"
  iv               String     否     AES 加解密的初始向量，经过 base64 编码后的字符串，默认值为 key 值
  ivOffset         Integer    否     AES 加解密的初始向量偏移，默认值为 0
  ivLen            Integer    否     AES 加解密的初始向量字节长度，默认值为 16
  success          Function   否     成功回调
  fail             Function   否     失败回调
  complete         Function   否     执行结束后的回调

#### [\#](cipher.html#success-返回值-2){.header-anchor} success 返回值： {#success-返回值-2}

  参数名   类型     说明
  -------- -------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------
  text     String   经过加密或解密后生成的文本内容。加密后内容是经过 base64 编码的一段二进制值，解密后内容是一段普通文本。如果解密后的内容不能转化为 utf-8 字符串会出错（CODE：200）

#### [\#](cipher.html#fail-返回错误代码-2){.header-anchor} fail 返回错误代码： {#fail-返回错误代码-2}

  错误码   说明
  -------- ----------------------------------------
  200      一般性错误，在加解密出错时会返回此错误
  202      参数错误

#### [\#](cipher.html#示例-2){.header-anchor} 示例： {#示例-2}

::: {.language-javascript .extra-class}
``` language-javascript
//加密
cipher.aes({
  action: 'encrypt',
  //待加密的文本内容
  text: 'hello',
  //base64编码后的密钥
  key: 'NDM5Qjk2UjAzMEE0NzVCRjlFMkQwQkVGOFc1NkM1QkQ=',
  transformation: 'AES/CBC/PKCS5Padding',
  ivOffset: 0,
  ivLen: 16,
  success: data => {
    console.log(`handling success: ${data.text}`)
  },
  fail: (data, code) => {
    console.log(`### cipher.aes fail ### ${code}: ${data}`)
  }
})

//解密：
cipher.aes({
  action: 'decrypt',
  //待解密的内容，是base64编码后的一段二进制值
  text:
    'CUg3tTxTIdpCfreIxIBdws3uhd5qXLwcrVl3XDnQzZFVHyjVVCDHS16rjopaZ4C5xU2Tc8mSDzt7\n' +
    'gp9vBfSwi7bMtSUvXG18DlncsKJFDkJpS5t0PkpS9YrJXrY80Gpe+ME6+6dN9bjgqMljbitDdBRf\n' +
    'S/ZWNI4Q8Q0suNjNkGU=',
  //base64编码后的密钥
  key: 'NDM5Qjk2UjAzMEE0NzVCRjlFMkQwQkVGOFc1NkM1QkQ=',
  transformation: 'AES/CBC/PKCS5Padding',
  ivOffset: 0,
  ivLen: 16,
  success: data => {
    this.dealTxt = data.text
  },
  fail: (data, code) => {
    prompt.showToast({
      message: '解密失败, code=' + code + ':' + data
    })
  }
})
```
:::
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[接口声明](cipher.html#接口声明 "接口声明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[导入模块](cipher.html#导入模块 "导入模块")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[接口定义](cipher.html#接口定义 "接口定义")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[cipher.rsa(OBJECT)](cipher.html#cipher-rsa-object "cipher.rsa(OBJECT)")
:::

::: {.vuepress-toc-item .vuepress-toc-h3}
[cipher.aes(OBJECT)](cipher.html#cipher-aes-object "cipher.aes(OBJECT)")
:::
:::
:::

::: global-ui
:::
:::
