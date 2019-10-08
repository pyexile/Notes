## 操作系统

### 1. 操作系统的概述

#### 1.1 操作系统的基本概念

- 操作系统定义及作用

  - 定义

    能有效的组织和管理系统中的各种软、硬件资源，合理的组织计算机系统工作流程，控制程序的执行，并向用户提供一个良好的工作环境和友好的接口

  - 作用

    1. 通过资源管理提高计算机系统的效率
    2. 改善人机界面向用户提供友好的工作环境

- 操作系统特征与功能

  - 4个特征

    并发性、共享性、虚拟性、不确定性

  - 功能

    操作系统的功能可分为进程管理、文件管理、存储管理、设备管理、作业管理

#### 1.2 操作系统分类及特点

- 批处理操作系统

  分为单道批处理和多道批处理。

  单道批处理指一次只有一个作业装入内存执行。

  多道批处理允许多个作业装入内存执行。多道批处理系统特点：多道、宏观上并行运行、微观上串行运行。

- 分时操作系统

  一个计算机系统与多个终端设备连接。特点：多路性、独立性、交互性、及时性。

- 实时操作系统

  分为实时控制系统（武器控制、飞机自动驾驶等）和实时信息处理系统（飞机订票系统、情报检索等）。

  实时系统与分时系统的区别：

  - 系统的设计目标不同
  - 交互性的强弱不同
  - 响应时间的敏感度不同

- 网络操作系统

  - 网络操作系统的功能

    主要包括高效、可靠的网络通信；对网络中共享资源的有效管理；提供电子邮件、文件传输、共享硬盘和打印机等服务；网络安全管理；提供互操作能力。

  - 网络操作系统分类
    1. 集中模式。系统基本单元由一台主机和若干与主机相连的终端构成，信息的处理和控制是集中的。UNIX就是这类操作系统的典型例子
    2. 客户端/服务器模式。这种模式网络可分为服务器和客户端。
    3. 对等模式（peer-to-peer）。在采用这种模式的操作系统网络中，各个站点是对等的。它既可以作为客户端区访问其它站点，也可以作为服务器向其它站点提供服务。可见该模式具有分布处理和分布控制的特征。

- 分布式操作系统
  
  由多个分散的计算机经连接而成的计算机系统，系统中的计算机无主、次之分，任一两台计算机可以通过通信交换信息。
  
- 微型计算机操作系统

  常见的有Windows、Mac OS、Linux。

- 嵌入式操作系统

  运行在嵌入式智能芯片环境中，对整个智能芯片以及它所操作、控制的各种部件装置等资源进行同意协调、处理、指挥和控制

  特点：微型化、可定制、实时性、可靠性、易移植性。