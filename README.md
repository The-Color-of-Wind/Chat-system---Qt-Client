# 实时聊天系统————客户端
## 项目介绍（客户端）：
基于 Linux 的高性能聊天服务器与 Qt 客户端的跨网段通信系统，采用 TCP 作为通信协议，支持**用户注册、登录、好友管理 和 实时消息收发**。服务端基于 Linux 开发，使用 **epoll + 线程池** 进行高并发连接管理，客户端采用 Qt 实现跨平台 GUI。（本篇只包含客户端）

- 利用 **多态思想** 设计不同的界面模块，所有界面继承自统一基类，便于扩展和维护。
- 利用 **Qt 信号与槽机制** 实现模块间的解耦，确保界面与逻辑的独立性。
- 利用 **Qt 信号与槽机制** 实现模块间的解耦，确保界面与逻辑的独立性
- 利用 **Qt布局管理器和UI**，设计符合用户习惯的界面，确保交互流畅，提升用户体验

## 关于本客户端
- 本客户端是自学 Qt 过程中的实践产物，主要用于与服务器交互，验证服务器端的开发效果。因此，界面美化较差，且可能存在部分 bug。
- 分享本项目的目的是希望能提供一个较为完整的项目框架和实现思路，供自学 Qt 的同学参考。（请大家不要嫌弃）
- 因为这是我的第一个 Qt 项目，代码框架可能较为凌乱。如果后续有时间和精力，我将规范代码，并持续维护。

### **对本项目支持跨网段传输，我对其进行了打包并上传了安装包，欢迎大家安装尝试，也欢迎反馈问题和建议！（但目前bug较多...）**

## 目录
1. [Demo演示](#Demo演示)
2. [界面概述](#界面概述)
3. [框架](#框架)
4. [安装包](#安装包)
5. [更新日志](#更新日志)
6. [致谢](#致谢)


## Demo演示
这里是简介部分...

## 界面概述
[启动界面](ClassDescription/action.md)

[登录界面](ClassDescription/loginwidget.md)

[注册界面](ClassDescription/registerwidget.md)

[主界面](ClassDescription/mainwidget.md)

[聊天界面](ClassDescription/chatwidget.md)

[好友界面](ClassDescription/friendwidget.md)


## 类概述
[用户类](ClassDescription/user.md)

[好友类](ClassDescription/userfriend.md)

[聊天框类](ClassDescription/userchat.md)

[信息类](ClassDescription/message.md)


## 框架
![17cbcaa469b8cabf301f1f46c5eec79](https://github.com/user-attachments/assets/79878936-25bb-45c1-9fb8-c0420581f572)
![67482f768071677e8eb44c841035083](https://github.com/user-attachments/assets/f8f68a2b-4542-4edd-9f86-b1178da9703d)



## 安装包
这里是使用部分...

## 更新日志

## 致谢
