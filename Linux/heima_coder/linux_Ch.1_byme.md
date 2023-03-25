视频地址：[黑马程序员Linux2023](https://www.bilibili.com/video/BV1n84y1i7td/?spm_id_from=333.999.0.0&vd_source=f111e229e8ddffc692d57d989194e313)

# Linux 第一章（黑马程序员）

---

## 00 Linux导学

### why Linux？

个人桌面操作系统

- Windows
- MacOS

服务器操作系统

- Linux👉没有牛的过linux的



无论开发什么，最终都需要运行在Linux操作系统之上

<img src="https://raw.githubusercontent.com/ajuicefans/mylearning/main/Linux/heima_coder/images/1.png" alt="1" style="zoom:67%;" />



### 课程设计

![2](https://raw.githubusercontent.com/ajuicefans/mylearning/main/Linux/heima_coder/images/2.png)



### 如何学习Linux？

实操性强，Linux没有高深的理论知识，纯操作👉**==敲！==**就够了

---



## 01 操作系统概述

学习目标：

1. 了解操作系统的作用
2. 了解常见的操作系统



### 硬件和软件

硬件（看得见摸得到的）：计算机系统中由电子，机械和光电元件等组成的各种物理装置的总称

软件：是用户和计算机硬件之间的接口和桥梁，用户通过软件与计算机进行交流

> 而操作系统，就是软件的一类



一个完整的计算机：由硬件和OS组合而来



### 操作系统

操作系统是计算机软件的一种，它主要负责：作为**==用户和计算机硬件之间的桥梁==**，**==调度和管理计算机硬件进行工作==**

而计算机，如果没有操作系统，就是一堆无法使用的塑料而已。

---

计算机有了OS，就有了灵魂，OS可以：

- 调度CPU
- 调度内存
- 调度硬盘进行数据存储
- 调度网卡进行网络通讯
- 调度音响发出声音
- 调度打印机打印内容
- ......

![3](https://raw.githubusercontent.com/ajuicefans/mylearning/main/Linux/heima_coder/images/3.png)



### 常见的操作系统

PC端

- Windows
- Linux
- macOS

移动端：

- andriodOS
- iOS
- HarmonyOS



### 总结：

1. 计算机由哪两个主要部分组成？
2. OS是什么？有什么作用？👉软件的一类，**协助用户调度硬件工作**，充当用户和计算机硬件之间的桥梁
3. 常见的OS有哪些？

---



## 02 初识Linux

### Linux的诞生

<img src="images/4.png" alt="4" style="zoom:67%;" />



### Linux内核

内核不是给我们“普通人”使用的~

<img src="images/5.png" alt="5" style="zoom:67%;" />

---

### 下载内核源码

<img src="images/6.png" alt="6" style="zoom:67%;" />

### Linux发行版

<img src="images/7.png" alt="7" style="zoom:67%;" />

<img src="images/8.png" alt="8" style="zoom:67%;" />

### 总结：

1. Linux的诞生

   Linux由**林纳斯 托瓦兹**在**1991**年创立并发展至今成为服务器操作系统领域的核心系统

2. 什么是Linux系统的内核？

   内核提供了Linux系统的主要功能，如**==硬件调度管理的能力==**。Linux内核是免费开源的，任何人都可以查看内核的源代码，甚至是贡献源代码

3. 什么是Linux系统发行版？

   **内核无法被用户直接使用**，需要**配合应用程序**才能被用户使用。**在内核之上，封装**系统级应用程序，组合在一起就称之为**Linux发行版**

---



## 03 虚拟机介绍

学习Linux系统，就需要有一个可用的Linux系统。

如何获得？将自己的电脑重装系统为Linux？

NoNo。这不现实，因为Linux系统并不适合日常办公使用。

我们需要借助 **虚拟机** 来获得可用的Linux系统环境进行学习



### 什么是虚拟机？

借助**==虚拟化技术==**，我们可以在系统中，**==通过软件：模拟计算机硬件，并给虚拟硬件安装真实的操作系统==**。这样，就可以在电脑中，虚拟出一个完整的电脑，以供我们学习Linux系统

<img src="F:\lifeProject\Mylearning\Linux\heima_coder\images\9.png" alt="9" style="zoom:50%;" />



### 总结：

1. 什么是虚拟机？

   通过**虚拟化技术**，在电脑内，**虚拟出计算机硬件，并给虚拟的硬件安装操作系统**，即可得到一台虚拟的电脑，称之为虚拟机

2. 为什么要使用虚拟机？

   学习Linux系统，**需要有Linux系统环境**。我们不能给自己电脑重装系统为Linux，所以通过虚拟机的形式，得到可以用的Linux系统环境，**供后续学习使用**。

---



## 04 安装VMware Workstation虚拟化软件