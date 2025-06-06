---
comments: true
---
# C++ 高级程序设计

## 课程信息
0.2
**保研必修课**，讲 C++。内容上有两个部分。第一部分主要讲 C++ 结构化编程的特性，比如数据结构与类型、函数、泛型、模板等等；第二部分主要讲 C++ 中的面向对象程序设计，以及一些现代 C++。

- 授课老师：郑滔、潘敏学
- 课时：3 学分。每周一次课，前 2 个小时上课，后 1 个小时上机 (2024)
- 成绩：平时成绩 (40%，包括平时作业、签到、平时机考)，期末笔试 (40%)，期末机考 (20%)

- 教材：太多了，找 PPT 看吧

## 课程资源

- cpp reference
- [The Standard : Standard C++](https://isocpp.org/std/the-standard)

- [简述 | Co-rricula](https://xjynotes.top/C++高级程序设计/c++概述)

- [分类 - 2020-C++高级程序设计 - SpriCoder的博客](https://spricoder.github.io/categories/2020-C-高级程序设计/)

- [分类: 2022Spring-C++ 高级程序设计 | EagleBear2002 的博客](https://eaglebear2002.github.io/categories/南京大学软件学院本科课程/2022Spring-C-高级程序设计/)

## 上课情况

上课内容分为两大部分：结构化编程和面向对象。

结构化编程部分是郑滔老师讲，知识偏零碎，从 C98 到 C++14 都有覆盖。这些语言的小特性乐趣十足，郑滔老师讲得也相当引人入胜。在软院一众老师可算 T0。

面向对象部分是潘敏学老师讲，知识点相对集中。不过与其说是 C++ 的面向对象，不如说是 Java 的 OO 在 C++ 中的实现(然而实际很少有人这样干)。现代 C++ 的很多特性和实践都没讲到，RAII 和所有权这些也只是略微涉及，更不要说 C++ 的一些哲学了。总得来说还是一个套着 C++ 皮的 Java OO 课。潘敏学老师讲得中规中矩，不过也算软院讲课还行的老师之一了。

## 平时作业

平时大概有四五次 oj。每次 oj 有 3 ~ 5 道题，涉及简单的算法(贪心, 递归, dfs, dp)、面向对象和 C++ 特色题。oj 体验很糟糕，老师鼓励大家全程使用 oj 网页编码，但是 oj 网页 IDE 的体验比记事本写好不到哪去。经常复制粘贴的时候吞代码、调试时卡死等等。

建议使用本地 IDE 编码，调试完了再复制粘贴到 oj 网页上。

不过平时作业有一次是谢神出的 Trie 树，是国外课程作业魔改而来，质量很高。 ~~C++ 课作业最有 C++ 味的一集~~ 。

## 平时机考

平时机考大概有两次，地点在费楼机房。考题莫名其妙且恶心。大致是给一个场景，写类似增删改查的业务代码，并且很多时候是在和结构化输入输出做斗争，不明白考这个还限时意义在哪，也没一点 C++ 的特点，换什么语言都能写。用这种没有技术含量的题目来考察 C++ 的语法和特性，通过增加题目里业务需求的数量和复杂度来增加难度，强行增加区分度。

## 期末机考

期末机考有三道题。两道算法 + 模拟，一道面向对象。前两道题规模不大，和 CPL 差不多。但是最后一道题给恶心坏了。与平时机考类似 —— Java 味大的业务题。提供了一个模板代码（模板中五六个类塞一个文件，有够逆天的），需要自己加函数和代码。题面是无尽的业务需求 + Java 式 OO。样例及其稀少并且对调试毫无作用，得高分的唯一办法就是祈祷自己有足够好的运气能够一遍写对。出题和验题助教真的写过现代 C++ 吗？这种题 Bjarne 和 Linus 来都得红温。总之，期末机考完完全全地暴露了这门课的本质：一门 C++ 课，教的却是 Java 的 OO，附带一些需要死记而不是从哲学角度去理解的 C++ 特性。 

## 期末笔试

期末笔试印象是一整面的简答题(概念 + 特性)，背面有代码阅读和编码题。大部分题出得没什么槽点，只是一部分题的情景比较刁钻，平时编码基本不会遇到。

## 攻略

对于平时作业，不要拖到 DDL 前再做就行。而且 AI 基本也能写个七七八八的，但是可能需要注意查重。不过还是建议自己写吧，毕竟这是实打实的编码能力。

对于机考，平时作业只要是自己做的基本问题不大。遇到了一些恶心的点也不要太过纠结，这课就这样，问题不在你身上。尽人事知天命。

对于期末笔试，由于神人 PPT 拥有防自学机制，建议上课听讲 + 寻找学长复习笔记。笔记的覆盖面以 PPT 为准，尽量保证 PPT 上鸡飞狗跳的文字和代码都能理解。

对于真正希望认真学现代 C++ 的(对本课意义不是很大)，可以读：

- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)

- [Effective Modern C++](https://cntransgroup.github.io/EffectiveModernCppChinese/)

- [More C++ Idioms](https://en.wikibooks.org/wiki/More_C%2B%2B_Idioms)

不要把这门课的分数放在心上，真正学到了什么知识，领悟了什么哲学才是语言学习中最重要的事情。但问本心无愧处，何忧天命不归真。祝你好运。

## Change Log

