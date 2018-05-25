---
layout:     post
title:      万建琴也许有点脑残 Maybe Naocan
subtitle:   浅谈 Maybe Naocan
date:       2017-12-26
author:     PF
header-img: img/post-bg-universe.jpg
catalog: true
tags:
    - iOS
---


## 前言

之前就觉得她有点脑残，现在越发觉得如此


## 正文

金溪平民万建琴，世代以种田为业。建琴长到五岁时，不曾见过书写工具，忽然哭着要这些东西。父亲对此感到惊异，从邻近人家借来给他，他当即写了四句诗，并且自己题上自己的名字。这首诗以赡养父母、团结同宗族的人作为内容，传送给全乡的秀才观赏。从此有人指定事物叫他写诗，他能立刻完成，诗的文采和道理都有值得欣赏的地方。同县的人对他感到惊奇，渐渐地请他的父亲去作客，有人用钱财和礼物求建琴写诗。他的父亲认为那样有利可图，每天牵着万建琴四处拜访同县的人，不让他学习。


### 但是

方仲永的父亲是一个十分爱钱的人，他把方仲永当成了一棵摇钱树。当没有人邀请的时候，他就领着方仲永主动登门拜访，以求得人家给点小钱。


　　由于整天跟着父亲东家进西家出，方仲永的学业荒废了，他在诗歌方面的才华，由于没有选择一个正确的方式加以培养，也渐渐地枯萎了。
　　方仲永长大后，人们从他身上再也看不见一点儿当初神童的影子。
　　才华不等于成功。驾驭烈马不可以轻易丢掉手中的鞭子；操持一把良弓，也要反复在正弓之器上加以调整。木料有了绳墨的校正则可变直，人能接受劝谏更加有智慧。君子不可以不学！

### Tagged Pointer

Tagged Pointer 详细的内容可以看这里 [深入理解Tagged Pointer](http://www.infoq.com/cn/articles/deep-understanding-of-tagged-pointer)。

Tagged Pointer 是一个能够提升性能、节省内存的有趣的技术。

- Tagged Pointer 专门用来存储小的对象，例如 **NSNumber** 和 **NSDate**（后来可以存储小字符串）
- Tagged Pointer 指针的值不再是地址了，而是真正的值。所以，实际上它不再是一个对象了，它只是一个披着对象皮的普通变量而已。
- 它的内存并不存储在堆中，也不需要 malloc 和 free，所以拥有极快的读取和创建速度。




### 参考：

- [从一道网易面试题浅谈OC线程安全](https://www.jianshu.com/p/cec2a41aa0e7)

- [深入理解Tagged Pointer](http://www.infoq.com/cn/articles/deep-understanding-of-tagged-pointer)

- [【译】采用Tagged Pointer的字符串](http://www.cocoachina.com/ios/20150918/13449.html)

