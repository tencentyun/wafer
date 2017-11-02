<img src="https://cdn.rawgit.com/tencentyun/wafer/master/logo.svg" width="32" /> Wafer - 快速构建具备弹性伸缩能力的微信小程序
=========================================

Wafer 是腾讯云面向广大开发者提供的小程序开发全栈资源套件，套件提供小程序会话管理服务和 WebSocket 信道服务，部署方式具备良好的弹性伸缩能力，可以快速应对业务的爆发增长，同时具备较低的开发门槛。

如果你希望自己动手搭建小程序，[小程序实验室](https://www.qcloud.com/developer/labs/lab/10004)将提供 step by step 的教程帮助你完成目标！

阅读 [Wiki](https://github.com/tencentyun/wafer/wiki) 文档了解 Wafer 提供的服务、部署方法、架构设计以及实现细节。

使用过程中若有疑问，欢迎到[腾讯云开发者问答社区](https://www.qcloud.com/developer/ask)进行提问。

## Wafer2 正式发布

开发者工具方案（以下简称 Wafer2）是 2017 年腾讯云基于原来的 Wafer 解决方案（以下简称 Wafer1）并与微信团队深度定制合作的一站式小程序解决方案，Wafer 团队基于腾讯云强大的 IaaS 能力搭建了一个 PaaS 小程序解决方案，用户只需要开通，即可使用开发者工具上传、部署、调试小程序后端代码，无需了解服务器运维、数据库部署搭建即可使用。

[点击查看Wafer2 指引](https://github.com/tencentyun/wafer2-quickstart)

## Wafer1 开发者资源索引

* 客户端
  - [SDK](https://github.com/tencentyun/wafer-client-sdk) - 客户端增强 SDK 源码
  - [Demo](https://github.com/tencentyun/wafer-client-demo) - 客户端 Demo
* 业务服务器
  - [PHP SDK](https://github.com/tencentyun/wafer-php-server-sdk) - PHP 解决方案的 SDK 源码及 Demo
  - [C# SDK](https://github.com/tencentyun/wafer-csharp-server-sdk) - C# 解决方案的 SDK 源码及 Demo
  - [Java SDK](https://github.com/tencentyun/wafer-java-server-sdk) - Java 解决方案的 SDK 源码及 Demo
  - [Node SDK](https://github.com/tencentyun/wafer-node-server-sdk) - Node 解决方案的 SDK 源码及 Demo
* 会话服务器
  - [Session Server](https://github.com/tencentyun/wafer-session-server) - PHP 会话服务器的源码
  - [Node Middleware](https://github.com/tencentyun/wafer-node-session) - 独立 NodeJS 会话服务中间件
* 微信小程序文档
  - [小程序介绍](https://mp.weixin.qq.com/debug/wxadoc/introduction)
  - [设计指南](https://mp.weixin.qq.com/debug/wxadoc/design/)
  - [开发指南](https://mp.weixin.qq.com/debug/wxadoc/dev/)
    - [组件](https://mp.weixin.qq.com/debug/wxadoc/dev/component/)
    - [API 文档](https://mp.weixin.qq.com/debug/wxadoc/dev/api/)
    - [开发工具下载](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html)
* 优质第三方资源
  - [10 分钟实现 PHP 业务](https://github.com/tencentyun/wafer/issues/5) - @tsr106
  - [自行部署 Wafer 的一点心得](https://github.com/tencentyun/wafer/issues/8) - @ITJaye

## 关于 Wafer

Wafer 是一个愿景，希望可以给开发者提供到像晶片一样精致且可靠的开源项目，也希望和广大开发者一起进行打磨，打造健康的小程序全栈开发生态。

Wafer 的全称是 Weapp Application Fullstack Essential Resources，即微信小程序全栈基础资源。

关于 Wafer 的探索历程，可以阅读[这篇文章](https://github.com/tencentyun/blog/issues/1)

## LICENSE

[MIT](LICENSE)
