---
description: 本章将从“如何成为前端开发人员”开始，逐步分解并概要描述前端工程实践。
---

# 第2章-前端开发实践-概述

## 2.1 如何成为前端开发工程师？

初学者如何成为前端开发工程师？嗯，这很复杂，先来看看这张线路图：



时至今日，我们依旧不能通过大学课堂得到一份前端开发工程师的学位，而且我很少听说有前端开发者在拿到计算机科学学位/视觉设计学位后就能立刻编写出专业的 HTML、CSS、JavaScript 代码。据我所见，今天的大部分前端从业者似乎都是自学成才的，或者从计算机科学领域/视觉设计领域转入前端领域的。

![&#x56FE;&#x7247;&#x6765;&#x6E90;&#xFF1A;https://github.com/kamranahmedse/developer-roadmap](.gitbook/assets/frontend.png)

如果你希望从今天开始前端之旅，希望你能够大致遵循下面列出的学习流程（第 3 章和第 4 章将深入展开每项，并介绍更多相关学习资源）。

1. 大致了解 Web 平台的工作原理，确保你能理解 [HTML, CSS, DOM, JavaScript, 域名, DNS, URLs, HTTP, 浏览器, 以及服务器/托管](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web)的基本概念，先不要对其进行深入研究，只需要了解每个部分如何运转，以及它们是如何被组合到一起的，从构建简单的 Web 页面开始。
2. [学习 HTML](https://developer.mozilla.org/zh-CN/docs/learn/HTML)
3. [学习 CSS](https://developer.mozilla.org/zh-CN/docs/Learn/CSS)
4. [学习 JavaScript](https://youtu.be/QjKH1J77gjI?list=PL055Epbe6d5bQubu5EWf_kUNA3ef_qbmL)
5. 学习 DOM
6. 学习用户界面设计的基本原理（如 UI 元件、交互设计、用户体验设计与可用性）
7. 学习 CLI/命令行工具
8. 学习软件工程的相关实践（例如：应用程序设计/架构、模板、Git、测试、监控、自动化、代码质量、开发方法）
9. 根据你的个人喜好自行定制你的工具箱（例如 Webpack，React 和 Mobx）
10. 学习 Node.js

一个关于学习的小建议：[在学习抽象前，先学习底层技术](https://youtu.be/QjKH1J77gjI?list=PL055Epbe6d5bQubu5EWf_kUNA3ef_qbmL)。

比如说：先学习 DOM，再学习 jQuery， 先学习 CSS，再学习 SASS，先学习 HTML，再学习 JSX，先学习 JavaScript，再学习 TypeScript，先学习 JavaScript ES6 模版，再学习 HandleBars，先学习 UI 元件，再学习 BootStrap。

最近出现了许多未经认证的，学费高昂的前端代码训练营/培训机构，他们所提供的成为前端开发人员的途径通常是教师指导的课程，与正规讲师所提供的更传统的学习方式（即课程大纲，考试，测验，项目，团队项目，成绩等）。

记住，如果你正在考虑昂贵的培训计划，那就通过网络的形式学习吧！所有需要学习的内容都可以从网络上获取，成本极低甚至为零。但是，如果你需要有人告诉你如何以低成本获取学习资源，并时刻督促你学习的话，你应该考虑传统的由讲师主导的课程。除此之外，我想不到有其他任何一种职业能通过互联网以近乎免费的方式进行学习的，只需[每月 20 美元的会员](https://frontendmasters.com/join/)，以及强烈的求知欲。

举个例子，如果你想从今天开始学习之旅，下面这些课程都可以用于自学：

* [Getting started with the Web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web) \[文章\]
* [So, You Want to be a Front-End Engineer](https://www.youtube.com/watch?v=Lsg84NtJbmI) \[视频\]
* [Frontend Masters Learning Path](https://frontendmasters.com/learn) \[视频\]\[$\]
* [Introduction to Web Development](https://frontendmasters.com/courses/web-development-v2/) \[视频\]\[$\]
* [Treehouse Techdegree](https://teamtreehouse.com/techdegree/front-end-web-development-2) \[视频\]\[$\]
* [Front-End Web Developer Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001) \[视频\]\[$\]
* [Become a Front-End Web Developer](https://www.lynda.com/learning-paths/Web/become-a-front-end-web-developer) \[视频\]\[$\]
* [freeCodeCamp](https://learn.freecodecamp.org/) \[互动形式\]

一开始，你应该恐惧大多数将复杂性隐藏起来的事物，抽象（如：jQuery）在低级开发者的手中依旧能展现出一些进阶技巧，同时一直隐藏着这样一个事实：开发人员对底层概念的理解不够深入。

假设在这个过程中，您不仅要学习，还要进行相应的实践与工具调研，有些人建议仅通过实践的方式去学习，还有些人建议仅学习如何实践，而我建议你根据自身情况去寻找两者间的平衡点。但是，这两者间一定是相辅相成的，因此，不要只是学习纸面知识，实践是必要的。理论 - 实践 - 理论 - 实践，事物的快速更迭需要我们不断重复这个流程，这也就是为什么“学习底层知识，而非学习抽象知识”如此重要。

## 2.2 前端开发相关职位

前端开发界中存在两种类型截然不同，但都被归为前端开发者的开发群体，[他们之间的分歧已经酝酿了好几年了](https://css-tricks.com/the-great-divide/)，其中一方是专注于 JavaScript 的程序员，为前端运行时编写 JavaScript。他们一般有计算机科学技能与软件开发经验，很可能将 HTML 和 CSS 视为一种抽象概念（即 [JSX](https://reactjs.org/docs/introducing-jsx.html) 与 [CSS in JS](https://hackernoon.com/all-you-need-to-know-about-css-in-js-984a72d48ebc)）。另一方很可能是非计算机科学出身的开发人员，他们专注于 HTML、CSS 与专属于 UI 的 JavaScript，2019 年，当你试图了解/踏入前端领域时，你一定会感受到这种分歧。不用额外词汇标明正在讨论的是哪种前端开发者的话，“前端开发者” 这个词汇就处于无意义的边缘。

下面是一张列表，记述了各种前端职位（记住职位比较难），最常用的是“前端开发者”或“前端开发工程师”。注意，任何包含“前端“、“客户端”、“Web UI”、“HTML”、“CSS” 或 “JavaScript”等关键词的岗位一般都代表着这个人具备 HTML、CSS、DOM 与 JavaScript 专业知识。

**前端开发者**：通用职位名称，代表在一定程度上精通 HTML、CSS、DOM 和JavaScript 并在 web 平台上实施这些技术的开发人员。

**前端开发工程师 \(亦称为 JavaScript 开发者或全栈 JavaScript 开发者\)：**该职位名称通常被赋予那些背景为计算机科学/软件工程，并将这些技能运用在前端技术的开发者，这一角色通常需要计算机科学知识与多年的软件开发经验。当职位名称中包括“JavaScript 应用程序”一词时，通常代表开发人员必须是具有高级编程、软件开发和应用程序开发技能的高级 JavaScript 开发人员（即拥有多年构建前端软件应用程序的经验）。

**CSS/HTML 开发者：**该前端职位代表一个精通 HTML 和 CSS（不包括 JavaScript 和 App）的开发人员。

**前端 Web 设计师：**当职位名称中包括“设计师”一词时，便表示该设计师具备前端技能\(即 HTML & CSS）与专业设计（视觉设计和交互设计）技能。

**UI \(用户界面\) 开发者/工程师：**当职位名称中包含“界面”或“UI”时，通常代表开发人员除了具备前端开发人员技能或前端工程技能外，还具备交互设计技能。

**（移动端/平板电脑）前端开发者：**当职位名称中包含“**移动端**”或“**平板电脑**”时，通常代表开发人员具有在移动端或平板设备上开发的相关经验（原生环境或 Web 平台上\)。

**前端 SEO 专家：**当职位名称中包含“SEO”一词时，通常代表开发人员在运用前端技术制定 SEO 策略这一方面具有丰富的经验。

**前端可用性专家：**当职位名称中包含“可用性”一词时，通常代表开发人员在制定支持可访问性规定和标准的前端技术方面拥有丰富的经验。

**前端 Dev. Ops：**当职位名称中包含“DevOps”一词时，通常代表开发人员在关于协作，集成，部署，自动化和质量相关的软件开发实践方面具有丰富的经验。

**前端测试/QA：**当职位中包含“测试”或“QA”时，通常代表开发人员具有大量测试与管理软件的经验，包括单元测试、功能测试、用户测试和A/B测试。

> 注**:**
>
> 1. 如果你在职位名称中见到“全栈”或“Web 开发者”这类通用术语，雇主可能在运用这些词来描述负责 Web /应用程序开发的所有方面的角色，即同时包括前端和后端（可能包括设计）。

## 2.3 - 前端开发者所使用的基础 Web 技术 

![](.gitbook/assets/web-tech-employed.jpg)

前端开发者使用以下核心Web技术（建议以此顺序进行学习）：

1. 超文本标记语言（HTML）
2. 层叠样式表 （CSS）
3. 统一资源定位符（URLs）
4. 超文本传输协议（HTTP）
5. JavaScript 编程语言（ECMAScript 262）
6. JavaScript 对象表示法 （JSON）
7. 文档对象模型（DOM）
8. Web API（HTML5 与浏览器 API）
9. Web内容无障碍指南（WCAG）& Accessible Rich Internet Applications \(ARIA\)

有关 Web 相关规范的完整列表，请查阅 [platform.html5.org](https://platform.html5.org/) 或 [MDN Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)。

以下是刚刚提到的九种技术的详细定义，定义下方均附有相关文档和规范的链接。

#### 超文本标记语言（HTML） <a id="hyper-text-markup-language-aka-html"></a>

> **超文本标记语言**（英语：**H**yper**T**ext **M**arkup **L**anguage，简称：**HTML**）是一种用于创建[网页](https://zh.wikipedia.org/wiki/%E7%BD%91%E9%A1%B5)的标准[标记语言](https://zh.wikipedia.org/wiki/%E6%A0%87%E8%AE%B0%E8%AF%AD%E8%A8%80)。HTML是一种基础技术，常与[CSS](https://zh.wikipedia.org/wiki/CSS)、[JavaScript](https://zh.wikipedia.org/wiki/JavaScript)一起被众多网站用于设计网页、网页应用程序以及移动应用程序的用户界面[\[3\]](https://zh.wikipedia.org/wiki/HTML#cite_note-3)。[网页浏览器](https://zh.wikipedia.org/wiki/%E7%BD%91%E9%A1%B5%E6%B5%8F%E8%A7%88%E5%99%A8)可以读取HTML文件，并将其渲染成可视化网页。HTML描述了一个网站的结构语义随着线索的呈现，使之成为一种标记语言而非[编程语言](https://zh.wikipedia.org/wiki/%E7%BC%96%E7%A8%8B%E8%AF%AD%E8%A8%80)。
>
> —[Wikipedia](https://en.wikipedia.org/wiki/HTML)

相关规范/文档：

* [所有 W3C HTML 标准](http://www.w3.org/standards/techs/html#w3c_all)
* [现有标准下的 HTML 元素](https://html.spec.whatwg.org/multipage) 
* [全局属性](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
* [W3C 标准下的 HTML 5.2](https://www.w3.org/TR/2017/REC-html52-20171214/)
* [W3C 标准下的 HTML 5.3](http://w3c.github.io/html/)
* [HTML 属性参考手册](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
* [HTML 元素参考手册](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [现有标准下的 HTML 语法](https://html.spec.whatwg.org/multipage/syntax.html#syntax)

#### 层叠样式表（CSS） <a id="cascading-style-sheets-aka-css"></a>

> 层叠样式表（CSS）是一种样式表语言，用于描述用标记语言编写的文档的外观和格式。虽然它经常被用来更改用 HTML 和 XHTML 编写的网页和用户界面的样式，该语言还是能应用于任何类型的 XML 文档，包括纯 XML、SVG 和 XUL。与 HTML 和 JavaScript 一样，CSS 也是大多数网站用来创建具有视觉吸引力的网页、web应用交互界面以及许多移动端用户界面的基础技术。
>
> —[Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

相关规范/文档：

* [所有 W3C CSS 规范](http://www.w3.org/Style/CSS/current-work)
* [层叠样式表第 2 版第 2 次修订（CSS 2.2）规范](https://www.w3.org/TR/CSS22/)
* [CSS 参考手册](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
* [第三版选择器](http://www.w3.org/TR/css3-selectors/)

#### 超文本传输协议（HTTP） <a id="hypertext-transfer-protocol-aka-http"></a>

> **超文本传输协议**（英语：**H**yper**T**ext **T**ransfer **P**rotocol，缩写：**HTTP**）是一种用于分布式、协作式和[超媒体](https://zh.wikipedia.org/wiki/%E8%B6%85%E5%AA%92%E9%AB%94)信息系统的[应用层](https://zh.wikipedia.org/wiki/%E5%BA%94%E7%94%A8%E5%B1%82)[协议](https://zh.wikipedia.org/wiki/%E7%BD%91%E7%BB%9C%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)[\[1\]](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE#cite_note-ietf2616-1)。HTTP是[万维网](https://zh.wikipedia.org/wiki/%E5%85%A8%E7%90%83%E8%B3%87%E8%A8%8A%E7%B6%B2)的数据通信的基础。
>
> —[Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

相关规范：

* [超文本传输协议 -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)
* [HTTP/2](http://httpwg.org/specs/rfc7540.html)

#### 统一资源定位符（URL） <a id="uniform-resource-locators-aka-url"></a>

> 统一资源定位符（URL）（也称为web地址）是对资源的引用，它指定了计算机网络上资源的位置与获取资源的机制。URL 是一种特定类型的统一资源标识符\(uniform resource identifier, URI\)，许多人经常混用这两个术语。URL 必然包含着访问指定资源的方法，但这并不适用于每个 URI。URL 通常用于引用网页（http），但也用于文件传输（ftp）、电子邮件（mailto）、数据库访问（JDBC）等应用程序。
>
> —[Wikipedia](https://en.wikipedia.org/wiki/Uniform_Resource_Locator)

相关规范：

* [统一资源定位符 \(URL\)](http://www.w3.org/Addressing/URL/url-spec.txt)
* [URL 当前标准](https://url.spec.whatwg.org/)

#### 文档对象模型（DOM） <a id="document-object-model-aka-dom"></a>

> 文档对象模型（DOM）是一种跨平台的、独立于语言的约定，用于表示与操作 HTML、XHTML 和 XML 文档中的对象。每个文档的节点都按树状结构进行组织，称为 DOM 树。可以使用对象上的方法对 DOM 树中的对象进行寻址和操作，DOM 的公共接口在其应用程序编程接口（API）中被指定。
>
> —[Wikipedia](https://en.wikipedia.org/wiki/Document_Object_Model)

相关规范/文档：

* [DOM 当前标准](https://dom.spec.whatwg.org/)
* [W3C DOM4](https://www.w3.org/TR/domcore/)
* [UI 事件](https://www.w3.org/TR/uievents/)

#### JavaScript 编程语言（ECMAScript 262） <a id="javascript-programming-language-aka-ecmascript-262"></a>

> JavaScript 是一种高级、动态、无类型的解释型编程语言，已经经由 ECMAScript 语言规范实现了标准化。是除了 HTML 和 CSS 外万维网内容生产的三大基本技术之一；主流网站都使用它，且所有现代 Web 浏览器都对其提供了原生支持。JavaScript 是基于原型，以函数为第一公民的语言，这使得它有多种编程范式，支持面向对象、命令式与函数式编程风格。它有一个用于处理文本、数组、日期和正则表达式的 API，但不包括任何 I/O，如网络，存储以及图像处理功能，这些都依赖于它所嵌入的环境。

> —[Wikipedia](https://en.wikipedia.org/wiki/JavaScript)

相关规范/文档：

* [ECMAScript® 2018 语言规范](http://ecma-international.org/ecma-262/9.0/index.html#Title)
* [所有 ECMAScript 语言规范](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Language_Resources)

#### Web APIs \(HTML5\)  <a id="web-apis-aka-html5-and-friends"></a>

> 在使用 JavaScript 编写 Web 代码时，有许多 API 可供调用。以下是所有接口（即对象类型）的列表，你可以在开发网站或 Web 应用程序时使用它们。
>
> —[Mozilla](https://developer.mozilla.org/en-US/docs/Web/API)

相关文档：

* [Web API 接口](https://developer.mozilla.org/en-US/docs/Web/API)

#### JavaScript 对象表示法（JSON） <a id="javascript-object-notation-aka-json"></a>

> 这是浏览器与服务器异步通信（AJAJ）时基本的数据格式，在很大程度上取代了 XML （由AJAX使用）。虽然 JSON 最初起源于 JavaScript 脚本语言，但它是一种独立于语言的数据格式。用于解构和生成 JSON 数据的代码在很多语言中都已经有对应的实现。JSON格式最初由 Douglas Crockford 提出，它目前有两个相互竞争中的标准描述，分别是 RFC 7159 和 ECMA-404。ECMA 标准使用者较少，仅描述了允许的语法规则，而 RFC 还提供了一些语义和安全方面的考量。官方的 JSON 互联网媒体文件类型是 application/json。JSON 的后缀名为 .json。
>
> —[Wikipedia](https://en.wikipedia.org/wiki/JSON)

相关规范：

* [JSON 入门介绍](http://json.org/)
* [JSON API](http://jsonapi.org/)
* [JSON 数据交换格式](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)

####  Web 内容无障碍指南（WCAG） & Accessible Rich Internet Applications \(aka ARIA\)  <a id="web-content-accessibility-guidelines-aka-wcag--accessible-rich-internet-applications-aka-aria"></a>

> 可访问性是指产品、设备、服务或环境针对残障人士的设计。可访问性设计的理念同时保证了『直接访问』（即无需帮助）和『间接访问』，代表与个人辅助技术的兼容性（如计算机屏幕阅读助手）。
>
> —[Wikipedia](https://en.wikipedia.org/wiki/Accessibility)

* [网络可访问性倡议（WAI）](https://www.w3.org/WAI/standards-guidelines/)
* [ Web 内容无障碍指南 \(WCAG\) 当前状态 ](http://www.w3.org/standards/techs/wcag#w3c_all)

## 前端开发者所需额外技能

![&#x56FE;&#x7247;&#x6765;&#x6E90;: http://blog.naustud.io/2015/06/baseline-for-modern-front-end-developers.html](.gitbook/assets/front-end-skills.png)

深入了解 HTML、CSS、DOM、JavaScript、HTTP/URL 与浏览器对所有前端开发者都是必要的。

除开我们刚刚提到过的技能，一名前端开发者可能还需要掌握以下一种/多种技能：

* 内容管理系统（CMS）
* Node.js
* 跨浏览器测试
* 跨平台测试
* 单元测试
* 跨设备测试
* 可访问性 / WAI-ARIA
* 搜索引擎优化（SEO）
* 用户界面/交互设计
* 用户体验设计
* 可用性
* 电子商务系统
* 门户系统
* 线框图
* CSS 布局 / 网格
* DOM 操作（如 jQuery）
* 移动端网络性能
* 负载测试
* 性能测试
* 渐进增强 / 优雅降级
* \(e.g., GIT\)版本控制（如 GIT）
* MVC / MVVM / MV\*
* 函数式编程
* 数据格式（如 JSON、XML）
* 数据 API（如 Restful API）
* Web 字体嵌入
* 可缩放矢量图形（SVG）
* 正则表达式
* 微数据/微格式
* 任务运行器，构建工具，自动化工具
* 响应式网页设计
* 面向对象编程
* 应用程序架构
* 模块
* 依赖管理
* 包管理
* JavaScript 动画
* CSS 动画
* 图表 / 图形
* UI 元件
* 代码质量测试
* 代码覆盖率测试
* 代码复杂性分析
* 集成测试
* 命令行 / CLI
* 模版策略
* 模版引擎
* 单页应用程序
* 网络/浏览器安全
* 浏览器开发工具

## 2.5 前端开发者面向什么平台开发？

一个前端开发者所编写的 HTML、CSS 与 JS 通常会运行在由以下操作系统（OS）之一所搭载的 [Web 平台](http://tess.oconnor.cx/2009/05/what-the-web-platform-is)（如：浏览器）上：

* [Android](https://www.android.com/)
* [Chromium](https://www.chromium.org/chromium-os)
* [iOS](https://developer.apple.com/ios/)
* [OS X \(即 MacOS\)](https://www.apple.com/macos)
* [Ubuntu \(或其他 Linux 发行版\)](https://www.ubuntu.com/)
* [Windows](https://www.microsoft.com/en-us/windows)

这些系统通常运行在下列的一个/多个设备上：

* 台式电脑
* 笔记本电脑 / 上网本
* 手机
* 平板电脑
* 电视
* 手表
* [其他设备](https://en.wikipedia.org/wiki/Internet_of_things)（任何你能想得到的东西，汽车，冰箱，灯泡，恒温器等等）

![&#x56FE;&#x7247;&#x6765;&#x6E90;&#xFF1A;https://www.enterpriseirregulars.com/104084/roundup-internet-things-forecasts-market-estimates-2015/](.gitbook/assets/growth-iot.jpg)

一般来说，前端技术可以用在前面提到的操作系统和设备的以下 Web 运行时平台上（存疑）：

* Web 浏览器 \(例如: [Chrome, IE, Safari, Firefox](http://outdatedbrowser.com/en)\).
* [无头浏览器](https://en.wikipedia.org/wiki/Headless_browser) \(例如: [Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)\).
* 被嵌入在原生应用程序中作为运行时的 [WebView](http://developer.telerik.com/featured/what-is-a-webview/) /浏览器选项卡（就像 [iframe](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe)），能够桥接到到原生 API，WebView 应用程序通常包含运用 Web 技术（即 HTML，CSS和JS）构建的 UI（例如: [Apache Cordova](https://cordova.apache.org/), [NW.js](http://nwjs.io/), [Electron](http://electron.atom.io/)）。
* 运用 Web 技术构建的原生应用程序，在运行时通过与原生 API 之间的桥梁进行转译。UI 将使用原生 UI 部件（例如 iOS 原生控件\)，而不是 Web 技术（例如: [NativeScript](https://www.nativescript.org/), [React Native](https://facebook.github.io/react-native/)）。

## 2.6 团队中的前端

前端开发人员通常只是设计和开发网站、Web 应用或基于 Web 技术的原生应用程序团队中的一员。

为 Web 平台构建**专业**网站或软件的小型开发团队通常至少包含以下角色：

* 视觉设计师（负责产品的字体、颜色、间距、情感、视觉概念或主题）
* UI/交互设计师/信息架构师（负责线框图、细化所有用户交互和 UI 功能、组织信息）
* 前端开发者（负责编写在客户端/设备上运行的代码）
* 后端开发者（负责编写在服务器上运行的代码）

角色排序是根据重叠技能来排列的，前端开发人员通常可以很好地处理 UI /交互设计以及后端开发。团队成员通过承担重叠角色的职责来填补角色的空缺情况并不少见。

上述团队通常被假定为由项目负责人或某种产品所有者（即利益相关者，项目经理，项目负责人等）主导。

更大规模的 Web 团队可能包括以下之前未列出的角色：

* SEO 策略专家
* DevOps 工程师
* 性能工程师
* API 开发者
* 数据库管理员
* QA 工程师 / 测试

## 2.7 多面手/全栈神话

![](.gitbook/assets/full-stack.jpg)

"全栈"开发者这个词的含义越来越多，以至于当我们使用此术语时，没有一个含义是明确的。先看看下面两份调查报告，这些报告可能会让人以为大多数开发者都是全栈开发者，但以我近 20 年的经验来看，这不太可能是开发领域的现状。

![&#x56FE;&#x7247;&#x6765;&#x6E90;&#xFF1A;https://medium.freecodecamp.com/we-asked-15-000-people-who-they-are-and-how-theyre-learning-to-code-4104e29b2781\#.ngcpn8nlz](.gitbook/assets/fullstack1.png)

![&#x56FE;&#x7247;&#x6765;&#x6E90;&#xFF1A;https://insights.stackoverflow.com/survey/2017\#developer-profile-specific-developer-types](.gitbook/assets/fullstack2.png)

设计和开发网站或 Web 应用的角色需要在视觉设计、UI/交互设计、[前端开发](https://github.com/kamranahmedse/developer-roadmap#-front-end-roadmap)和[后端开发](https://github.com/kamranahmedse/developer-roadmap#-back-end-roadmap)领域具备精湛的技能与丰富的经验，任何能够以高水准胜任这四个角色中的一个或多个的人都是极为罕见的。

实际上，你应该以成为或招募上述角色中专精于单一领域的人才（即视觉设计，交互设计/ IA，前端开发，后端开发）为目标，能够在单个/多个领域中达到专家级水平的人非常罕见。

然而，考虑到 JavaScript 已经渗透到所有层级的技术栈（即 Node.js），找到一个能够编写前端和后端代码的全栈 JS 开发人员就不那么不切实际了。一般来说，这些全栈开发人员只和 JavaScript 打交道。同时编写前端、后端、API 和数据库代码不再像以前那样遥不可及（不包括视觉设计、交互设计和 CSS）。在我看来这些人依旧像都市传说一样，但不像以前那么罕见。因此，我不建议开发人员将成为“全栈”开发人员作为目标。极少数情况下，它是可行的。但是，本文是规划前端开发人员职业生涯的通识，因此我会专注于前端技术。

## 2.8 前端面试

**准备阶段:**

* [2017 年，如何准备前端开发面试](http://davidshariff.com/blog/preparing-for-a-front-end-web-development-interview-in-2017/)
* [破解前端面试](https://medium.freecodecamp.com/cracking-the-front-end-interview-9a34cd46237)
* [前端面试手册](https://github.com/yangshun/front-end-interview-handbook)
* [揭秘前端面试流程](https://dev.to/emmawedekind/decoding-the-front-end-interview-process-14dl)

**问答题:**

* [前端 Web 开发问答](http://davidshariff.com/quiz/)
* [JavaScript Web 问答](http://davidshariff.com/js-quiz/)

**你可能被问到的问题:**

* [10 个所有 JavaScript 开发者应该知道的面试问题](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
* [前端岗位面试问题](http://h5bp.github.io/Front-end-Developer-Interview-Questions/)
* [前端 Web 开发问答](http://davidshariff.com/quiz/)
* [前端开发面试题](http://thatjsdude.com/interview/index.html)
* [最好的前端 JavaScript 面试问题（由一名前端开发工程师编写）](https://performancejs.com/post/hde6d32/The-Best-Frontend-JavaScript-Interview-Questions-%28Written-by-a-Frontend-Engineer)

**你会提的问题:**

* [开源列表 -- 开发者会向未来雇主提出的问题](https://github.com/ChiperSoft/InterviewThis)

## 2.9 前端招聘板

技术岗招聘渠道非常多，以下精简过的列表是目前寻找特定前端职位/职业最相关的资源。

* [authenticjobs.com](https://authenticjobs.com/#category=4)
* [careers.stackoverflow.com](http://careers.stackoverflow.com/jobs?searchTerm=front-end)
* [css-tricks.com/jobs](https://css-tricks.com/jobs/)
* [frontenddeveloperjob.com](http://frontenddeveloperjob.com/)
* [glassdoor.com](http://www.glassdoor.com/Job/front-end-developer-jobs-SRCH_KO0,19.htm?jobType=all)
* [jobs.github.com](https://jobs.github.com/)
* [linkedin.com](https://www.linkedin.com/jobs/search/?keywords=frontend%20developer)
* [remote.co](https://remote.co/remote-jobs/developer/)
* [weworkremotely.com](https://weworkremotely.com/)
* [www.smashingmagazine.com/jobs/](https://www.smashingmagazine.com/jobs/)

> **注:**
>
> 1. 如果你希望成为远程前端开发，可以看看这些[支持远程工作的公司](https://github.com/jessicard/remote-jobs)。

## 2.10 前端薪资待遇

在美国，中级前端开发的平均薪资水平在 [$65k](https://www.payscale.com/research/US/Job=Front_End_Developer_%2f_Engineer/Salary) 到 [100k](https://www.indeed.com/salaries/Front-End-Developer-Salaries) 之间。

当然，如果你期望进入该领域时拿到 40k 左右的薪资，这取决于地理位置和工作经验。

> **注:**
>
> 1. Leader / 高级前端开发者 / 工程师拥有超过 $150k 的年薪，而且能生活在他们希望居住的地方（即远程工作）（访问 [angel.co](https://angel.co/jobs)，在 [Stack Overflow Jobs](https://stackoverflow.com/jobs?q=front-end&sort=y) 注册并查看年薪超过 $150k 的前端工作或自行约定薪资范围）。

