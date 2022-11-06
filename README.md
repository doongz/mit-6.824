# MIT-6.824 Distributed Systems

Basic Sources for MIT 6.824 Distributed Systems Class

## Introduction

- 所属大学：Harvard
- 授课老师：Robert Morris
- 编程语言：Golang
- 课程难度：🌟🌟🌟🌟🌟
- 预计学时：Two months
- 学年：2020

一直在断断续续的学习mit 6.824 分布式系统这门课程。分布式系统是现在计算机软件系统中不可避免的一种架构，了解分布式系统对于构建任何大型分布式应用，对于理解分布式程序的运行，对于优化分布式程序的运行环境都有一定的帮助。

mit6.824 这门课程可以说是明星课程了，主讲老师是Robert Morris，这个看起来平易近人的小老头，是个传奇人物。能够听这样的传奇人物叨叨十几个小时，本身就是一种享受，更何况Robert教授能够一种理论联系实际的方式，将主流的分布式系统软件讲的浅显易懂。

这门课程总共有20节课，4个实验，实验都是基于golang完成，课程配套了实验相关的测试用例，动手完成实验可以加深对于相关知识的理解。

## Resources

- 课程链接：[https://pdos.csail.mit.edu/6.824/](https://pdos.csail.mit.edu/6.824/)
- 课表：[https://pdos.csail.mit.edu/6.824/schedule.html](https://pdos.csail.mit.edu/6.824/schedule.html)
- 视频 6.824 / 2020：[https://www.bilibili.com/video/BV1R7411t71W?p=1](https://www.bilibili.com/video/BV1R7411t71W?p=1)
- 视频 6.824 / Spring 2021：[https://www.bilibili.com/video/BV16f4y1z7kn?p=16](https://www.bilibili.com/video/BV16f4y1z7kn?p=16)
- 课程翻译 2020：[https://mit-public-courses-cn-translatio.gitbook.io/mit6-824/](https://mit-public-courses-cn-translatio.gitbook.io/mit6-824/)
- 中文学习资料+2021版本代码：[https://github.com/chaozh/MIT-6.824](https://github.com/chaozh/MIT-6.824)
- 2021版本实验记录：[https://github.com/OneSizeFitsQuorum/MIT6.824-2021](https://github.com/OneSizeFitsQuorum/MIT6.824-2021)

## Labs

lab 代码为 2021 版本

- [x] Lab 1: MapReduce [手册](./docs/lab1-手册.md) [实现](./docs/lab1-实现.md)
- [x] Lab 2: Raft [手册](./docs/lab2-手册.md) [实现](./docs/lab2-实现.md)
- [x] Lab 3: Fault-tolerant Key/Value Service [手册](./docs/lab3-手册.md) [实现](./docs/lab3-实现.md)
- [x] Lab 4: Sharded Key/Value Service [手册](./docs/lab4-手册.md) [实现](./docs/lab4-实现.md)

## 讲座

- [Lec1: 入门介绍(以MapReduce为例)](https://github.com/chaozh/MIT-6.824/issues/2)
- [Lec2: RPC与线程机制(Go语言实战)](https://github.com/chaozh/MIT-6.824/issues/3)
- [Lec3: GFS](https://github.com/chaozh/MIT-6.824/issues/6)
- [Lec4：主从备份](https://github.com/chaozh/MIT-6.824/issues/7)
- [Lec 5：Raft基本](https://github.com/chaozh/MIT-6.824/issues/9)
- [Lec6：Raft实现](https://github.com/chaozh/MIT-6.824/issues/10)

## 问题

记录在issues中

- 课前问题：[对分布式系统课程有啥想说的？](https://github.com/chaozh/MIT-6.824/issues/1)
- [Lab0 完成Crawler与KV的Go语言实验](https://github.com/chaozh/MIT-6.824/issues/4)
- Lab1 MapReduce实验
- [Lec3 请描述客户端从GFS读数据的大致流程？](https://github.com/chaozh/MIT-6.824/issues/6)
- [Lec4 论文中VM FT如何处理网络分区问题？](https://github.com/chaozh/MIT-6.824/issues/7)
- [Lec5 Raft什么机制会阻止他们当选？](https://github.com/chaozh/MIT-6.824/issues/9)
- [Lec6 Figure13中第8步能否导致状态机重置，即接收InstallSnapshot RPC消息能否导致状态回退](https://github.com/chaozh/MIT-6.824/issues/10)

## 参考资料 Related

- [MapReduce(2004)](https://pdos.csail.mit.edu/6.824/papers/mapreduce.pdf)
- [GFS(2003)](https://static.googleusercontent.com/media/research.google.com/zh-CN//archive/gfs-sosp2003.pdf)
- [Fault-Tolerant Virtual Machines(2010)](https://pdos.csail.mit.edu/6.824/papers/vm-ft.pdf)
- [Raft Extended(2014)](https://pdos.csail.mit.edu/6.824/papers/raft-extended.pdf)
