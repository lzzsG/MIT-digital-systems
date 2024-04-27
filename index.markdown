---
layout: post
title: Home
nav_order: 0
description: "在这个系列中，我们将共同学习三门课程（MIT 6.004, MIT 6.175, MIT 6.375）。大部分的内容都是基于 ChatGPT 对相关资源的翻译和解释，以及本站作者的审核调整和补充，希望能帮助大家更好地理解这些复杂的概念。"
permalink: /
---


# 开始 - 介绍与资源

---

在这个系列中，我们将共同学习三门课程（MIT 6.004, MIT 6.175, MIT 6.375）。大部分的内容都是基于 ChatGPT 对相关资源的翻译和解释，以及本站作者的审核调整和补充，希望能帮助大家更好地理解这些复杂的概念。

MIT的这三门课程涵盖了计算机科学和电子工程的一些高级主题。下面是每门课程的详细介绍：

### MIT 6.004：计算系统结构（Computation Structures）

MIT 6.004 主要教授计算机系统的基本构造块。学生将学习有关硬件和软件接口的知识，包括处理器设计、存储器层次结构和异步序列器。此课程涉及如何从低级硬件构建出能够运行软件应用的系统。此外，学生也会学到如何使用模拟工具和硬件描述语言来设计和测试这些系统。

### MIT 6.175：构造可靠的数字系统（Constructive Computer Architecture）

MIT 6.175 课程着重于数字系统的构造，特别是在处理器设计领域。学生会学习到如何设计、构建和测试处理器和微处理器。课程内容包括数字逻辑、微架构、流水线和优化以及测试和验证技术。此外，该课程还会使用现代的硬件描述语言和验证工具，教授如何构建高性能且可靠的计算机硬件。

### MIT 6.375：设计和实施数字系统（Design and Implementation of Digital Systems）

MIT 6.375 专注于数字系统的设计和实施，尤其是通过使用现场可编程门阵列（FPGA）。课程内容涵盖了从理论到实践的所有方面，包括硬件描述语言、系统设计、性能分析和优化以及FPGA的特定技术。此课程特别适合对硬件设计感兴趣的学生，并且强调实际操作和实验。

这些课程都非常适合对计算机硬件和系统设计感兴趣的学生，尤其是那些希望在未来从事硬件工程或系统架构设计的学生。每门课程都有丰富的实验和项目，帮助学生将理论知识转化为实践能力。

随着课程内容的深入，我们将探讨更多高级主题，包括但不限于集成电路的设计、优化和测试。无论你是计算机科学的新手还是经验丰富的工程师，这个系列都将是一个宝贵的资源，帮助你在计算机科学和工程领域取得进步。

在追求深入了解的过程中，我们还强调提高个人的动手实践能力。为了做到这一点，我们鼓励学生自行搜集和利用开源资料，掌握实际操作和实验。我们坚信通过亲自动手实践和主动搜寻资料，学生能够更好地巩固理论知识，并在计算机科学领域和开源社区取得更大的进步。

敬请期待后续的更新，我们将继续深入这些激动人心的课程，解锁计算机科学的更多秘密！

---

# 告知

感谢您访问和使用本资源。这里分享的是我个人的学习记录，包括我在学习过程中遇到的问题及我所采用的解答方式。这些内容是参考费曼学习法的模式，通过记录和文档化我的学习过程形成的笔记和教程。请注意，这些材料是为了辅助理解和掌握知识点，它们并非官方认可的答案或教学资源，并且可能包含错误。鼓励您在使用这些资源时保持批判性思维，自行解决问题并形成独立的见解。如果您正在进行相关课程学习，请尽量先独立完成作业或任务。使用本资源默认不会破坏您的独立学习过程。同时，为尊重教育者的意愿并减少潜在冲突，请避免在相关课程社区或团体中传播这些内容。

<br/>

> <span style="color: red;">注意！</span>ChatGPT 可能会出错，考虑检查重要信息，尤其是数学逻辑相关内容 ChatGPT 会产生大量幻觉，本站作者已经尽力审核调整和补充。不过同样，本站作者的调整和补充可能并不准确。具体内容以课程表述为准，本站只做参考理解使用。如果发现任何问题，请在 GitHub 反馈。

---

# MIT公开课内容介绍

