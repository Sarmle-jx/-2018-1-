# 介绍

------

MuiPlayer 是一款 HTML5 视频播放插件，其默认配置了精美可操作的的播放控件，涉及了常用的播放场景，例如全屏播放、播放快进、循环播放、音量调节、视频解码等功能。

<ClientOnly><Player-Default></Player-Default></ClientOnly>

播放器的设计兼容了在 PC、Mobile 端运行，提供了 “移动端” 以及 “PC端” 两类扩展插件，因此你也可应用于在 Android、Ios 的    Webview 中使用。

如果你的应用是运行在 [html5 plus](http://www.html5plus.org/doc/zh_cn/runtime.html) 环境中，那么你使用该播放插件将会默认得到更多原生 api 的支持，例如播放控制设备音量、全屏时横竖屏播放、沉浸式播放等。你也可以使用原生与网页交互的方式来控制视频以及设备功能，MuiPlayer 提供了所有事件触发的回调函数，你需要在这里作一些自己的控制。

# 特点

MuiPlayer 帮助我们解决了日常 H5 Video 应用开发中的常见的一些大量问题：

1. 各浏览器平台播放 ui 不能统一
2. ui 扩展之间以及状态处理容易产生冲突
3. 在不同环境下（android、ios、pc）针对 h5 video api 可能触发事件的时机尽不相同
4. 媒体格式存在各种兼容问题，muiplayer 处理了大多数在不同环境下播放的兼容问题
5. 重复踩踏在开发 h5 video 过程中的一些坑，我们提供了一套完好的解决方案，让开发者少走一些弯路

