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
[组件](../index.html){.nav-link .router-link-active}
:::

::: nav-item
[JS接口](../../features/index.html){.nav-link}
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
[组件](../index.html){.nav-link .router-link-active}
:::

::: nav-item
[JS接口](../../features/index.html){.nav-link}
:::

::: nav-item
[编程示例](../../samples/index.html){.nav-link}
:::

::: nav-item
[工具](../../tools/index.html){.nav-link}
:::

-   ::: {.section .sidebar-group .depth-0}
    [通用规范](index.html){.sidebar-heading .clickable
    .router-link-active .open}
    -   [通用样式](style.html){.sidebar-link}
    -   [颜色配置](color.html){.active .sidebar-link
        aria-current="page"}
    -   [动画样式](animation-style.html){.sidebar-link}
    -   [背景图样式](background-img-styles.html){.sidebar-link}
    -   [通用属性](properties.html){.sidebar-link}
    -   [通用事件](events.html){.sidebar-link}
    -   [通用方法](methods.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [容器组件](../container/index.html){.sidebar-heading .clickable}
    -   [div](../container/div.html){.sidebar-link}
    -   [list](../container/list.html){.sidebar-link}
    -   [list-item](../container/list-item.html){.sidebar-link}
    -   [scroll](../container/scroll.html){.sidebar-link}
    -   [stack](../container/stack.html){.sidebar-link}
    -   [swiper](../container/swiper.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [基础组件](../basic/index.html){.sidebar-heading .clickable}
    -   [text](../basic/text.html){.sidebar-link}
    -   [span](../basic/span.html){.sidebar-link}
    -   [a](../basic/a.html){.sidebar-link}
    -   [image](../basic/image.html){.sidebar-link}
    -   [image-animator](../basic/image-animator.html){.sidebar-link}
    -   [progress](../basic/progress.html){.sidebar-link}
    -   [marquee](../basic/marquee.html){.sidebar-link}
    -   [chart](../basic/chart.html){.sidebar-link}
    -   [qrcode](../basic/qrcode.html){.sidebar-link}
    -   [barcode](../basic/barcode.html){.sidebar-link}
    :::

-   ::: {.section .sidebar-group .depth-0}
    [表单组件](../form/index.html){.sidebar-heading .clickable}
    -   [input](../form/input.html){.sidebar-link}
    -   [picker](../form/picker.html){.sidebar-link}
    -   [switch](../form/switch.html){.sidebar-link}
    -   [slider](../form/slider.html){.sidebar-link}
    :::

::: {.page role="main"}
::: {.theme-default-content .content__default}
# [\#](color.html#颜色配置){.header-anchor} 颜色配置

Vela JS 应用支持 `rgb()` and `rgba()` 颜色值设置，

开发者可参考[MDN
文档![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtaGlkZGVuPSJ0cnVlIiBmb2N1c2FibGU9ImZhbHNlIiB4PSIwcHgiIHk9IjBweCIgdmlld2JveD0iMCAwIDEwMCAxMDAiIHdpZHRoPSIxNSIgaGVpZ2h0PSIxNSIgY2xhc3M9Imljb24gb3V0Ym91bmQiPjxwYXRoIGZpbGw9ImN1cnJlbnRDb2xvciIgZD0iTTE4LjgsODUuMWg1NmwwLDBjMi4yLDAsNC0xLjgsNC00di0zMmgtOHYyOGgtNDh2LTQ4aDI4di04aC0zMmwwLDBjLTIuMiwwLTQsMS44LTQsNHY1NkMxNC44LDgzLjMsMTYuNiw4NS4xLDE4LjgsODUuMXoiPjwvcGF0aD4gPHBvbHlnb24gZmlsbD0iY3VycmVudENvbG9yIiBwb2ludHM9IjQ1LjcsNDguNyA1MS4zLDU0LjMgNzcuMiwyOC41IDc3LjIsMzcuMiA4NS4yLDM3LjIgODUuMiwxNC45IDYyLjgsMTQuOSA2Mi44LDIyLjkgNzEuNSwyMi45Ij48L3BvbHlnb24+PC9zdmc+){.icon
.outbound} [(opens new
window)]{.sr-only}](https://developer.mozilla.org/zh-CN/docs/Web/CSS/color_value){target="_blank"
rel="noopener noreferrer"}了解更多颜色值的信息。

## [\#](color.html#颜色值格式示例){.header-anchor} 颜色值格式示例

-   `'#f0f'` (#rgb)
-   `'#ff00ff'` (#rrggbb)
-   `'rgb(255, 0, 255)'`
-   `'rgba(255, 255, 255, 1.0)'`
-   `'#f0ff'` (#rgba)
-   `'#ff00ff00'` (#rrggbbaa)

## [\#](color.html#透明){.header-anchor} 透明

`rgba(0,0,0,0)`还有另外一个简写版本：

-   `'transparent'`

## [\#](color.html#颜色名字){.header-anchor} 颜色名字

你也可以用下面的颜色配置：

-    aliceblue (#f0f8ff)
-    antiquewhite (#faebd7)
-    aqua (#00ffff)
-    aquamarine (#7fffd4)
-    azure (#f0ffff)
-    beige (#f5f5dc)
-    bisque (#ffe4c4)
-    black (#000000)
-    blanchedalmond (#ffebcd)
-    blue (#0000ff)
-    blueviolet (#8a2be2)
-    brown (#a52a2a)
-    burlywood (#deb887)
-    cadetblue (#5f9ea0)
-    chartreuse (#7fff00)
-    chocolate (#d2691e)
-    coral (#ff7f50)
-    cornflowerblue (#6495ed)
-    cornsilk (#fff8dc)
-    crimson (#dc143c)
-    cyan (#00ffff)
-    darkblue (#00008b)
-    darkcyan (#008b8b)
-    darkgoldenrod (#b8860b)
-    darkgray (#a9a9a9)
-    darkgreen (#006400)
-    darkgrey (#a9a9a9)
-    darkkhaki (#bdb76b)
-    darkmagenta (#8b008b)
-    darkolivegreen (#556b2f)
-    darkorange (#ff8c00)
-    darkorchid (#9932cc)
-    darkred (#8b0000)
-    darksalmon (#e9967a)
-    darkseagreen (#8fbc8f)
-    darkslateblue (#483d8b)
-    darkslategrey (#2f4f4f)
-    darkturquoise (#00ced1)
-    darkviolet (#9400d3)
-    deeppink (#ff1493)
-    deepskyblue (#00bfff)
-    dimgray (#696969)
-    dimgrey (#696969)
-    dodgerblue (#1e90ff)
-    firebrick (#b22222)
-    floralwhite (#fffaf0)
-    forestgreen (#228b22)
-    fuchsia (#ff00ff)
-    gainsboro (#dcdcdc)
-    ghostwhite (#f8f8ff)
-    gold (#ffd700)
-    goldenrod (#daa520)
-    gray (#808080)
-    green (#008000)
-    greenyellow (#adff2f)
-    grey (#808080)
-    honeydew (#f0fff0)
-    hotpink (#ff69b4)
-    indianred (#cd5c5c)
-    indigo (#4b0082)
-    ivory (#fffff0)
-    khaki (#f0e68c)
-    lavender (#e6e6fa)
-    lavenderblush (#fff0f5)
-    lawngreen (#7cfc00)
-    lemonchiffon (#fffacd)
-    lightblue (#add8e6)
-    lightcoral (#f08080)
-    lightcyan (#e0ffff)
-    lightgoldenrodyellow (#fafad2)
-    lightgray (#d3d3d3)
-    lightgreen (#90ee90)
-    lightgrey (#d3d3d3)
-    lightpink (#ffb6c1)
-    lightsalmon (#ffa07a)
-    lightseagreen (#20b2aa)
-    lightskyblue (#87cefa)
-    lightslategrey (#778899)
-    lightsteelblue (#b0c4de)
-    lightyellow (#ffffe0)
-    lime (#00ff00)
-    limegreen (#32cd32)
-    linen (#faf0e6)
-    magenta (#ff00ff)
-    maroon (#800000)
-    mediumaquamarine (#66cdaa)
-    mediumblue (#0000cd)
-    mediumorchid (#ba55d3)
-    mediumpurple (#9370db)
-    mediumseagreen (#3cb371)
-    mediumslateblue (#7b68ee)
-    mediumspringgreen (#00fa9a)
-    mediumturquoise (#48d1cc)
-    mediumvioletred (#c71585)
-    midnightblue (#191970)
-    mintcream (#f5fffa)
-    mistyrose (#ffe4e1)
-    moccasin (#ffe4b5)
-    navajowhite (#ffdead)
-    navy (#000080)
-    oldlace (#fdf5e6)
-    olive (#808000)
-    olivedrab (#6b8e23)
-    orange (#ffa500)
-    orangered (#ff4500)
-    orchid (#da70d6)
-    palegoldenrod (#eee8aa)
-    palegreen (#98fb98)
-    paleturquoise (#afeeee)
-    palevioletred (#db7093)
-    papayawhip (#ffefd5)
-    peachpuff (#ffdab9)
-    peru (#cd853f)
-    pink (#ffc0cb)
-    plum (#dda0dd)
-    powderblue (#b0e0e6)
-    purple (#800080)
-    rebeccapurple (#663399)
-    red (#ff0000)
-    rosybrown (#bc8f8f)
-    royalblue (#4169e1)
-    saddlebrown (#8b4513)
-    salmon (#fa8072)
-    sandybrown (#f4a460)
-    seagreen (#2e8b57)
-    seashell (#fff5ee)
-    sienna (#a0522d)
-    silver (#c0c0c0)
-    skyblue (#87ceeb)
-    slateblue (#6a5acd)
-    slategray (#708090)
-    snow (#fffafa)
-    springgreen (#00ff7f)
-    steelblue (#4682b4)
-    tan (#d2b48c)
-    teal (#008080)
-    thistle (#d8bfd8)
-    tomato (#ff6347)
-    turquoise (#40e0d0)
-    violet (#ee82ee)
-    wheat (#f5deb3)
-    white (#ffffff)
-    whitesmoke (#f5f5f5)
-    yellow (#ffff00)
-    yellowgreen (#9acd32)
:::

::: page-nav
[ ← [通用样式](style.html){.prev} ]{.prev} [
[动画样式](animation-style.html) → ]{.next}
:::
:::

::: toc
::: on-this-page
快速导航
:::

::: {.vuepress-toc-item .vuepress-toc-h2 .active}
[颜色值格式示例](color.html#颜色值格式示例 "颜色值格式示例")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[透明](color.html#透明 "透明")
:::

::: {.vuepress-toc-item .vuepress-toc-h2}
[颜色名字](color.html#颜色名字 "颜色名字")
:::
:::
:::

::: global-ui
:::
:::
