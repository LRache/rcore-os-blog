---
title: 2024A-rCore-Blog-Aoi979
date: 2024-11-10 02:36:55
tags:
    - author: Aoi979
    - repo: https://github.com/LearningOS/2024a-rcore-Aoi979 
    - rust
---





## 第一阶段总结

对Rust这门编程语言早有耳闻，在活动开始之前就学过一遍rust,不过因为用的不多也没有很熟练，第一阶段的Rust练习巩固了基础，我平时是写C/C++的，真正写起来的时候非常强烈的感受到Rust 的设计与C++之间的差异，Rust对安全的要求非常严格，还有就是这个编译器很强大，虽然过不了编译挺烦人的，但编译器又能教你改正错误，也算是Rust的一个魅力了

## 第二阶段总结

- ch1~3

  在学习汇编语言的过程中，我深刻体会到了“切换上下文”的概念。通过阅读trap.s和switch.s的代码，我不仅学到了编程技巧，还对操作系统和计算机的深层次工作原理有了更为深刻的理解。

- ch4

  地址空间的章节对我而言是一大挑战。尽管在理论学习中已经有所接触，但真正深入到代码层面时，我仍然感到些许迷茫。理解MapArea和MemorySet的过程颇费周折，最初我错误地将rCore视为单页表系统，导致对许多操作感到困惑。经过反复推敲和深入学习，我终于克服了这一障碍，这一部分的学习经历让我受益匪浅。

- ch5 & ch8

  与第四章相比，第五章和第八章的编程题目难度有所降低。这两章引入了进程的概念，并为后续的并发章节做了良好的铺垫。我开始对之前觉得理所当然存在的进程和线程有了更深刻的理解。在Linux系统中，进程和线程只是共享程度不同的任务。相较于理论书籍，代码的直观性让我对这些概念有了更加清晰的认识。第八章中，我花费了一些时间来理解银行家算法，一旦掌握，编程题目便迎刃而解。

- ch6

  这一章对我来说是整个学习阶段中难度最大的。在理论学习时，我对文件系统章节的理解不够深入，面对文档中逐步引入的抽象概念，我感到十分困惑。在反复阅读文档和代码后，我终于在微信训练营群友的帮助下完成了作业。我希望rCore在未来的讲解中能够更加细致地涵盖这一部分。

- ch7

  很轻量的章节，为系统引入了管道，实现了进程间的通信，因为没有编程作业，就没上面的章节反复翻阅文档式的去理解各个细节

  ## 感悟

  回顾这一阶段的学习，我感到非常充实。尽管在第六章的学习过程中遇到了不小的挑战，但这段经历对我的成长无疑是宝贵的。无论我能否在接下来的学习中继续坚持，这一阶段所学到的知识和技能都将对我产生长远的影响。