下面内容来自[计算机体系结构 l MIT课程学习新手上路宣讲 - 达坦科技 米明恒](https://www.bilibili.com/video/BV1u8411i7Qw/?vd_source=be5a8ad6859e70853a7cfb16c669115d)

我们选择了MIT的3门公开课程作为学习资料：

- **MIT 6.004**
  - 本科课程水平，优点是配有视频教材，适合初次接触。通过这些视频，学生可以系统地理解和掌握相关知识。
- **MIT 6.175**
  - 硕士课程水平，优点是拥有详细的课件和实验资料，有非常完善的Lab和Project。我们主要以此为基础，也会参考并建议学习MIT 6.004的视频内容，以弥补6.004的实验缺陷。
- **MIT 6.375**
  - 精讲精练的选修课，课程时间比较短，强调了编程语言Bluespec SV（Bluespec System Verilog, BSV）语言的使用，课程提供了4+1 Lab。由于这门课程的内容与6.175有重合，我们建议在完成6.175的学习后再学习。

---

- **Bluespec介绍与特点：**
  - Bluespec是一门现代的硬件描述语言，由MIT的Arvind教授主导开发。易于使用且强调安全性，但其社区和生态较小，资源和用户较少。

- **三门公开课中Bluespec的作用和位置：**
  - Bluespec与Chisel, SpinalHDL等HDL一样，都是用于硬件开发的现代工具，优于传统的Verilog设计方式。Bluespec提供了更抽象的语言特性，有助于提高开发效率，但需要时间学习并掌握。

- **6.004课程内容简介：**
  - 6.004包含了一系列的视频讲座，覆盖了RISC-V处理器及其汇编语言，编译技术和操作系统等核心计算机科学领域知识，并结合实验（如硬件机构原理）进行讲解。提供了一个视频选集链接（[Bilibili 6.004课程视频](https://www.bilibili.com/video/BV197411s736)），方便直接访问。

---

# 6.004

6.004课程内容涵盖从计算机系统的基础概念、组合逻辑电路、到寄存器文件和存储系统的设计等。它强调理解和掌握基础知识，并通过实验学习BlueSpec语言进行硬件设计，使学生能够在实践中找到理论与实用之间的平衡。（[Bilibili 6.004课程视频](https://www.bilibili.com/video/BV197411s736)）

#### 第1部分：L01 - L04

- **L01 - 引言 (Introduction)**
- **L02 - RISC-V 汇编 (RISC-V Assembly)**
- **L03 - 编译代码、过程及栈 (Compiling Code, Procedures, and Stacks)**
- **L04 - 过程和存储映射I/O (Procedures and MMIO)**

一些概述性质的课程，分别介绍了RISC-V处理器及其汇编语言、软件的编译过程、函数调用栈之类的基础知识，相当于在复习国内《计算机组成原理》这门课程。

#### 第2部分：L05 - L10

- **L05 - 组合逻辑 (Combinational Logic)**
- **L06 - Barrel Shifter 和 Boolean 优化 (Barrel Shifter, Boolean Optimizations, and Logic Synthesis)**
- **L07 - 在Bluespec中的复杂组合电路 (Complex Combinational Circuits in Bluespec)**
- **L08 - 算术电路设计权衡 (Design Tradeoffs in Arithmetic Circuits)**
- **L09 - 时序电路 (Sequential Circuits)**
- **L10 - 时序电路：带有保护接口的模块 (Sequential Circuits, Modules with Guarded Interfaces)**

相当于在带领大家复习《数字电路》课程相关知识，在这里会开始穿插着介绍Bluespec的一些基础语法知识。在这里可以学会BSV中如何描述组合逻辑、时序逻辑，以及电路设计中的一些trade-off。

#### 第3部分：L11 - L12

- **L11 - 在Bluespec中的硬件综合 (Hardware Synthesis in Bluespec)**
- **L12 - 模块接口与并发性 (Module Interfaces and Concurrency)**

重点！这里将涉及到两个重要知识点：

- BSV程序的各个模块之间是怎样握手的(不同于Verilog需要开发者自己去处理模块间的握手，BSV将模块间的握手抽象成了和软件函数调用一样简单的写法，这意味着BSV编译器会在背后做很多工作，你需要了解BSV编译器自动生成了什么样的握手信号)

- BSV中Conflict Matrix的概念，理解了这个概念，你才能知道BSV是如何并行调度执行你所写的代码的。

#### 第4部分：L13 - L23

- **L13 - 在硬件中实现RISC-V处理器 (Implementing RISC-V Processor in Hardware)**
- **L14 - 多周期处理器 (Multicycle Processors)**
- **L15 - 存储层次结构 (The Memory Hierarchy)**
- **L16 - 存储系统设计与实现 (Memory Systems: Design and Implementation)**
- **L17 - 操作系统 (Operating Systems)**
- **L18 - 虚拟内存 (Virtual Memory)**
- **L19 - 流水线引言 (Introduction to Pipelining)**
- **L20 - 处理器流水线 (Processor Pipelining)**
- **L21 - 实现流水线 (Implementing Pipelines)**
- **L22 - 同步 (Synchronization)**
- **L23 - 实现处理器流水线 (Implementing Processor Pipelines)**

这一部分开始教大家如何用BSV编写RISC-V处理器，从最初的单周期一直到多级流水线。其中会继续穿插着介绍BSV语言本身的特性，以及存储器、操作系统、虚拟内存等相关的知识。

#### 第5部分：L24 - L25

- **L24 - 数字抽象和时序约束 (The Digital Abstraction and Sequential Timing Constraints)**
- **L25 - 缓存一致性 (Cache Coherence)**

介绍了时序约束和缓存一致性相关的内容

---

# 6.175

**6.175课程内容简介** ( [http://csg.csail.mit.edu/6.175/index.html](http://csg.csail.mit.edu/6.175/index.html) )

由于6.175没有视频课程，但是它的课件非常完善，除了课件以外还有Textbook，因此6.175非常适合配合着6.004的视频一起同步学习。

6.175的实验也建议配合着6.004的视频同步开展。

相比于6.004，6.175的课程在Conflict Matrix、处理器流水线、缓存一致性的介绍上会更加深入。

6.175的课件有PPT和PDF两个版本，PPT版本有动画效果，强烈建议看PPT版本。

在实验上，由于6.175的课程开设了很多年，前些年采用的是MIPS处理器来讲的，最近换成了RISC-V处理器，所以有些资料可能是MIPS的，但是不影响大家学习。不过做实验的时候要找好代码框架，不要做成MIPS版本的实验。

---

**6.175的实验室内容由3个大部分：**

- **Lab0~Lab4**，熟悉Bluespec语言和处理器基础知识，其中：
  - **Lab0~Lab3**：主要是熟悉Bluespec的语法，如何编写仿真和验证、时序验证、流水线设计等。
  - **Lab4** 在重点训练 Conflict Matrix，很重要，一定要认真做明白。

- **Lab5~Lab8**，RISC-V处理器实验，通过过一步步的迭代，达到性能优化和增加新的功能。

- **Project1~Project2**，涉及到多核处理器以及多核之间的缓存一致性。

注意，6.175课程网站具有不同年份的存档，目前主页默认是2017年的课程安排，但在实验方面，2017年的实验难度低于2016年的实验(主要体现在Project部分)，因此建议大家在做实验的时候，选择2016年的课程网站进行学习。另外，不同年份的PPT、助教答疑PPT等内容也有一些区别，有精力的同学可以把两年的都看一下。

---

# 6.375

6.375课程内容简介 ( [http://csg.csail.mit.edu/6.375/6_375_2019_www/index.html](http://csg.csail.mit.edu/6.375/6_375_2019_www/index.html) )

- 6.375 实验指导书写的很长，会在实验指导书里教给大家关于BSV的一些高级用法。相比课件更推荐实验指导书。
- 6.375 也有一份Textbook，这个Textbook是6.175的Textbook的前半部分的高消重制版，对于数电基础知识，以及Bluespec的Confict Matrix、调度算法等有更详细的介绍。如果6.175的Textbook还没有满足你的好奇心，或者感觉6.175的Textbook讲的不清楚，那么可以试试阅读6.375的Textbook，但是6.375的Textbook没有涉及到处理器相关的部分。
- 6.375 的实验内容侧重于信号处理以及BSV的高级语法，同时也涉及到软硬件联合开发调试的一些内容。
- 6.375 的课件还讲了很多BSV的其他应用案例，但是6.375的实验却没有涉及到这些部分。所以6.375的课件大家有选择的看就行了，有精力的可以把所有课件都看了。理论上看为6.004和6.175之后，6.375的课件应该看起来比较简单了。

---

### 实验的学习顺序

- **6.175 Lab0~Lab4**
  - 熟悉BSV基础语法，Conflict Matrix
- **6.375 Lab1~Lab4**
  - 强化BSV语法，熟悉软硬件联合调试框架Connectal，为后续处理器实验做准备
- **6.175 Lab5~Lab8**
  - 编写RISC-V处理器
- **6.175 Proj1~Proj2**
  - 实现Store Queue和多核缓存一致性
- **6.375 Lab5（选做）**
  - 前置6.175的Project以后，这个实验相对较为简单

---

### 推荐的学习顺序

- MIT6.004  **L01 - L04**

​ 基础知识，不对应具体的Lab，但是对做Lab有帮助，帮助大家了解软件和硬件的交互边界

- MIT6.004  **L04 - L08**

​ 对应6.175 Lab0-Lab3

- MIT6.004  **L08 - L12**

​ 对应6.175 Lab3-Lab4，以及6.375的Lab1-Lab4

- MIT6.004  **L13 - L24**

​ 对应6.175 Lab5-Lab8

- MIT6.004  **L22 - L25**

​ 对应6.175 Project 1-2

---

# 学习资料

### [Bilibili 6.004课程视频](https://www.bilibili.com/video/BV197411s736)

- [PPT](https://pan.baidu.com/s/1WnCeNkclf3k1A894D1IwgA?pwd=r452)

### [6.175 课程官网](http://csg.csail.mit.edu/6.175/index.html)

- Schedule
  - 课件
- Resources
  - 切换2016版本
  - Textbook
- Labs
  - 实验指导书

### [6.375 课程官网](http://csg.csail.mit.edu/6.375/6_375_2019_www/index.html)

- [Resources](http://csg.csail.mit.edu/6.375/6_375_2019_www/resources.html)
  - Textbook

- [Handouts](http://csg.csail.mit.edu/6.375/6_375_2019_www/handouts.html)
  - 课件
  - 实验指导书
  - 实验环境代码

### 另

- [BSV资源](https://github.com/B-Lang-org/bsc/releases)
  - 标准库文档
  - BSV编译器说明
  - Bluespec文档
- 6.175实验环境在GitHub早年仓库寻找

---

# 实验环境搭建

### BSV工具链

实验环境的代码问题解决了以后，下一步是实验环境工具链的搭建，这里同样不直接给出具体的操作指南，仅给出一些可选的方案，具体选择哪一种，都有各自对应的坑需要大家自己去踩。毕竟搭建环境也是能力考察的
一部分。

**方案1:纯手工搭建**

- BSV的编译器可以到GitHub上BSV的官网release页面直接下载，WangXuan同学的中文教程里有步骤，不是很难
- **6.375的Lab4和6.175的后几个Lab**会用到一个叫Connectal的开发框架，这个框架安装比较折腾人

**方案2:使用Docker开发环境**

- 可以搜索connectal-docker这个开源镜像，是我们之前的一位实习同学自己搭建的，集成了BSV编译器和Connectal
- 需要大家对docker比较熟悉

**Connecta是什么?**

Connectal是剑桥开发的一个软硬件联合调试的框架，可以方便的在FPGA和PC之间打通一个数据交换的通道。在近几年RISC-V相关的Lab中，使用Connectal搭建了测试框架用于监测自己编写的RISC-V处理器的工作状态。

### RISC-V工具链

下面是RISC-V工具链相关的东西，**Lab5~Lab8**及**Project 1~2**需要用到。

因为后面要自己编写RISC-V处理器，并且在RISC-V处理器上运行测试用的汇编程序和C程序，所以需要自己动手安装RISC-V的编译工具链。

**存在的坑:**

- 实验环境代码用到的编译器版本比较古老，新的RISC-V GCC编译器的一些命令行参数已经发生了改变，需要大家自己去调整。

- GCC编译得到的可执行文件需要通过一定的方式传给仿真器里面跑的RISC-V处理器使用，这里也有不同的工具可以使用，而这些工具可能也存在版本问题，不同版本转换出来的二进制文件格式不一样，需要大家自己修改。

- 关于把可执行文件喂给仿真器这件事，不同年代的实验代码也有不同的实现方式，有的是通过把ELF文件格式转换成BIN或者VMH格式的文件让仿真器读取，有的是通过Connectal作为通道直接使用ELF文件，各有利整，大家可以自行对比不同版本的实验代码。

### 实验对应环境需求

只需要BSV编译器，没必要一开始就配置Connectal和RISC-V工具链

- **6.175 Lab0-4**
- **6.375 Lab1-3**

需要BSV编译器和Connectal

- **6.375 Lab4**
- **6.175 Lab5**

需要BSV编译器、Connectal以及RISC-V工具链

- **6.175 Lab5-8 Proj1-2**

---

## FAQ

- 有一些实验需要用用到FPGA开发板，这部分涉及到上板实验的部分先跳过即可，我们只做软件仿真部分。
- 作为开源项目的参与者，必须自己有很强的Debug能力，要习惯于自己踩坑。所以本次新手入门，有一些坑并没有展示给大家，就是留着让大家去踩的。
- 没有太多中文资料，做开源，与全球的开发者交流，基本的英语读写能力还是需要的。和GitHub或者其他资料网站打不开怎么办--自己修炼魔法，这也是必备技能。
- 6.175的Lab2和Lab3可能网页上的顺序和GitHub找到的代码顺序是颠倒的。如果你遇到了这个情况，那就先做Lab3再做Lab2。正确的顺序就是先加法器，再乘法器，再FFT。
- 6.375的Lab是以信号处理为主题的，但是大家不用关注信号处理算法本身，而是重点关注Bluespec本身的一些高级语法。
- 建议大家在做实验的时候阅读TestBench的代码，而不是只写实验代码，事实上，有一些Debug工作需要你在了解了TestBench是如何工作以后才能找到问题，甚至有的TestBench本身就有问题。
- 关于查看仿真波形这件事，整套实验的指导书里面都没有教大家如何查看波形，我们也不是特别鼓励大家去看波形。看波形并不是一个高效的debug手段，也难以做到自动化评测。我们建议大家更多的了解BSV自带的仿真器bluesim的特性，采用更高效的手段来debug，将更多软件开发中的debug方式应用到硬件开发中。当然，如果你对看波形有执念，bluesim也可以导出vcd格式的波形文件，大家可以自己学习。
- 如果感觉入门还是比较费力，可以考虑先自学一生一芯项目的基础课程，然后再挑战MIT的实验课程。
- 关于何时提交代码:如果只是对BSV感兴趣，想学习BSV语言的同学，大家直接在群里互相交流即可，但是对于有申请达坦实习岗位的同学，BSV的学习是面试流程的一部分，需要在完成6.175的Lab0~Lab2之后主动联系达坦科技的同学对大家的代码进行Review。**(达坦科技实习相关)**
- 如果是申请实习的同学，建议在1~2个月内完成所有实验。
  - [达坦科技DatenLord官网](https://datenlord.github.io/zh-cn/)
  - B站：达坦科技DatenLord
  - [GitHub](https://GitHub.com/datenlord)

---

## 附：MIT 6.004课程内容目录

课程链接：[MIT 6.004公开课程](https://www.bilibili.com/video/BV197411s736)

- **L01 - 引言 (Introduction)**
- **L02 - RISC-V 汇编 (RISC-V Assembly)**
- **L03 - 编译代码、过程及栈 (Compiling Code, Procedures, and Stacks)**
- **L04 - 过程和存储映射I/O (Procedures and MMIO)**

- **L05 - 组合逻辑 (Combinational Logic)**
- **L06 - Barrel Shifter 和 Boolean 优化 (Barrel Shifter, Boolean Optimizations, and Logic Synthesis)**
- **L07 - 在Bluespec中的复杂组合电路 (Complex Combinational Circuits in Bluespec)**
- **L08 - 算术电路设计权衡 (Design Tradeoffs in Arithmetic Circuits)**
- **L09 - 时序电路 (Sequential Circuits)**
- **L10 - 时序电路：带有保护接口的模块 (Sequential Circuits, Modules with Guarded Interfaces)**

- **L11 - 在Bluespec中的硬件综合 (Hardware Synthesis in Bluespec)**
- **L12 - 模块接口与并发性 (Module Interfaces and Concurrency)**

- **L13 - 在硬件中实现RISC-V处理器 (Implementing RISC-V Processor in Hardware)**
- **L14 - 多周期处理器 (Multicycle Processors)**
- **L15 - 存储层次结构 (The Memory Hierarchy)**
- **L16 - 存储系统设计与实现 (Memory Systems: Design and Implementation)**
- **L17 - 操作系统 (Operating Systems)**
- **L18 - 虚拟内存 (Virtual Memory)**
- **L19 - 流水线引言 (Introduction to Pipelining)**
- **L20 - 处理器流水线 (Processor Pipelining)**
- **L21 - 实现流水线 (Implementing Pipelines)**
- **L22 - 同步 (Synchronization)**
- **L23 - 实现处理器流水线 (Implementing Processor Pipelines)**

- **L24 - 数字抽象和时序约束 (The Digital Abstraction and Sequential Timing Constraints)**
- **L25 - 缓存一致性 (Cache Coherence)**
