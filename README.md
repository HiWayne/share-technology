# 前端技术分享（含原创）

`🖌 一个明智地追求快乐的人，除了培养生活赖以支撑的主要兴趣之外，总得设法培养其他许多闲情逸致。—— 罗素`

<br />

> 原创导航：[文章 10](#10-原创从一次前端公共库的搭建中深入谈谈-tree-shaking-的相关问题)、[文章 14](#14-原创gif-和滤镜会碰撞出怎样的火花写了一个可以混合-gif-和滤镜的库)

## 1. 来看看 CSS Functions 好不好恰 🍽

- ### 文章链接
  > https://juejin.cn/post/6990289477201559565#heading-20
- ### 类别
  > `css`
- ### 简介

  > 介绍了 css 中的函数，从基础的 url()、calc()、not()到 var()、cubic-bezier()、perspective()

  > 不管你是 css 新手还是老鸟，总会收获一些你不知道的 css 知识

- ### 推荐指数：⭐️⭐️⭐️⭐️
- ### 收获 & 感悟（可选）
  > 开发者很容易对 css 停留在现有的认识，满足于能够完成任务需要的样式，又或者依赖 css 预处理器，觉得它们就是全部。殊不知 css 早已出现了许多新特性，比如可以声明变量、像编程一样计算、做出复杂的动画和 3D 变换等等。这篇文章只是领你入门，让你明白 css 还有更大的世界。

<br />

## 2. 浏览器原理系列-浏览器渲染流程详解

- ### 文章链接
  > https://juejin.cn/post/6906470997898362894
- ### 类别
  > `浏览器`
- ### 推荐指数：⭐️⭐️⭐️⭐️

<br />

## 3. 浏览器原理系列-JS 执行上下文详解

- ### 文章链接
  > https://juejin.cn/post/6908314735708635150
- ### 类别
  > `V8引擎`
- ### 推荐指数：⭐️⭐️⭐️⭐️

<br />

## 4. 浏览器原理系列-JS 内存机制和垃圾回收

- ### 文章链接
  > https://juejin.cn/post/6908981982017880071
- ### 类别
  > `V8引擎`
- ### 推荐指数：⭐️⭐️⭐️⭐️

<br />

## 5. 浏览器原理系列-V8 引擎对象存储的优化

- ### 文章链接
  > https://juejin.cn/post/6910086185683533838
- ### 类别
  > `V8引擎`
- ### 推荐指数：⭐️⭐️⭐️

<br />

## 6. 浏览器原理系列-V8 编译流水线

- ### 文章链接
  > https://juejin.cn/post/6911613368205836302
- ### 类别
  > `V8引擎`
- ### 推荐指数：⭐️⭐️⭐️

<br />

## 7. React 的秘密

- ### 文章链接
  > https://github.com/neroneroffy/react-source-code-debug
- ### 类别
  > `React原理`
- ### 推荐指数：⭐️⭐️⭐️⭐️
- ### 收获 & 感悟（可选）
  > 子文章很多，初次看可能懵懵懂懂，但随着对 react 的细节了解增加，多次阅读会有更多收获。但不要寄期望于读完这些就等于明白了 react 源码，**绝知此事要躬行**，这些文章虽然比较详细，但也有一些细节没有给出解释的情况。

<br />

## 8. Unicode 与 JavaScript 详解

- ### 文章链接
  > https://www.ruanyifeng.com/blog/2014/12/unicode.html
- ### 类别
  > `Unicode`、`JavaScript`
- ### 推荐指数：⭐️⭐️⭐️
- ### 收获 & 感悟（可选）
  > 平时开发时可能很少关心，但可以从底层了解 unicode 和 js 的关系，将来遇到字符串相关的问题可以打开思路

<br />

## 9. Web 移动端适配方案

- ### 文章链接
  > [深入浅出移动端适配（总结版）](https://juejin.cn/post/6844903951012200456#heading-1)

> [Web 移动端适配方案](https://juejin.cn/post/6894044091836563469#heading-18)

- ### 类别
  > `移动端像素适配`
- ### 推荐指数：⭐️⭐️⭐️⭐️⭐️
- ### 收获 & 感悟（可选）
  > 关于移动端尺寸适配，对多种方案的原理、利弊、向下兼容等等讲的比较详细，实际中经常遇到，比较实用。

<br />

## 10. 【原创】从一次前端公共库的搭建中，深入谈谈 tree shaking 的相关问题

- ### 文章链接

  > 知乎：https://zhuanlan.zhihu.com/p/438065895

  > 掘金：https://juejin.cn/post/7034739926016983071

  > segmentfault：https://segmentfault.com/a/1190000041022779

- ### 类别
  > `前端工程化`、`tree shaking`、`rollup`

<br />

## 11. SWR：最具潜力的 React Hooks 数据请求库

- ### 文章链接
  > [SWR：最具潜力的 React Hooks 数据请求库（主要是一些功能介绍）](https://zhuanlan.zhihu.com/p/89570321)

> [SWR 与前端数据依赖请求（作者：SWR 创作团队-ZEIT 团队成员）](https://zhuanlan.zhihu.com/p/90660704)

- ### 类别
  > `react`、`hooks`、`fetch`
- ### 推荐指数：⭐️⭐️⭐️
- ### 收获 & 感悟（可选）
  > 它的特性可以看文档或者第一篇文章。主要讲一下初步使用后个人的感觉：基于状态驱动的请求在调度方面粒度太大，如果想在某些状态下不调度就需要额外在 fetcher 中写一些逻辑。在对数据新鲜度要求高和可能存在重复请求的场景还是挺舒适的。能不能流行有待市场检验。

<br />

## 12. 精读《模态框的最佳实践》

- ### 文章链接

  > [精读《模态框的最佳实践》](https://github.com/ascoders/weekly/blob/master/%E5%89%8D%E6%B2%BF%E6%8A%80%E6%9C%AF/2.%E7%B2%BE%E8%AF%BB%E3%80%8A%E6%A8%A1%E6%80%81%E6%A1%86%E7%9A%84%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5%E3%80%8B.md)

- ### 类别
  > `ux`、`产品`、`react`、`modal`
- ### 推荐指数：⭐️⭐️⭐️⭐️
- ### 收获 & 感悟（可选）
  > 开发者也需要关心产品体验、长尾需求。以及新手开发中容易忽视的有关 modal 的性能、代码合理性问题，公司实习生就曾出现过文中的反面代码。

<br />

## 13. 国外大神超详细解读：苹果 M1 为什么比英特尔 x86 快了那么多

- ### 文章链接

  > [苹果 M1 为什么比英特尔 x86 快了那么多](http://finance.sina.com.cn/tech/csj/2020-12-02/doc-iiznctke4367373.shtml) > [英文原文](https://debugger.medium.com/why-is-apples-m1-chip-so-fast-3262b158cba2)

- ### 类别
  > `cpu`、`硬件架构`
- ### 简介
  > 不局限于说明 SoC、统一内存、乱序执行的优势，更是分析了为什么 intel、AMD 难以做到。它不是面向大众的科普文，文中简单涉及到了计算机硬件、内存、cpu 指令、micro-ops、商业模式等知识
- ### 推荐指数：⭐️⭐️
- ### 收获 & 感悟（可选）
  > 对 cpu 等硬件感兴趣的可以看看，比较浅显，计算机硬件不太懂的人也适合看。

<br />

## 14. 【原创】gif 和滤镜会碰撞出怎样的火花？写了一个可以混合 gif 和滤镜的库

- ### 文章链接

  > 知乎： https://zhuanlan.zhihu.com/p/459502707

  > 掘金：https://juejin.cn/post/7054844668088942623

  > segmentfault：https://segmentfault.com/a/1190000041310365

  > github: https://github.com/HiWayne/colorful_gif

- ### 类别
  > `js`、`gif`、`滤镜`、`npm-package`
- ### 简介
  > 这是一个可以把滤镜图片混合进 gif 的库，它会返回一个新的 gif dataURL。你可以通过它生成很多好看或有意义的 gif。比如在 Demo 中我就让一个撑伞走路的人，变成了在云中漫步。你也可以实现自己的灵感。比如如果滤镜中的 icon 位置合适的话，就可以做到给 gif 打水印等等……
- ### 推荐指数：喜欢的话去 github 和文章里给个赞吧！
- ### 收获 & 感悟（可选）
  > 在搭建公司某个 monorepo npm 项目的过程中收获了一些工程化知识，所以多入口 build、deploy 和 npm publish 这个库的过程很快，几乎没遇到什么坑，算是一种进步吧。

<br />

## 15. 15. 你会怎么做前端优化？

- ### 文章链接

  [https://juejin.cn/post/7028028584463695879](https://juejin.cn/post/7028028584463695879)

- ### 类别
  > `前端优化`、`web前端知识体系小汇总`
- ### 简介
  > 从几乎所有角度体系化的介绍了前端优化策略。涵盖前端监控、多端渲染、浏览器渲染策略、计算机网络、前端构建、资源优化、编程粒度的优化（web worker、service worker、IntersectionObserver、web font 等）
- ### 推荐指数：⭐️⭐️⭐️⭐️⭐️
- ### 收获 & 感悟（可选）
  > 整篇文章较长，且有体系，精读其中的每一个知识点可能会花费不少时间。有些知识需要你提前对它有前置了解，比如浏览器渲染流水线部分，更具体的讲解可以看之前的[分享 2](#2-浏览器原理系列-浏览器渲染流程详解)。同时有些概念必须建立在实践的基础上。比如如果你没有在生产中接触过 SSR，那么对 hydration 等概念就不太清楚。如果你精读下来并去深入了解、动手实践，除了提高优化方面的认知，对建立前端知识体系也有很大作用。
