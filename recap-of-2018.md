# 第0章-回顾2018并展望未来

## 0.1 2018 前端发展回顾

* 去年，React 发布了有一些值得注意的新特性，如 [lifecycle methods](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#component-lifecycle-changes), [context API](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#official-context-api), [suspense](https://reactjs.org/docs/react-api.html#reactsuspense), 与 [React hooks](https://reactjs.org/docs/hooks-intro.html).
* [Microsoft 收购了 Github](https://news.microsoft.com/2018/06/04/microsoft-to-acquire-github-for-7-5-billion/)，嗯，这确实是挺不可思议的。
* 运用 CSS 设计字体[成为了现实](https://yusugomori.com/projects/css-sans/)。
* 我以前称之为前端驱动的应用程序被打上了 [serverless](https://thepowerofserverless.info/) 的标签. 不幸的是, 这个词被[滥用](https://www.jeremydaly.com/stop-calling-everything-serverless/)了。然而， [JAMstack](https://jamstack.org/) 这个词似乎引起了开发者们的[共鸣](https://jamstackconf.com/nyc/)。
* Google 提供了一些精巧的工具（[squoosh](https://github.com/GoogleChromeLabs/squoosh/) 和 [quicklink](https://github.com/GoogleChromeLabs/quicklink)），用以帮助优化页面加载速度，
* [Vue 今年得到了](https://risingstars.js.org/2018/en/#section-framework)比 React 更多的 [Github stars](https://hasvuepassedreactyet.surge.sh/)，但是 React 在框架界的[统治地位](https://2018.stateofjs.com/front-end-frameworks/overview/)依旧[无人能敌](https://www.npmjs.com/browse/depended)。
* 介绍一下 [RE:DOM](https://github.com/redom/redom)，一个类似于 React 的解决方案, 但是没有引入 virtual DOM 与 JSX。
* NW.js 和 Electron 的替代品 -- [DeskGap](https://deskgap.com/) 和 [Neutralino.js](https://neutralino.js.org/) 出现了。
* 2017 年起，人们开始意识到[前端 HTML & CSS 工程师](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06)与[前端应用开发工程师间存在着](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06)巨大的[分歧](https://medium.com/@jerrylowm/the-death-of-front-end-developers-803a95e0f411)，2018 年时，[分歧开始变得越来越明显](https://css-tricks.com/the-great-divide/)，越来越多的[人](https://rachelandrew.co.uk/archives/2019/01/30/html-css-and-our-vanishing-industry-entry-points/)开始[感受](https://hackernoon.com/the-backendification-of-frontend-development-62f218a773d4)到[这种](http://bradfrost.com/blog/post/big-ol-ball-o-javascript/)[分歧](https://justmarkup.com/log/2018/11/just-markup/)。
* 与最近几年一样，今年依旧充斥着各种应用/框架解决方案，试图与JavaScript主流应用工具抗衡（如.[React, Angular, 和 Vue 等等...](https://stateofjs.com/2017/front-end/results)），比如说 [Radi.js](https://radi.js.org/)、[DisplayJS](https://display.js.org/)、[Stimulus](https://stimulusjs.org/)、[Omi](https://github.com/Tencent/omi) 与 [Quasar](https://quasar-framework.org/)。
* JavaScript 框架开始提供它们自己的语言，并编译成 JavaScript（例如：[Mint](https://www.mint-lang.com/)）。
* [CodeSandbox](https://codesandbox.io/) 逐步成为在线代码共享的主流解决方案。
* [CSS Grid](https://cssgridgarden.com/) 和 [CSS Flexbox](https://flexboxfroggy.com/) 已得到了现代浏览器的完全支持，而且可以用在一些重要场合（存疑），但是大多数人都[不清楚](https://www.youtube.com/watch?v=hs3piaN4b5I)应当使用[使用哪一种方案](https://css-irl.info/to-grid-or-to-flex/)？以及如何使用 。
* Many realize the long terms costs of bolted on type systems \(e.g. TypeScript and Flow\). Some concluded bolted on systems are not unlike bolted on module systems \(i.e. AMD/Require.js\) and come with [more issues than solutions](https://medium.com/javascript-scene/the-typescript-tax-132ff4cb175b). Minimally, many developers realize that if types are needed in large code bases, that bolted on systems are not ideal in comparison to languages that have them baked in \(e.g. [Reason](https://reasonml.github.io/), [Purescript](http://www.purescript.org/), [Elm](https://elm-lang.org/)\).
* [CSS 变量](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)已经在现代浏览器中获得了[相应支持](https://caniuse.com/#feat=css-variables)。
* [CSS in JS](http://michelebertoli.github.io/css-in-js/) 越发流行，一些人[质疑](http://bradfrost.com/blog/link/whats-wrong-with-css-in-js/)这种做法的必要性。
* [ES modules](https://caniuse.com/#search=modules) 现可用于现代浏览器，[dynamic imports](https://developers.google.com/web/updates/2017/11/dynamic-import#dynamic) 会紧随其后，我们甚至可以看到围绕这一事实而发生的[工具转变](https://www.pikapkg.com/blog/introducing-pika-pack/)。
* 越来越多的人意识到端对端测试是进行正确测试的起点，而这很大程度上归功于 [Cypress](https://www.cypress.io/how-it-works/)（Cypres 要先于 [Jest](recap-of-2018.md) 提出这一理念）
* 在 [Webpack](https://webpack.js.org/) 依旧被广泛使用的这个年头，一些开发者发现 [Parcel](https://github.com/parcel-bundler/parcel) 更易于上手。
* 今年提出的一个最重要的问题：[JavaScript 的性能开销有哪些？](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4)
* 今年发布了[Babel 7](https://babeljs.io/blog/2018/08/27/7.0.0)，这是一个大新闻，因为上一次的重大版本更新已经是三年前的事情了。
* 大家开始意识到 JavaScript 的变化过多也过快，现在人们开始讨论在学习像 React 这种框架前需要先掌握哪些知识，这场斗争还远未结束。
* 越来越多的开发者通过 [Apollo](https://www.apollographql.com/) 了解到 GraphQL，并将其[视为](https://blog.bitsrc.io/why-does-everyone-love-graphql-17de7f99f05a) data API 的下一个发展方向。
* Gulp 和它的朋友们已被 [NPM/Yarn](https://css-tricks.com/why-npm-scripts/) 耀眼的光芒所掩盖，但这依旧不能阻止 Microsoft 通过 [Just](https://github.com/Microsoft/just) 加入战局。
* 今年，我们不仅能检查 HTML, CSS, 和 JavaScript 代码，还能[检查 web 本身](https://webhint.io/)。
* 如果只是为了了解 jQuery 现目前的市场占有率的话，[2018前端工具调查](https://ashleynolan.co.uk/blog/frontend-tooling-survey-2018-results)依旧值得一读。
* 不可否认，[TypeScript](https://www.typescriptlang.org/) 今年确实又增加了不少新用户。
* [VScode](https://code.visualstudio.com/) 在代码编辑器中依然保有[统治地位](https://triplebyte.com/blog/editor-report-the-rise-of-visual-studio-code)。

## 0.2 2019年，我们所期待的是……

* 希望今年能有更多人 “[走出Sass](https://cathydutton.co.uk/posts/why-i-stopped-using-sass/)“.
* 通过 [https://cssdb.org](https://cssdb.org/) 来关注 CSS 今后会添加的新特性（潜在特性）依旧是个好主意。
* 希望来自 Google 的 [WebP](https://developers.google.com/speed/webp/) 图片格式在今年能得到[所有现代浏览器的支持](https://caniuse.com/#feat=webp)。
* [Prepack](https://prepack.io/) 能得到进一步的发展。
* [GraphQL](https://graphql.org/) 能获得进一步的推广。
* "[JavaScript 现状调查](https://stateofjs.com/)" 的作者将会在 2019 年发起 "[CSS 现状调查](https://stateofcss.com/)"。
* 密切关注 [Web Animations API](https://caniuse.com/#feat=web-animation)。
* 你认识的人会试图说服你使用 [TypeScript](https://www.typescriptlang.org/)。
* [swc-project](https://github.com/swc-project/swc) 能与 Babel 构成竞争关系。
* [JAMStack](https://jamstack.org/) 的相关案例能被[继续推行下去](https://jamstackconf.com/nyc/)。
* [基于单语言的跨平台尝试会继续进行](https://quasar-framework.org/)。
* 对于大型代码项目，更多开发者会选择 [ReasonML](https://www.imaginarycloud.com/blog/reasonml-react-as-first-intended/) 这种语言，而不是 JavaScript/TypeScript。
* 更多被广泛使用的[大型项目](https://github.com/twbs/bootstrap/pull/23586)能够舍弃 jQuery，转而使用原生 DOM 解决方案。
* [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)！现目前我还不清楚 Web Components 会将会如何发挥作用，事实是它们不会消失，而且它们在炒作结束的时候依然没有获得足够的影响力/运用。 

