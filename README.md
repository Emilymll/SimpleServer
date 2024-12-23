# SimpleServer

简易的、小型的服务器。

## 简介

源于湖南省大学生物联网应用创新设计竞赛（技能赛）服务器部分。

开发一个物联网服务器，充当中转中心的角色。前端与硬件之间相互不能直接通信，所有的数据处理和控制交互都需要经过服务器。

可用于测试、学习，或搭建小型 web 系统的后台。

提供了 Python 和 Java 两个版本。Python 版基于 Flask 框架，Java 版基于 SpringBoot 框架（暂未上传）。

## 快速上手

前端 - 服务器的通信由 RESTful API + WebSocket 实现。

硬件 - 服务器的通信由 TCP 实现。

采用 JSON 格式传递数据。

框架已搭好，数据库部分、API 接口部分、TCP 服务器部分根据应用场景修改相应的代码即可。

当然也可以砍掉 TCP 服务器部分，只保留 web 后台。