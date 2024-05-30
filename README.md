# TOE Control 🚀

_注：本仓库用于项目文档存放和导航，详细内容请移步下方仓库导览_

## 💡 项目简介

这是一个软件框架上基于ros2_control、通讯链路上基于ethercat的通用机器人框架，依托此平台可以高效部署低延时无下位机感知控制系统，以下是此平台的特点和优势：
* 高度模块化：电机通讯和整机控制、感知解耦，方便成员分工。
* 高实时性：ethercat在通讯实时性上远超串口，同时使用ros2_control支持执行器/传感器的进程间通讯，配合内核realtime补丁实现高实时性。
* 电机&传感器抽象层：不同类型执行器通过yaml文件配置即可实现一键接入，抽象成同类型接口，减少重复造轮子。
* ros2生态支持：轻松实现rqt和rviz2的可视化调参，不改变控制程序接口的情况下轻松实现sim2real。




## 目录 📚

- [安装](#安装)
- [依赖](#使用方法)
- [示例](#示例)
- [TODO](#TODO)
- [贡献](#贡献)
- [许可证](#许可证)
- [联系](#联系)

## TODO 🔍

## 依赖 🛠️

## 安装 💻

## 贡献 🤝
欢迎任何形式的贡献！

## 许可证
该项目基于 MIT 许可证 - 详情参见 [LICENSE](LICENSE) 文件。

## 联系 📬
如有任何问题或建议，欢迎联系项目维护者：

* 维护者：EvenceWu
* 邮箱：evencewu@outlook.com