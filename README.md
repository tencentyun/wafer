腾讯云微信小程序一站式解决方案
============================

腾讯云微信小程序一站式解决方案（下文简称「方案」）为需要开发微信小程序的开发者提供整合的云端资源、服务以及对应的 SDK、示例，可以让广大开发者轻松上手，获得云端能力的支持。

![解决方案架构示意](https://cloud.githubusercontent.com/assets/1901286/19711936/1d94d934-9b6c-11e6-9771-1d414dfc1c44.png)

上面一整套方案，可以直接到[腾讯云控制台](https://console.qcloud.com/la)进行购买。

方案提供以下资源和服务：

* 通信域名与 HTTPS 证书，用于微信小程序的请求和通信（小程序域名要求使用 HTTPS 进行通信）
* 业务服务器，提供给开发者进行微信小程序的业务服务
* 云数据库 MySQL，可提供给鉴权服务器以及业务服务器使用
* 鉴权服务，部署在鉴权服务器上。配合 SDK 跟踪微信小程序的会话，获得用户身份和信息
* 信道服务，配合 SDK 使用，可以提供实时双工的 WebSocket 通信能力
* 基础监控和防御服务，保障业务稳定安全

## 开发者资源索引

* 文档
  - [Wiki](https://github.com/tencentyun/weapp-solution/wiki) - 解决方案的技术架构、具体设计和实现
* 服务端
  - [PHP SDK](https://github.com/tencentyun/weapp-php-server-sdk) - PHP 解决方案的 SDK 源码及 Demo
  - [C# SDK](https://github.com/tencentyun/weapp-csharp-server-sdk) - C# 解决方案的 SDK 源码及 Demo
  - [Java SDK](https://github.com/tencentyun/weapp-java-server-sdk) - Java 解决方案的 SDK 源码及 Demo
  - [Node SDK](https://github.com/tencentyun/weapp-node-server-sdk) - Node 解决方案的 SDK 源码及 Demo
  - [Session Server](https://github.com/tencentyun/weapp-session-server) - 会话服务器的源码
* 客户端
  - [SDK](https://github.com/tencentyun/weapp-client-sdk) - 客户端增强 SDK 源码
  - [Demo](https://github.com/tencentyun/weapp-client-demo) - 客户端 Demo

