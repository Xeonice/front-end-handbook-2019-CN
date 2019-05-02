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

[A great divide has been brewing in the front-end developer space for several years between two very different types of so-called front-end developers](https://css-tricks.com/the-great-divide/). On the one side, you have JavaScript-focused programmers who write JavaScript for front-end runtimes that likely have computer science skills with a software development history. They more than likely view HTML and CSS as an abstraction \(i.e.[JSX](https://reactjs.org/docs/introducing-jsx.html)and[CSS in JS](https://hackernoon.com/all-you-need-to-know-about-css-in-js-984a72d48ebc)\). On the other side, you have, most likely, non-computer science educated developers who focus on HTML, CSS, and JavaScript as it specifically pertains to the UI. In 2019, when entering or trying to understand the front-end developer space you will absolutely feel this divide. The term front-end developer is on the verge of meaninglessness without clarifying words to address what type of front-end developer is being discussed.

Below is a list and description of various front-end job titles \(Keep in mind titles are[hard](https://blog.prototypr.io/dissecting-front-end-job-titles-7f72a0ef0bc5)\). The common, or most used \(i.e., generic\), title for a front-end developer is, "front-end developer" or "front-end engineer". Note that any job that contains the word "front-end", "client-side", "web UI", "HTML", "CSS", or "JavaScript" typically infers that a person has some degree of HTML, CSS, DOM, and JavaScript professional know how.

**Front-End Developer**: The generic job title that describes a developer who is skilled to some degree at HTML, CSS, DOM, and JavaScript and implementing these technologies on the web platform.

**Front-End Engineer \(aka JavaScript Developer or Full-stack JavaScript Developer\)**: The job title given to a developer who comes from a computer science, engineering, background and is using these skills to work with front-end technologies. This role typically requires computer science knowledge and years of software development experience. When the word "JavaScript Application" is included in the job title, this will denote that the developer should be an advanced JavaScript developer possessing advanced programming, software development, and application development skills \(i.e has years of experience building front-end software applications\).

**CSS/HTML Developer**: The front-end job title that describes a developer who is skilled at HTML and CSS, excluding JavaScript and application, know how.

**Front-End Web Designer**: When the word "Designer" is included in the job title, this will denote that the designer will possess front-end skills \(i.e., HTML & CSS\) but also professional design \(Visual Design and Interaction Design\) skills.

**UI \(User Interface\) Developer/Engineer**: When the word "Interface" or "UI" is included in the job title, this will denote that the developer should posses interaction design skills in addition to front-end developer skills or front-end engineering skills.

**Mobile/Tablet Front-End Developer**: When the word "Mobile" or "Tablet" is included in the job title, this will denote that the developer has experience developing front-ends that run on mobile or tablet devices \(either natively or on the web platform, i.e., in a browser\).

**Front-End SEO Expert**: When the word "SEO" is included in the job title, this will denote that the developer has extensive experience crafting front-end technologies towards an SEO strategy.

**Front-End Accessibility Expert**: When the word "Accessibility" is included in the job title, this will denote that the developer has extensive experience crafting front-end technologies that support accessibility requirements and standards.

**Front-End Dev. Ops**: When the word "DevOps" is included in the job title, this will denote that the developer has extensive experience with software development practices pertaining to collaboration, integration, deployment, automation, and quality.

**Front-End Testing/QA**: When the word "Testing" or "QA" is included in the job title, this will denote that the developer has extensive experience testing and managing software that involves unit testing, functional testing, user testing, and A/B testing.

> 注**:**
>
> 1. If you come across the "Full Stack" or the generic "Web Developer" terms in job titles these words may be used by an employer to describe a role that is responsible for all aspects of web/app development, i.e., both front-end \(potentially including design\) and back-end.



