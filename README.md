# 高级前端知识架构
* [异步](https://github.com/liuyongliang/Advanced-Frontend#%E5%BC%82%E6%AD%A5)
    * 异步编程
    * async/await
    * Promise
* 函数式编程
    * 函数式编程
* 服务器端渲染SSR
    * SSR指南
    * SSR框架
* 代码质量
    * 代码规范
    * JavaScript
    * TypeScript
* 性能优化
    * 调试工具
    * H5优化
    * 缓存
    * 压缩
    * 内存
    * 渲染
    * 资源加载
* 监控
    * 异常捕获
    * 页面性能监控
    * 设备信息采集
    * 埋点
    * 用户行为
* 设计模式
    * 单体
    * 工厂
    * 迭代器
    * 装饰者
    * 策略
    * 外观
    * 代理
    * 中介者
    * 观察者
* 工程化
    * 构建工具
    * webpack
    * 脚手架
* 浏览器
    * 自动化
* 网络
    * OSI七层协议
    * DNS解析
* 协议
    * TCP
    * UDP
* 测试
    * 单元测试
    * 自动化测试
* 前端标准/规划
	* 骨架屏 
* 前端算法
    * 递归
* 可视化
    * d3
    * three.js
* NodeJS
* 移动web开发
    * Hybrid
    * Flutter
* 物联网
* 安全
    * 抓包/代理
    * 监控技术
* 机器学习
    * TensorFlow
* 客户端开发
    * electron
    * nw.js
    * chrome插件
* 源码分析
    * vue源码
    * react源码
    * TypeScript
* 项目管理
* 前端发展趋势
* 面试
* 社区/会议


## 异步

### 异步编程

* [《深入理解 JavaScript 异步系列》](https://www.cnblogs.com/wangfupeng1988/p/6513070.html)

    * JS 是单线程的语言。运行的js ，可能会有大量的网络请求，而一个网络资源啥时候返回，这个时间是不可预估的。这种情况会出现等待卡顿。JS 对于这种场景就设计了异步 ———— 即，发起一个网络请求，就先不管这边了，先干其他事儿，网络请求啥时候返回结果，到时候再说。这样就能保证一个网页的流程运行

* [《javascript 异步编程的5种方式》](https://blog.csdn.net/daydream13580130043/article/details/83105098)

### async/await

* [《async/await 详解》](https://blog.csdn.net/qq_24510455/article/details/101292914)

    * promise的出现对于异步编程是一个跨越式的提高，但是往往在实际业务中存在很多更加复杂的流程，promise还是无法满足我们的需要，这时候在ES7中提出了async函数

* [《为什么async/await关键字是如此重要》](http://jimliu.net/2018/09/11/why-we-need-async-await/)

* [《async await 是把双刃剑》](https://github.com/dt-fe/weekly/blob/v2/055.%E7%B2%BE%E8%AF%BB%E3%80%8Aasync%20await%20%E6%98%AF%E6%8A%8A%E5%8F%8C%E5%88%83%E5%89%91%E3%80%8B.md)

### Promise

* [《深入理解 ES6 Promise》](https://segmentfault.com/a/1190000020934044)


## 服务器端渲染SSR

### SSR指南

* [《浅谈服务端渲染(SSR)》](https://www.jianshu.com/p/10b6074d772c)

    * 简单理解是将组件或页面通过服务器生成html字符串，再发送到浏览器，最后将静态标记"混合"为客户端上完全交互的应用程序    

* [《有必要使用服务器端渲染(SSR)吗？》](https://www.zhihu.com/question/308792091?sort=created)

* [《从头开始，彻底理解服务端渲染原理》](https://blog.csdn.net/qq_29438877/article/details/98477160)

* [《精读前后端渲染之争》](https://github.com/dt-fe/weekly/blob/v2/003.%E7%B2%BE%E8%AF%BB%E5%89%8D%E5%90%8E%E7%AB%AF%E6%B8%B2%E6%9F%93%E4%B9%8B%E4%BA%89.md)
 
### SSR框架
* [《Vue.js 服务器端渲染指南》](https://ssr.vuejs.org/zh/)   

* [《基于 Vue 的通用应用框架Nuxt.js》](https://www.nuxtjs.cn/guide)

* [《轻量级的 React 服务端渲染应用框架NEXT.js》](https://www.nextjs.cn/)
    * Next.js 为您提供生产环境所需的所有功能以及最佳的开发体验：包括静态及服务器端融合渲染、 支持 TypeScript、智能化打包、 路由预取等功能 无需任何配置

* [《webpack4+koa2+vue 实现服务器端渲染(详解)》](https://www.cnblogs.com/tugenhua0707/p/11048465.html)

## 函数式编程

### 函数式编程

* [《简明 JavaScript 函数式编程——入门篇》](https://juejin.cn/post/6844903936378273799#heading-31)

* [《函数式编程进阶：杰克船长的黑珍珠号》](https://juejin.cn/post/6844904034260910094)

    * 函数式编程就像第三次工业革命，前两次分别为命令式编程（Imperative programming）和面向对象编程（Object Oriented Programming）

* [《前端开发js函数式编程真实用途体现在哪里？》](https://www.zhihu.com/question/59871249)


## 代码质量

### 代码规范

* [《写出高质量JS代码的12条建议》](https://zhuanlan.zhihu.com/p/92478119)

* [《如何保证前端项目代码质量》](https://zhuanlan.zhihu.com/p/82546272)

    * 代码本身的质量: 包括复杂度, 重复率, 代码风格等。
        * 复杂度: 项目代码量，模块大小，耦合度等
        * 重复率: 重复出现的代码区块占比，通常要求在5%以下(借助平台化工具如Sonar)
        * 代码风格: 代码风格是否统一(动态语言代码如JS, Python风格不受约束)

### JavaScript

* [《JavaScript开发者应懂的33个概念》](https://github.com/stephentian/33-js-concepts)

* [《JavaScript 最佳实践: 提升你代码质量的一些提示&技巧》](https://ioliu.cn/2016/javascript-best-practices-tips-and-tricks-to-level-up-your-code/)

### TypeScript

* [《使用SonarTS创建进行typescript代码质量扫描》](https://blog.csdn.net/liumiaocn/article/details/102670480/)

## 性能优化

### 调试工具

* [《Chrome 开发者工具》](https://developers.google.cn/web/tools/chrome-devtools/)

### H5优化

* [《前端H5性能优化》](https://blog.csdn.net/likeky/article/details/103953017)

### 缓存

* [《前端资源缓存详解》](https://segmentfault.com/a/1190000020786519)

* [《promise实现前端缓存》](https://www.dsiab.com/1586697823556)

### 压缩

* [《前端性能优化：gzip压缩文件传输数据》](https://www.cnblogs.com/zs-note/p/9556390.html)

### 内存

* [《前端的角度讲讲内存》](https://zhuanlan.zhihu.com/p/142354342)

    * 在JS中具有自动垃圾回收机制，对于前端开发来说，内存空间并不是被常常提起的概念，容易被大家忽视。很多东西的原理与内存息息相关，如：闭包、深签拷贝、执行上下文等，要弄清楚这些，必须对内存空间有清晰的认知才行。

* [《前端内存泄露问题》](https://blog.csdn.net/sunycnb/article/details/108908917)

* [《内存空间详细图解》](https://www.jianshu.com/p/996671d4dcc4)

### 渲染

* [《深入浅出浏览器渲染原理》](https://zhuanlan.zhihu.com/p/53913989)

### 资源加载

* [《使用 Preload&Prefetch 优化前端页面的资源加载》](https://mp.weixin.qq.com/s/DaQkyjFh6_LXEO5X7pmuWg)

    * 对于前端页面来说，静态资源的加载对页面性能起着至关重要的作用。本文将介绍浏览器提供的两个资源指令-preload/prefetch，它们能够辅助浏览器优化资源加载的顺序和时机，提升页面性能

## 监控

### 异常捕获

* [《JavaScript错误处理完全指南》](https://mp.weixin.qq.com/s?src=11&timestamp=1612415201&ver=2869&signature=blR9eVa4RXFibU5Qtc1*OFoBVG6AI-IH*nUrjQUztd9fxNqUI17qjq9wDWezDQS*NNUnSIdF5iS9qYMGm8WqUd6*7U9gBRlvgnqtU*AFJ6Dhaza6OM0DI8ey3LPTxJmf&new=1)
	* JavaScript 中的一个错误是一个对象，错误会被抛出以暂停程序

* [《前端JavaScript 常见的报错及异常捕获与处理方法》](https://mp.weixin.qq.com/s?src=11&timestamp=1612410621&ver=2869&signature=zIc0WRGzvVyFm7R64MAdiIZ2HvPMXvrbbXniBqjUQmRmpBmDalx9jFxBy8ReoCAAZMUeeo0cxKMP6OWSsYhVom6gw3FMnmNCKKQNivQooUygkZEOwKKIL*XYAV5QB89U&new=1)

* [《前端中 try-catch 捕获不到哪些异常和错误》](https://mp.weixin.qq.com/s?src=11&timestamp=1612415017&ver=2869&signature=bOofrkhZqbN7UNuEIBbXWTbovT9XFvtfAdFYlL*3ChfKQY*4mHNsR3nzwI7ozoJ9yHwISVPujkV01C*zIyLrEzYzYxJysx-TFakVVNdKpFXojO0UynIgoUqD2TQq-QU8&new=1)

	* 在开发过程中，我们的目标是 0error，0warning。但有很多因素并不是我们可控的，为了避免某块代码的错误，影响到其他模块或者整体代码的运行，我们经常会使用try-catch模块来主动捕获一些异常或者错误

### 页面性能监控

* [《10分钟彻底搞懂前端页面性能监控》](https://zhuanlan.zhihu.com/p/82981365)

* [《Web 前端页面性能监控指标》](https://www.cnblogs.com/xgqfrms/p/13602022.html)

* [《 FrontJS 快你一步捕捉 Bug》](https://www.frontjs.com/)
	* FrontJS 提供准确、实时、完整的程序错误、资源加载、网络请求信息及网站性能监测报告，帮助开发者快速追踪网站故障，及时修复问题，维护网站质量，指导改善用户体验。 

### 埋点

* [《前端埋点统一接入方案实践》](https://mp.weixin.qq.com/s?src=11&timestamp=1612416083&ver=2869&signature=yKLfRDS89eiDh9nULkcStP*hOlk7AOyfQB41LvVqQ494aD5hFuiWdGK9UYGiOG5lCRuqe-Jytei7sR*LV69VYhQJQ5rYiUpS9YRGv-GzbZFGi8CdMeDxmjoEcUAYqj67&new=1)
	* 关于埋点，作为用户行为过程数据采集的一种方式，被广泛用于各公司的站点中。它不仅可以收集页面浏览量，还能对访问用户的时间、地点、操作路径等用户行为进行多维度记录

* [《网易云音乐大前端团队关于前端组件化埋点的实践》](https://mp.weixin.qq.com/s?src=11&timestamp=1612416223&ver=2869&signature=oWTAlFs0MSGjEU9BL28*vm4vOY54m32JcZEtWAGxcDTrIbeyTs1MXcqkSEXgcA1zmlLCrw3YKd4YPpKMETg0g9rNwaJnzQdNCpJJDMlRNXSfR7M33yzy896uO1q15Vt5&new=1)


### 用户行为

## 前端标准/规划

### 骨架屏 

* [《一个简易的预渲染自动骨架屏方案》](https://zhuanlan.zhihu.com/p/166009071)

## 源码分析

### vue源码

* [《vue源码分析》](https://github.com/answershuto/learnVue)

* [《前端路由简介以及 vue-router 实现原理》](https://juejin.cn/post/6844903615283363848)
    * 简单来说路由就是用来跟后端服务器进行交互的一种方式，通过不同的路径，来请求不同的资源，请求不同的页面是路由的其中一种功能。

### react源码

* [《React技术揭秘》](https://react.iamkasong.com/)

* [《理解react生命周期，以及react生命周期的使用场景》](https://blog.csdn.net/qq_32899575/article/details/81699357)

### TypeScript

* [《深入理解 TypeScript》](https://github.com/jkchao/typescript-book-chinese)

## 前端算法

### 递归

* [《前端电商 sku 全排列的递归回溯算法实战》](https://github.com/sl1673495/blogs/issues/50)

## 工程化

### 脚手架

* [《如何写一个标准的前端脚手架》](https://zhuanlan.zhihu.com/p/105846231)

## 前端发展趋势

### 前端发展趋势

* [《2021年前端发展预测》](https://mp.weixin.qq.com/s?__biz=MzUxMzcxMzE5Ng==&mid=2247506245&idx=1&sn=e498d49616ac8d9ae446ad9cb3ca5658&chksm=f9526c06ce25e5104940c19c42e49a54bb8e3d646b645d689ce0a5b7fc0e6e5ccf4ce05b163e&scene=132#wechat_redirect)
