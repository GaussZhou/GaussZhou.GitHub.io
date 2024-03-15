# 数据结构 理论基础

## 什么是数据结构

数据结构是计算机中存储、组织数据的方式。

不同种类的数据结构适合不同种类的应用，部分数据结构甚至是为了解决特定问题而设计出来的。例如 B 树即为加快树状结构访问速度而设计的数据结构，常被应用在数据库和文件系统上。

在计算机程序设计的过程中，选择适当的数据结构是一项重要工作。许多大型系统的编写经验显示，程序设计的困难程度与最终成果的质量与表现，取决于是否选择了最适合的数据结构。

## 什么是算法

解决某个问题的计算方法，步骤称之为算法，在计算机中，指用计算机解决问题的方法。

在计算机中针对某个问题的算法有很多种，我们对算法的效率从两个方面来考量，分别是

- 时间复杂度
- 空间复杂度

## 时间复杂度

算法的时间复杂度是指算法需要消耗的时间资源。一般来说，计算机算法是问题规模`n`的函数`f(n)`，算法的时间复杂度也因此记做`T(n)=O(f(n)`

## 空间复杂度

算法的空间复杂度是指算法需要消耗的空间资源。其计算和表示方法与时间复杂度类似，一般都用复杂度的渐近性来表示。同时间复杂度相比，空间复杂度的分析要简单得多。

## 取舍

计算机科学中的空间与时间取舍，有时被描述为`空间换时间`，来优化时间复杂度提升运算速率，或者`时间换空间`，来优化空间复杂度，减少计算机存储资源的消耗。

## 学习资料

[维基百科 数据结构](https://zh.wikipedia.org/wiki/数据结构)

[维基百科 算法](https://zh.wikipedia.org/wiki/算法)

[豆瓣读书 《学习 JavaScript 数据结构与算法》](https://book.douban.com/subject/26639401/)

[Classic algorithms and data structures implemented in JavaScript](https://github.com/felipernb/algorithms.js)