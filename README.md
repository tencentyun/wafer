Wafer - 企业级微信小程序全栈方案
==============================

Wafer 是腾讯云面向广大开发者提供的小程序开发全栈资源套件，套件提供小程序会话管理服务 WebSocket 信道服务，在扩展性和安全性上能满足企业级的要求，同时具备低开发门槛。

阅读 [Wiki](https://github.com/tencentyun/wafer/wiki) 文档了解 Wafer 的部署方法、架构设计以及实现细节。

## 开发者资源

* 业务服务器
  - [PHP SDK](https://github.com/tencentyun/wafer-php-server-sdk) - PHP 解决方案的 SDK 源码及 Demo
  - [C# SDK](https://github.com/tencentyun/wafer-csharp-server-sdk) - C# 解决方案的 SDK 源码及 Demo
  - [Java SDK](https://github.com/tencentyun/wafer-java-server-sdk) - Java 解决方案的 SDK 源码及 Demo
  - [Node SDK](https://github.com/tencentyun/wafer-node-server-sdk) - Node 解决方案的 SDK 源码及 Demo
* 会话服务器
  - [Session Server](https://github.com/tencentyun/wafer-session-server) - 会话服务器的源码
* 客户端
  - [SDK](https://github.com/tencentyun/wafer-client-sdk) - 客户端增强 SDK 源码
  - [Demo](https://github.com/tencentyun/wafer-client-demo) - 客户端 Demo

## 云资源

开发者可以自行选择运行 Wafer 所需要的云资源，这里推荐[腾讯云微信小程序一站式解决方案](https://www.qcloud.com/solution/la.html?utm_source=wafer&utm_medium=readme&utm_campaign=github)。可以自动分配 Wafer 所需要的云资源并自动部署，可以让广大开发者轻松上手。

方案提供以下云资源：

* 通信域名与 HTTPS 证书，用于微信小程序的请求和通信（小程序域名要求使用 HTTPS 进行通信）
* 业务服务器，根据选择的语言自动部署包含 Wafer 业务服务器 Demo 和 SDK 的环境，提供给开发者进行小程序业务开发
* 会话服务器，已部署 Wafer 的会话服务器源码和所需的运行环境
* 云数据库 MySQL，支持会话服务及业务
* 基础监控和防御服务，保障业务稳定安全

## 关于 Wafer

Wafer 是一个愿景，希望可以给开发者提供到像晶片一样精致且可靠的开源项目，也希望和广大开发者一起进行打磨，打造健康的小程序全栈开发生态。

Wafer 的全称是 Weapp Application Fullstack Essential Resources，即微信小程序全栈基础资源。
