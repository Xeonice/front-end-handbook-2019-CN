# 0.1 2018 前端发展回顾

* 去年，React 发布了有一些值得注意的新特性，如 [lifecycle methods](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#component-lifecycle-changes), [context API](https://reactjs.org/blog/2018/03/29/react-v-16-3.html#official-context-api), [suspense](https://reactjs.org/docs/react-api.html#reactsuspense), 与 [React hooks](https://reactjs.org/docs/hooks-intro.html).

* [Microsoft 收购了 Github](https://news.microsoft.com/2018/06/04/microsoft-to-acquire-github-for-7-5-billion/)，嗯，这确实是挺不可思议的。
* 运用 CSS 设计字体[成为了现实](https://yusugomori.com/projects/css-sans/).
* 我以前称之为前端驱动的应用程序被打上了 ["serverless"](https://thepowerofserverless.info/) 的标签. 不幸的是, 这个词被[滥用](https://www.jeremydaly.com/stop-calling-everything-serverless/)了。然而， [JAMstack](https://jamstack.org/) 这个词似乎引起了开发者们的[共鸣](https://jamstackconf.com/nyc/)。

* Google offered some neat tools this year to help make webpages load faster, i.e.[squoosh](https://github.com/GoogleChromeLabs/squoosh/) and [quicklink](https://github.com/GoogleChromeLabs/quicklink).
* [Vue gets](https://risingstars.js.org/2018/en/#section-framework) more [Github stars](https://hasvuepassedreactyet.surge.sh/) than React this year. But React remains dominant in [terms](https://2018.stateofjs.com/front-end-frameworks/overview/) of [use](https://www.npmjs.com/browse/depended).
* A solution similar to React, without a virtual DOM or JSX, is introduced [RE:DOM](https://github.com/redom/redom).
* Alternatives to NW.js and Electron show up, [DeskGap](https://deskgap.com/) and [Neutralino.js](https://neutralino.js.org/).
* In 2017 the [great](https://medium.com/@jerrylowm/the-death-of-front-end-developers-803a95e0f411) divide between a [front-end HTML & CSS developer](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06) v.s. [front-end application developer is realized/verbalized](https://medium.com/@mandy.michael/is-there-any-value-in-people-who-cannot-write-javascript-d0a66b16de06). In 2018 that [divide has grown wider and deeper](https://css-tricks.com/the-great-divide/) and more [people](https://rachelandrew.co.uk/archives/2019/01/30/html-css-and-our-vanishing-industry-entry-points/) start to [feel](https://hackernoon.com/the-backendification-of-frontend-development-62f218a773d4) [the](http://bradfrost.com/blog/post/big-ol-ball-o-javascript/) [divide](https://justmarkup.com/log/2018/11/just-markup/).
* This year, like most recent years, was stock full of app/framework solutions trying to contend with the mainstream JavaScript app tools \(i.e.[React, Angular, and Vue etc...](https://stateofjs.com/2017/front-end/results)\) Let me list them for you. [Radi.js](https://radi.js.org/), [DisplayJS](https://display.js.org/), [Stimulus](https://stimulusjs.org/), [Omi](https://github.com/Tencent/omi), [Quasar](https://quasar-framework.org/).
* JavaScript frameworks start offering their own languages that compile to JavaScript \(e.g.[Mint](https://www.mint-lang.com/)\).
* [CodeSandbox](https://codesandbox.io/) evolves to become the dominant solution for online code sharing.
* [CSS Grid](https://cssgridgarden.com/) and [CSS Flexbox](https://flexboxfroggy.com/) are fully supported in modern browsers and get taken for some serious rides. But many are left
  [wondering](https://www.youtube.com/watch?v=hs3piaN4b5I) when to [use which one and how](https://css-irl.info/to-grid-or-to-flex/).
* Many realize the long terms costs of bolted on type systems \(e.g. TypeScript and Flow\). Some concluded bolted on systems are not unlike bolted on module systems \(i.e. AMD/Require.js\) and come with [more issues than solutions](https://medium.com/javascript-scene/the-typescript-tax-132ff4cb175b). Minimally, many developers realize that if types are needed in large code bases, that bolted on systems are not ideal in comparison to languages that have them baked in \(e.g. [Reason](https://reasonml.github.io/), [Purescript](http://www.purescript.org/), [Elm](https://elm-lang.org/)\).
* [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables) gain [browser support](https://caniuse.com/#feat=css-variables) among modern web browsers
* The flavors of [CSS in JS](http://michelebertoli.github.io/css-in-js/) exploded and [some](http://bradfrost.com/blog/link/whats-wrong-with-css-in-js/) question the practice.
* [ES modules](https://caniuse.com/#search=modules) are now usable in modern browsers and [dynamic imports](https://developers.google.com/web/updates/2017/11/dynamic-import#dynamic) are close behind. We are even seeing a shift in [tooling](https://www.pikapkg.com/blog/introducing-pika-pack/) around this fact.
* Many realize that end to end testing is the starting point of doing tests correctly in large part due to [Cypress](https://www.cypress.io/how-it-works/) \(i.e. Cypres first,  then [Jest](https://jestjs.io/)\).
* While [Webpack](https://webpack.js.org/) was heavily used again this year, many developers found [Parcel](https://github.com/parcel-bundler/parcel) to be easier to get up and running.
* One of the most important questions asked this year was, what is the [cost of JavaScript](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4).
* [Babel 7 was released this year](https://babeljs.io/blog/2018/08/27/7.0.0). That's a big deal because the last major release was almost three years ago.
* The reality of too much JavaScript change too fast is realized and people start [talking](https://www.robinwieruch.de/javascript-fundamentals-react-requirements/) about what you need to know before you can even learn something like React. The fight is real.
* Most developers found GraphQL, via [Apollo](https://www.apollographql.com/), and [see it](https://blog.bitsrc.io/why-does-everyone-love-graphql-17de7f99f05a) as the next evolution for data API's.
* Gulp and friends definitely took a back seat to [NPM/Yarn run](https://css-tricks.com/why-npm-scripts/). But this did not stop Microsoft from getting in the game with [Just](https://github.com/Microsoft/just).
* This year, one can not only lint/hint HTML, CSS, and JavaScript they can [lint/hint the web](https://webhint.io/) itself.
* The [2018 Front-End Tooling survey](https://ashleynolan.co.uk/blog/frontend-tooling-survey-2018-results) is worth reading if only to realize just how much jQuery is still used.
* 不可否认，[TypeScript](https://www.typescriptlang.org/) 今年确实又增加了不少新用户.
* [VScode](https://code.visualstudio.com/) 在代码编辑器中依然保有[统治地位](https://triplebyte.com/blog/editor-report-the-rise-of-visual-studio-code)。



