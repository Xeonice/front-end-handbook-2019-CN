---
description: 本章将从“如何成为前端开发人员”开始，逐步分解并概要描述前端工程实践。
---

# 第2章-前端开发实践-概述

# 2.1 如何成为前端开发工程师？

初学者如何成为前端开发工程师？嗯，这很复杂，先来看看这张线路图：

时至今日，我们依旧不能通过大学课堂得到一份前端开发工程师的学位，而且我很少听说有前端开发者在拿到计算机科学学位/视觉设计学位后就能立刻编写出专业的 HTML、CSS、JavaScript 代码。据我所见，今天的大部分前端从业者似乎都是自学成才的，或者从计算机科学领域/视觉设计领域转入前端领域的。

![图片来源：https://github.com/kamranahmedse/developer-roadmap](.gitbook/assets/frontend.png)

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

# 2.2 前端开发相关职位

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



