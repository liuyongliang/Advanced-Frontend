# 高级前端知识架构
* [异步](https://github.com/liuyongliang/Advanced-Frontend#%E5%BC%82%E6%AD%A5)
    * [异步编程](https://github.com/liuyongliang/Advanced-Frontend#%E5%BC%82%E6%AD%A5%E7%BC%96%E7%A8%8B)
    * [async/await](https://github.com/liuyongliang/Advanced-Frontend#asyncawait)
    * [Promise](https://github.com/liuyongliang/Advanced-Frontend#promise)
* [服务器端渲染SSR](https://github.com/liuyongliang/Advanced-Frontend#%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AB%AF%E6%B8%B2%E6%9F%93ssr)
    * [SSR指南](https://github.com/liuyongliang/Advanced-Frontend#ssr%E6%8C%87%E5%8D%97)
    * [SSR框架](https://github.com/liuyongliang/Advanced-Frontend#ssr%E6%A1%86%E6%9E%B6)
* [函数式编程](https://github.com/liuyongliang/Advanced-Frontend#%E5%87%BD%E6%95%B0%E5%BC%8F%E7%BC%96%E7%A8%8B)
    * [函数式编程](https://github.com/liuyongliang/Advanced-Frontend#%E5%87%BD%E6%95%B0%E5%BC%8F%E7%BC%96%E7%A8%8B-1)
* [代码质量](https://github.com/liuyongliang/Advanced-Frontend#%E4%BB%A3%E7%A0%81%E8%B4%A8%E9%87%8F)
    * [代码规范](https://github.com/liuyongliang/Advanced-Frontend#%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83)
    * [JavaScript](https://github.com/liuyongliang/Advanced-Frontend#javascript)
    * [TypeScript](https://github.com/liuyongliang/Advanced-Frontend#typescript)
* [性能优化](https://github.com/liuyongliang/Advanced-Frontend#%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96)
    * [调试工具](https://github.com/liuyongliang/Advanced-Frontend#%E8%B0%83%E8%AF%95%E5%B7%A5%E5%85%B7)
    * [H5优化](https://github.com/liuyongliang/Advanced-Frontend#h5%E4%BC%98%E5%8C%96)
    * [缓存](https://github.com/liuyongliang/Advanced-Frontend#%E7%BC%93%E5%AD%98)
    * [压缩](https://github.com/liuyongliang/Advanced-Frontend#%E5%8E%8B%E7%BC%A9)
    * [内存](https://github.com/liuyongliang/Advanced-Frontend#%E5%86%85%E5%AD%98)
    * [渲染](https://github.com/liuyongliang/Advanced-Frontend#%E6%B8%B2%E6%9F%93)
    * [资源加载](https://github.com/liuyongliang/Advanced-Frontend#%E8%B5%84%E6%BA%90%E5%8A%A0%E8%BD%BD)
* [监控](https://github.com/liuyongliang/Advanced-Frontend#%E7%9B%91%E6%8E%A7)
    * [异常捕获](https://github.com/liuyongliang/Advanced-Frontend#%E5%BC%82%E5%B8%B8%E6%8D%95%E8%8E%B7)
    * [页面性能监控](https://github.com/liuyongliang/Advanced-Frontend#%E9%A1%B5%E9%9D%A2%E6%80%A7%E8%83%BD%E7%9B%91%E6%8E%A7)
    * [埋点](https://github.com/liuyongliang/Advanced-Frontend#%E5%9F%8B%E7%82%B9)
    	 *   [用户行为](https://github.com/liuyongliang/Advanced-Frontend#%E7%94%A8%E6%88%B7%E8%A1%8C%E4%B8%BA)
* [设计模式](https://github.com/liuyongliang/Advanced-Frontend#%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F)
	 * [概念](https://github.com/liuyongliang/Advanced-Frontend#%E6%A6%82%E5%BF%B5)
    * [单体模式](https://github.com/liuyongliang/Advanced-Frontend#%E5%8D%95%E4%BD%93%E6%A8%A1%E5%BC%8F)
    * [工厂模式](https://github.com/liuyongliang/Advanced-Frontend#%E5%B7%A5%E5%8E%82%E6%A8%A1%E5%BC%8F)
* [工程化](https://github.com/liuyongliang/Advanced-Frontend#%E5%B7%A5%E7%A8%8B%E5%8C%96)
    * [构建工具](https://github.com/liuyongliang/Advanced-Frontend#%E6%9E%84%E5%BB%BA%E5%B7%A5%E5%85%B7)
    * [webpack](https://github.com/liuyongliang/Advanced-Frontend#webpack)
    * [脚手架](https://github.com/liuyongliang/Advanced-Frontend#%E8%84%9A%E6%89%8B%E6%9E%B6)
* [前端标准/实践](https://github.com/liuyongliang/Advanced-Frontend#%E5%89%8D%E7%AB%AF%E6%A0%87%E5%87%86%E5%AE%9E%E8%B7%B5)
	*  [前端标准](https://github.com/liuyongliang/Advanced-Frontend#%E5%89%8D%E7%AB%AF%E6%A0%87%E5%87%86) 
	* [骨架屏](https://github.com/liuyongliang/Advanced-Frontend#%E9%AA%A8%E6%9E%B6%E5%B1%8F) 
* [前端算法](https://github.com/liuyongliang/Advanced-Frontend#%E5%89%8D%E7%AB%AF%E7%AE%97%E6%B3%95)
	* [递归](https://github.com/liuyongliang/Advanced-Frontend#%E9%80%92%E5%BD%92)
	* [冒泡](https://github.com/liuyongliang/Advanced-Frontend#%E5%86%92%E6%B3%A1)
	* [动态规划](https://github.com/liuyongliang/Advanced-Frontend#%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92)
	* [二分查找](https://github.com/liuyongliang/Advanced-Frontend#%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE)
	* [链表和数组](https://github.com/liuyongliang/Advanced-Frontend#%E9%93%BE%E8%A1%A8%E5%92%8C%E6%95%B0%E7%BB%84)
* [浏览器](https://github.com/liuyongliang/Advanced-Frontend#%E6%B5%8F%E8%A7%88%E5%99%A8)
    * [自动化](https://github.com/liuyongliang/Advanced-Frontend#%E8%87%AA%E5%8A%A8%E5%8C%96)
* [网络](https://github.com/liuyongliang/Advanced-Frontend#%E7%BD%91%E7%BB%9C)
    * [OSI七层协议](https://github.com/liuyongliang/Advanced-Frontend#osi%E4%B8%83%E5%B1%82%E5%8D%8F%E8%AE%AE)
    * [DNS解析](https://github.com/liuyongliang/Advanced-Frontend#dns%E8%A7%A3%E6%9E%90)
* [协议](https://github.com/liuyongliang/Advanced-Frontend#%E5%8D%8F%E8%AE%AE)
    * [TCP](https://github.com/liuyongliang/Advanced-Frontend#tcp)
    * [UDP](https://github.com/liuyongliang/Advanced-Frontend#udp)
* [测试](https://github.com/liuyongliang/Advanced-Frontend#%E6%B5%8B%E8%AF%95)
    * [单元测试](https://github.com/liuyongliang/Advanced-Frontend#%E5%8D%95%E5%85%83%E6%B5%8B%E8%AF%95)
    * [自动化测试](https://github.com/liuyongliang/Advanced-Frontend#%E8%87%AA%E5%8A%A8%E5%8C%96%E6%B5%8B%E8%AF%95)
* [可视化](https://github.com/liuyongliang/Advanced-Frontend#%E5%8F%AF%E8%A7%86%E5%8C%96)
    * [d3](https://github.com/liuyongliang/Advanced-Frontend#d3)
    * [three.js](https://github.com/liuyongliang/Advanced-Frontend#threejs)
* [NodeJS](https://github.com/liuyongliang/Advanced-Frontend#nodejs)
* [移动web开发](https://github.com/liuyongliang/Advanced-Frontend#%E7%A7%BB%E5%8A%A8web%E5%BC%80%E5%8F%91)
    * [Hybrid](https://github.com/liuyongliang/Advanced-Frontend#hybrid)
    * [Flutter](https://github.com/liuyongliang/Advanced-Frontend#flutter)
* [物联网](https://github.com/liuyongliang/Advanced-Frontend#%E7%89%A9%E8%81%94%E7%BD%91)
* [安全](https://github.com/liuyongliang/Advanced-Frontend#%E5%AE%89%E5%85%A8)
    * [抓包/代理](https://github.com/liuyongliang/Advanced-Frontend#%E6%8A%93%E5%8C%85%E4%BB%A3%E7%90%86)
    * [监控技术](https://github.com/liuyongliang/Advanced-Frontend#%E7%9B%91%E6%8E%A7%E6%8A%80%E6%9C%AF)
* [机器学习](https://github.com/liuyongliang/Advanced-Frontend#%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0)
    * [TensorFlow](https://github.com/liuyongliang/Advanced-Frontend#tensorflow)
* [客户端开发](https://github.com/liuyongliang/Advanced-Frontend#%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%BC%80%E5%8F%91)
    * [electron](https://github.com/liuyongliang/Advanced-Frontend#electron)
    * [nw.js](https://github.com/liuyongliang/Advanced-Frontend#nwjs)
    * [chrome插件](https://github.com/liuyongliang/Advanced-Frontend#chrome%E6%8F%92%E4%BB%B6)
* [源码分析](https://github.com/liuyongliang/Advanced-Frontend#%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90)
    * [vue源码](https://github.com/liuyongliang/Advanced-Frontend#vue%E6%BA%90%E7%A0%81)
    * [react源码](https://github.com/liuyongliang/Advanced-Frontend#react%E6%BA%90%E7%A0%81)
    * [TypeScript](https://github.com/liuyongliang/Advanced-Frontend#typescript-1)
    * [JavaScript](https://github.com/liuyongliang/Advanced-Frontend#javascript-1)
* [项目管理](https://github.com/liuyongliang/Advanced-Frontend#%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86)
* [前端发展趋势](https://github.com/liuyongliang/Advanced-Frontend#%E5%89%8D%E7%AB%AF%E5%8F%91%E5%B1%95%E8%B6%8B%E5%8A%BF)
	* [前端发展趋势](https://github.com/liuyongliang/Advanced-Frontend#%E5%89%8D%E7%AB%AF%E5%8F%91%E5%B1%95%E8%B6%8B%E5%8A%BF-1)
* [面试](https://github.com/liuyongliang/Advanced-Frontend#%E9%9D%A2%E8%AF%95)
* [社区/会议](https://github.com/liuyongliang/Advanced-Frontend#%E7%A4%BE%E5%8C%BA%E4%BC%9A%E8%AE%AE)


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

* [《Promise链式调用原理 》](https://github.com/LuckyWinty/blog/issues/3)


## 服务器端渲染SSR

### SSR指南

* [《浅谈服务端渲染(SSR)》](https://www.jianshu.com/p/10b6074d772c)

    * 简单理解是将组件或页面通过服务器生成html字符串，再发送到浏览器，最后将静态标记"混合"为客户端上完全交互的应用程序    

* [《有必要使用服务器端渲染(SSR)吗？》](https://www.zhihu.com/question/308792091?sort=created)

* [《从头开始，彻底理解服务端渲染原理》](https://blog.csdn.net/qq_29438877/article/details/98477160)

* [《精读前后端渲染之争》](https://github.com/dt-fe/weekly/blob/v2/003.%E7%B2%BE%E8%AF%BB%E5%89%8D%E5%90%8E%E7%AB%AF%E6%B8%B2%E6%9F%93%E4%B9%8B%E4%BA%89.md)

* [《带你五步学会Vue SSR》](https://mp.weixin.qq.com/s/phZ8jFVrAwcCfuNlZDFG1w)
 
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

* [《中高级前端必须注意的40条移动端H5坑位指南 | 网易三年实践》](https://juejin.cn/post/6921886428158754829)

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

* [《用户行为帧记录》](https://github.com/LuckyWinty/blog/blob/master/markdown/other/%E7%94%A8%E6%88%B7%E8%A1%8C%E4%B8%BA%E5%B8%A7%E8%AE%B0%E5%BD%95.md)

## 设计模式

### 概念

* [《深入理解JavaScript的设计模式》](https://mp.weixin.qq.com/s?src=11&timestamp=1612489338&ver=2871&signature=KFMlX3Mr3ajZfuJ1LLbh-LsuDQ8w9iAFCRIIsRW0zK4YozWJ5bbwRgcTd4i5Fo*v-76TGd7n2YFqZV6dSHj9s2SUzTNrtPvf4YW5F3PjDKXPzEd5jFzKrO*cKLbyt22n&new=1)
	* 在软件工程中，设计模式是软件设计中常见问题的可重用解决方案。设计模式代表了经验丰富的软件开发人员所使用的最佳实践。设计模式可以看作是编程模板

* [《JavaScript设计模式经典-面向对象中六大原则》](https://mp.weixin.qq.com/s?src=11&timestamp=1612489338&ver=2871&signature=513OASntwkXcghheaX9ciMwkkrFlDTK*ueVZ7BFY-VfJkl5MlxycRuqNrdTviRUUWb548PBFN4KY5GN3jC*uZY5pSLmiypKKkz8oT4ZwIBpruHdwN*s9wE28Y4MdnON2&new=1)

* [《介绍几个JavaScript设计模式及场景应用》](https://mp.weixin.qq.com/s?src=11&timestamp=1612489692&ver=2871&signature=kxq9X0tE0C42bPz9nFFhK4qxzZ7LOggpalvHgR76Mg-8cQiezkrGFNEQgEZhpnmZc8ilBEegc5TA2q5vRr7QW4Y-GeqR9cXh5s0SK-0p-sSvS*Mj9TXeHDWCBF65AS8X&new=1)

### 单体模式

* [《JavaScript设计模式——单体模式》](https://mp.weixin.qq.com/s?src=11&timestamp=1612489113&ver=2871&signature=l8PtIf29kNUDTEfYQIwCw*xvieBkVLJ32jDufMWLxtUfzY4azRwzp11X4tC4aFbf8pxnmWFxGRMF6gYc5i0Cpdv-YehRqO40I*HlCvkBimAOPGEdoNK0XpfyQbn3EWFl&new=1)
	* 单体模式(Singleton Pattern)的思想在于保证一个特定类仅有一个实例，即不管使用这个类创建多少个新对象，都会得到与第一次创建的对象完全相同。

### 工厂模式

* [《JavaScript设计模式——工厂模式》](https://mp.weixin.qq.com/s?src=11&timestamp=1612489200&ver=2871&signature=U2v5PFefC0EgXRYE0aT1GDPWGRJlMFlVWvBIQ1SZ-WqCpmavrX8qxoxs9w36qx4*QHCn8WWc6BO3KPI74jP-ztBSXsijXwaQI5lZwek-HfN737YFXsrarw-RI-odxBr3&new=1)


## 工程化

### 构建工具

*  [《从Npm Script到Webpack，6种常见的前端构建工具对比》](https://blog.csdn.net/broadview2006/article/details/79091719)

### webpack

* [《Webpack4打包机制原理解析》](https://mp.weixin.qq.com/s?src=11&timestamp=1612747768&ver=2877&signature=in2-reLaVXdYVNA7WWISwveiX-xOYgYydmaQb81Y5iJWA-Clf6nlXSGeyo2Wlml8odgYefLeMQgqT6Kf*2XkKlEZ4IVf1mIaYWvbd3QOKW3zLuxEWopeGjaJnIZXbsjO&new=1)
	* webpack是一个打包模块化 JavaScript 的工具，在 webpack里一切文件皆模块，通过 Loader 转换文件，通过 Plugin 注入钩子，最后输出由多个模块组合成的文件。webpack专注于构建模块化项目。

* [《从webpack4打包文件说起》](https://cloud.tencent.com/developer/article/1172453)

* [《揭秘webpack插件的工作原理》](https://mp.weixin.qq.com/s?src=11&timestamp=1612747768&ver=2877&signature=YdDKUzIEqCOwhJJ1Z56I2YE*7V9x4oIh6s9dgokEtuQdPW8UYFj963hepTbjjKd9pGWHzj3P2JX6n4vUPDlsdttmyx6yzjROt7AVGHNsf0bb9OSZTZkmziQXXM6Ne*5Y&new=1)

* [《Webpack5 新特性业务落地实战》](https://juejin.cn/post/6924258563862822919)


### 脚手架

* [《如何写一个标准的前端脚手架》](https://zhuanlan.zhihu.com/p/105846231)


## 前端标准/实践

### 前端标准

* [《Code Guide》](http://alloyteam.github.io/CodeGuide/)
	* 通过分析github代码库总结出来的工程师代码书写习惯

* [《JavaScript代码规范（Airbnb）》](https://github.com/linpenghui958/note/blob/master/js%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83.md)

* [《【译】Google 官方文章——如何去做coder review》](https://juejin.cn/post/6844903949347061768)
	*  CR(Code review)主要目的在于确保Google 的代码库代码质量越来越好。而所有相关的工具与流程皆是因应这个目的而生。为达到此目的，势必需要做出一连串的权衡与取舍

* [《字节研发设施下的 Git 工作流》](https://juejin.cn/post/6875874533228838925)

	* Git 提供了丰富的分支策略和工作流方式，我们在深入学习业界 Git 工作流时，每种工作流都设计的非常好，似乎都能运用到团队实践

### 骨架屏 

* [《一个简易的预渲染自动骨架屏方案》](https://zhuanlan.zhihu.com/p/166009071)

## 前端算法

### 递归

*  [《递归》](https://mp.weixin.qq.com/s?src=11&timestamp=1612749261&ver=2877&signature=YwnPW8Lm2ohk7fbjf54ovzJUJfg9p77-V5IahOQbMoGq01irmIMM-QmHlSDAOwSKzLScjWEnIFXdVr4*tZKba-jq5-BurWDu*dBkSbsjtCE1RI8H7NxTdIMEFTxHwvMP&new=1)

* [《前端电商 sku 全排列的递归回溯算法实战》](https://github.com/sl1673495/blogs/issues/50)

### 冒泡

*  [《冒泡排序》](https://juejin.cn/post/6910033657121996808)

### 动态规划

*  [《动态规划》](https://juejin.cn/post/6844903949795852295)

### 二分查找

*  [《二分查找》](https://github.com/USTB-musion/fee-skills/issues/21)

### 链表和数组

* [《链表和数组》](https://github.com/USTB-musion/fee-skills/issues/20)

## 浏览器

### 自动化

* [《提高 Web 自动化效率：建立一个用于 Web 自动化的浏览器环境》](https://mp.weixin.qq.com/s?src=11&timestamp=1612749613&ver=2877&signature=MJD-qP0zJhtrFrhTmEbdkcFUOw*yvWJAqWSvgLkTnB35y9GmUGFPG5mdBukDnU60y4CWwrnOdtJDNESmsgk7YNhbDBawUJV*3NOtp8wqltAOAXJzwwXk4KFFGOdO36yp&new=1)

## 网络

### OSI七层协议

### DNS解析

## 协议

### TCP

### UDP

## 测试

### 单元测试

### 自动化测试

## 可视化

### d3

### three.js

## NodeJS

## 移动web开发

### Hybrid

### Flutter

## 物联网

## 安全

### 抓包/代理

### 监控技术

## 机器学习

### TensorFlow

## 客户端开发
### electron
### nw.js
### chrome插件

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

### JavaScript

* [《Javascript 深拷贝》](https://juejin.cn/post/6926172825757679624)

## 项目管理

## 前端发展趋势

### 前端发展趋势

* [《2021年前端发展预测》](https://mp.weixin.qq.com/s?__biz=MzUxMzcxMzE5Ng==&mid=2247506245&idx=1&sn=e498d49616ac8d9ae446ad9cb3ca5658&chksm=f9526c06ce25e5104940c19c42e49a54bb8e3d646b645d689ce0a5b7fc0e6e5ccf4ce05b163e&scene=132#wechat_redirect)

## 面试

* [《今天聊：你为什么迟迟进不去大厂》](https://juejin.cn/post/6924860368393076749)

## 社区/会议
