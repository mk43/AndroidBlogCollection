# AndroidBlogCollection

> this repo aims to collect some high quality basic knowledge Android Blog.  Just like source code analysis or something.
> 
> 这个仓库致力于收集我在学习 Android 开发过程所遇到的高质量的基础知识文章. 类似于源码分析之类的, 可以帮大家加深对基础原理的理解.
> 
> 现在网络上有太多的知识可供学习, 但是作为一个自学者, 是好事也是坏事, 好事指不用担心没资源, 坏事是指对学习效率,理解程度和知识体系搭建都不太好.网上的文章不全是高质量的, 而且很多都是重复的碎片化知识,大家写的都差不多.所以为了自己的系统学习, 建议买书, 碰到哪个模块不懂再找大牛的 Blog 加深理解. 
> 
> 首先可以肯定像我这种刚刚入门的在写文章的高度不如大牛.而对于基础的知识,特别是涉及源码解析, 只要以一份资料为主就可以了. 最多加一两份做参考. 所以, 基本这种类型的文章, 我会收藏整理在这篇文章里并且永久更新. 同时自己也会利用课余时间把自己的实践项目以一个入门的学习者的视角解析, 相信这样对初学的开发者是比较友好的.如果你和也一样处在这个阶段, 欢迎关注这篇文章.
> 
> 这里永久更新这类基础知识解读. [GitHub](https://github.com/mk43) 和 [Blog](http://fitzeng.org) 永久更新项目练习项目. 如果对你有帮助欢迎 Star ^_^;

## Chapter UI

### View 的绘制源码解析
> 这里推荐的是[Carson_Ho](http://www.jianshu.com/nb/9976005)的一系列源码分析教程, 主要是从 View 和 ViewGroup 的测量, 布局和绘制过程进行详细分析, 很多图示十分清晰易懂, 对于初学者和进阶者都是很不错的学习资料. 如果有找到其他的好的教程我还会继续加上.

- [自定义View基础 - 最易懂的自定义View原理系列(1)](http://www.jianshu.com/p/146e5cec4863)
- [自定义View Measure过程 - 最易懂的自定义View原理系列(2)](http://www.jianshu.com/p/1dab927b2f36)
- [自定义View Layout过程 - 最易懂的自定义View原理系列(3)](http://www.jianshu.com/p/158736a2549d)
- [自定义View Draw过程- 最易懂的自定义View原理系列(4)](http://www.jianshu.com/p/95afeb7c8335)

### View 相关类解析
> 这个主要是介绍一些对自定义 View 过程中需要仔细了解的一些类的使用. 

- [Path类的最全面详解 - 自定义View应用系列](http://www.jianshu.com/p/2c19abde958c)
- [Canvas类的最全面详解 - 自定义View应用系列](http://www.jianshu.com/p/762b490403c3)

<!--more-->

### XML使用示例

> 这里推荐[Keegan小钢](http://keeganlee.me/)的Android样式的开发相关教程, 通过十分简洁的小例子帮你快速实现对 XML 的了解和使用.

- [Android样式的开发:shape篇](http://keeganlee.me/post/android/20150830)
- [Android样式的开发:selector篇](http://keeganlee.me/post/android/20150905)
- [Android样式的开发:layer-list篇](http://keeganlee.me/post/android/20150909)
- [Android样式的开发:drawable汇总篇](http://keeganlee.me/post/android/20150916)
- [Android样式的开发:View Animation篇](http://keeganlee.me/post/android/20151003)
- [Android样式的开发:Property Animation篇](http://keeganlee.me/post/android/20151026)
- [Android样式的开发:Style篇](http://keeganlee.me/post/android/20151031)


### 事件分发
> 事件分发是一个重要的知识点, 在面试中也有很大可能几率被问到.在开发中经常会遇到, 只有彻底理解好了在写代码时候才能思路清晰.希望以下文章能帮助你我弄清事件分发机制.

- [Android事件分发机制详解：史上最全面、最易懂](http://www.jianshu.com/p/38015afcdb58)