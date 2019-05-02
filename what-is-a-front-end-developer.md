---
description: 本章提供了前端开发和前端开发者规程的基本说明
---

# 第1章-什么是前端开发工程师？

> 前端Web开发（也称为客户端开发）是为网站或 Web 应用生成 HTML、CSS 和 JavaScript 以便用户查看并与之直接交互的相关实践的统称，前端开发所面临的挑战在于，用于创建网站前端的工具和技术不断变化，需要开发人员需要持续关注该领域的开发方式与发展趋势。
>
> 设计网站的目的是确保当用户打开网站时，网站会以易于用户阅读且恰当的格式呈现相关信息，用户现在使用具有不同屏幕尺寸/分辨率的各种设备，这使得设计者在设计网页时必须考虑这些方面，这使得开发变的更加复杂，他们需要确保网站在不同的浏览器（跨浏览器），不同的操作系统（跨平台）和不同的设备（跨设备）中都能正确显示，这需要在开发者在开发时进行细致的规划。
>
> [_https://en.wikipedia.org/wiki/Front-end\_web\_development_](https://en.wikipedia.org/wiki/Front-end_web_development)

![&#x56FE;&#x7247;&#x6765;&#x6E90;&#xFF1A;https://www.upwork.com/hiring/development/front-end-developer/](https://content-static.upwork.com/blog/uploads/sites/3/2015/05/05110037/Front-end-dev1.png)

## **前端开发者**  <a id="html-css--javascript"></a>

前端开发者使用Web技术（即 [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)，[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) 和 [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)）来开发网站与 Web 应用，这些技术通常在[开放 Web 平台](https://en.wikipedia.org/wiki/Open_Web_Platform)上运行，或者充当非 Web 平台环境（即 [React Native](https://facebook.github.io/react-native/)）的编译输入端。

初学者通过学习构建依赖于 HTML、CSS、JavaScript 的网站或 Web 应用踏足前端开发领域，这些应用通常运行在 [Web 浏览器](https://en.wikipedia.org/wiki/Web_browser)上，但也可以运行在[无头浏览器](https://en.wikipedia.org/wiki/Headless_browser)、[WebView](http://developer.telerik.com/featured/what-is-a-webview/) 或作为原生运行环境的编译输入端，下面分别解释这四种运行场景：

**Web浏览器\(最流行的\)**

Web 浏览器是用于检索，呈现和遍历位于 [WWW](https://en.wikipedia.org/wiki/World_Wide_Web) 上的信息的软件，通常运行在台式机、笔记本电脑、平板电脑或手机上，​​但近几年浏览器可以说是随处可见（例如冰箱，汽车等）。

常见的 Web 浏览器有以下这几种（按照[市场份额](https://en.wikipedia.org/wiki/Usage_share_of_web_browsers#Summary_tables)自上至下排序）:

* [Chrome](http://www.google.com/chrome/)
* [Safari](http://www.apple.com/safari/)
* [Internet Explorer](https://en.wikipedia.org/wiki/Internet_Explorer) （注: 并非 [Edge](http://dev.modern.ie/), 此处特指 IE 9 到 IE 11\)
* [Firefox](https://www.mozilla.org/firefox/)
* [Edge](https://www.microsoft.com/en-us/windows/microsoft-edge)

**无头浏览器**

无头浏览器是**没有图形用户界面**的网络浏览器，可以通过编程的形式从命令行界面控制网页浏览器以实现网页自动化操作（例如，功能测试，抓取，单元测试等）。无头浏览器可以被视为以编程方式运行在命令行，且能够检索和遍历网页代码的浏览器。

常见的无头浏览器有以下几种：

* [Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)
* [Zombie](https://github.com/assaf/zombie)
* [slimerjs](http://slimerjs.org/)
* [puppeteer](https://github.com/GoogleChrome/puppeteer)

**Webviews**

[Webviews](http://developer.telerik.com/featured/what-is-a-webview/) 被原生系统在原生 App 中调用以运行一个 Web 页面，可以把 [Webview](http://developer.telerik.com/featured/what-is-a-webview/) 想象成一个 iframe，或者一个运行在浏览器上的单 Tab 页被嵌入到设备上运行的原生应用程序中（如 [iOS](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIWebView_Class/)、[android](http://developer.android.com/reference/android/webkit/WebView.html)、[windows](https://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.controls.webview.aspx)）。

最流行的 [Webview](http://developer.telerik.com/featured/what-is-a-webview/) 开发解决方案有以下几种：

* [Cordova](https://cordova.apache.org/) \(通常用于原生手机/平板电脑应用开发）
* [NW.js](https://github.com/nwjs/nw.js)（通常用于桌面应用开发）
* [Electron](http://electron.atom.io/)（通常用于桌面应用开发）

**基于 Web 技术的原生开发**

最后，前端开发人员可以运用从 Web 浏览器开发中学到的知识来为非浏览器引擎（即Web平台）驱动的环境编写代码。最近，开发环境正在被设想为使用 Web 技术（例如，CSS 和 JavaScript）开发原生应用，但不引入 Web 引擎。

这类环境的部分示例有以下这些：

* [Flutter](https://flutter.io/)
* [React Native](https://facebook.github.io/react-native/)
* [NativeScript](https://www.nativescript.org/)

> 注**:**
>
> 1. 为确保您能准确理解“Web 平台“的含义，请阅读 ["Open Web Platform"](https://en.wikipedia.org/wiki/Open_Web_Platform)，探索构成 Web 平台的[相关技术](https://platform.html5.org/)。

