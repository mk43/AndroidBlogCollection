# AndroidBlogCollection V2
> this repo aims to collect some high quality basic knowledge Android Blog.  Just like source code analysis or something.
> 
> 这个仓库致力于收集我在学习 Android 开发过程所遇到的高质量的基础知识文章. 类似于源码分析之类的, 可以帮大家加深对基础原理的理解.


## 0. Start

### > 前言
 
> 现在网络上有太多的知识可供学习, 但是作为一个自学者, 是好事也是坏事, 好事指不用担心没资源, 坏事是指对学习效率,理解程度和知识体系搭建都不太好.网上的文章不全是高质量的, 而且很多都是重复的碎片化知识,大家写的都差不多.所以为了自己的系统学习, 建议买书, 碰到哪个模块不懂再找大牛的 Blog 加深理解. 
> 
> 所以可以看到我推荐的基本都是成一个小体系的系列文章, 可以帮助我们形成一个好的"学习思维树". 而不是一大堆"散叶". 而其他文章主要是作为自己加深理解, 对某个知识点深入学习的参考.
> 
> 首先可以肯定像我这种刚刚入门的在写文章的高度和视野都不如大牛. 而对于基础的知识,特别是涉及源码解析, 只要以一份资料为主就可以了. 最多加一两份做参考. 所以, 基本这种类型的文章, 我会收藏整理在这篇文章里并且永久更新. 同时自己也会利用课余时间把自己的实践项目以一个入门的学习者的视角解析, 相信这样对初学的开发者是比较友好的.如果你和我也一样处在这个阶段, 欢迎关注这篇文章.
> 
> 这里永久更新这类基础知识解读. [GitHub](https://github.com/mk43) 和 [Blog](http://fitzeng.org) 永久更新练习项目. 如果对你有帮助欢迎 Star ^_^;
 
### > 更新
- v3 : [敬请期待...](https://github.com/mk43)
- v2 : 添加 `JVM` `设计模式` `常用框架` `计算机基础` 四大模块优质 Blog 收集
- v1 : 以 Android View 基础知识为主的 Blog 收集.

<!--more-->

## 1. UI

### > View 的绘制源码解析
> 这里推荐的是[Carson_Ho](http://www.jianshu.com/nb/9976005)的一系列源码分析教程, 主要是从 View 和 ViewGroup 的测量, 布局和绘制过程进行详细分析, 很多图示十分清晰易懂, 对于初学者和进阶者都是很不错的学习资料. 如果有找到其他的好的教程我还会继续加上.

- [自定义View基础 - 最易懂的自定义View原理系列(1)](http://www.jianshu.com/p/146e5cec4863)
- [自定义View Measure过程 - 最易懂的自定义View原理系列(2)](http://www.jianshu.com/p/1dab927b2f36)
- [自定义View Layout过程 - 最易懂的自定义View原理系列(3)](http://www.jianshu.com/p/158736a2549d)
- [自定义View Draw过程- 最易懂的自定义View原理系列(4)](http://www.jianshu.com/p/95afeb7c8335)

> 前面给了 View 的绘制最主要的三个过程进行了详细分析的 Blog, 在前面的阅读基础上,下面给出[郭霖大神](http://blog.csdn.net/guolin_blog)的 View 的工作原理系列文章. 相信在读完以下四篇文章之后你会对 View 有一个重新认识的.

- [Android LayoutInflater原理分析，带你一步步深入了解View(一)](http://blog.csdn.net/guolin_blog/article/details/12921889)
- [ Android视图绘制流程完全解析，带你一步步深入了解View(二)](http://blog.csdn.net/guolin_blog/article/details/16330267)
- [Android视图状态及重绘流程分析，带你一步步深入了解View(三)](http://blog.csdn.net/guolin_blog/article/details/17045157)
- [ Android自定义View的实现方法，带你一步步深入了解View(四)](http://blog.csdn.net/guolin_blog/article/details/17357967)

> 下面介绍[扔物线](https://juejin.im/user/552f20a7e4b060d72a89d87f)的[HenCoder：给高级 Android 工程师的进阶手册](https://juejin.im/post/59591e42f265da6c407350c0), 包含了视频讲解. 目前持续更新, 在学习完前面的 Blog 并进行了部分实践 Demo 后把这当做复习提高挺不错的, 同时我也会一直关注并更新.

- [HenCoder Android 开发进阶: 自定义 View 1-1 绘制基础](https://juejin.im/post/5962a3746fb9a06ba2687226)

### > View 相关类解析
> 这个主要是介绍一些对自定义 View 过程中需要仔细了解的一些类的使用. 

- [Path类的最全面详解 - 自定义View应用系列](http://www.jianshu.com/p/2c19abde958c)
- [Canvas类的最全面详解 - 自定义View应用系列](http://www.jianshu.com/p/762b490403c3)

### > XML 使用示例

> 这里推荐[Keegan小钢](http://keeganlee.me/)的Android样式的开发相关教程, 通过十分简洁的小例子帮你快速实现对 XML 的了解和使用.

- [Android样式的开发:shape篇](http://keeganlee.me/post/android/20150830)
- [Android样式的开发:selector篇](http://keeganlee.me/post/android/20150905)
- [Android样式的开发:layer-list篇](http://keeganlee.me/post/android/20150909)
- [Android样式的开发:drawable汇总篇](http://keeganlee.me/post/android/20150916)
- [Android样式的开发:View Animation篇](http://keeganlee.me/post/android/20151003)
- [Android样式的开发:Property Animation篇](http://keeganlee.me/post/android/20151026)
- [Android样式的开发:Style篇](http://keeganlee.me/post/android/20151031)

### > 动画

> Android 动画介绍, 感谢[阿祥JOKER](http://www.jianshu.com/p/551f84402752) 分享.

- [Android动画解析](http://www.jianshu.com/p/551f84402752)

> 重点!!!这里还是推荐郭霖大神的文章. 然后后面补充一篇偏知识点式的文章供复习.

- [Android属性动画完全解析(上)，初识属性动画的基本用法](http://blog.csdn.net/guolin_blog/article/details/43536355)
- [ Android属性动画完全解析(中)，ValueAnimator和ObjectAnimator的高级用法](http://blog.csdn.net/guolin_blog/article/details/43816093)
- [ Android属性动画完全解析(下)，Interpolator和ViewPropertyAnimator的用法](http://blog.csdn.net/guolin_blog/article/details/44171115)
- 补充参考:[Android动画，一篇就够](http://www.jianshu.com/p/b7aa2a4a9787), 感谢[Shaun白一辰](http://www.jianshu.com/u/b7e9763ffd86)的分享.

### > 事件分发
> 事件分发是一个重要的知识点, 在面试中也有很大几率被问到.在开发中经常会遇到, 只有彻底理解好了在写代码时候才能思路清晰.希望以下文章能帮助你我弄清事件分发机制.

- [Android事件分发机制详解：史上最全面、最易懂](http://www.jianshu.com/p/38015afcdb58)

### > 自成体系的 View 教程
> 这里主要是推荐一些其他优秀文章作为参考阅读, 同样也是自成体系的. 

- [GcsSloop : 安卓自定义View教程目录](http://www.gcssloop.com/customview/CustomViewIndex/)

## 2. Java API

> 这里主要是对 Java API 中的一些重要的源码解析进行收集. 同时也是面试重点, 希望能加深对 Java 的认识. 做到真的理解底层实现而不是只会使用.
> 
> 由于 Java 面太广, 所以在这里主要是以知识点的形式覆盖基本概念. 这里推荐 [树上月](http://www.cnblogs.com/chenssy/category/525010.html) 的教程. 从 Blog 介绍看接触 Java 有一段时间, 所以分析会比较深入且正确. 更主要的是, 他把 Java 类文章基本都串起来了, 共有 38 篇可供学习. 文章太多就不一一贴链接了...

- [想学Java, 值得一阅](http://www.cnblogs.com/chenssy/category/525010.html)

## 3. 浅析JVM

> 当然这块知识会推荐一本书, 是[《深入理解 Java 虚拟机》](https://book.douban.com/subject/24722612/)， 而网上的那些分析大多数都是基于这本书的。这里会收集一些较好的讲解共在线阅读。

## 4. 深入理解设计模式

> 这块也有一本书[《Android 源码设计模式解析与实战》](https://book.douban.com/subject/26644935/)推荐. 

- [Java 的 23 种设计模式全解析](https://juejin.im/entry/58faca0a1b69e600588cd952)

## 5. Android 常用框架分析


## 6. 计算机基础

### > 数据库

[如果有人问你数据库的原理，叫他看这篇文章](http://blog.jobbole.com/100349/?from=timeline)

### > 网络

### > 操作系统