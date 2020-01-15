云原生Java
目录
前言（James Watters）.xv
前言（Rod Johnson） xvii
前言 xix
第Ⅰ部分　基础知识
第1 章　云原生应用程序 3
亚马逊的故事  3
平台的承诺  5
模式  7
可扩展性 . 7
可靠性  8
敏捷性 . 8
Netflix 的故事 . 9
微服务 . 11
拆分单体系统  12
Netflix OSS . 13
云原生Java . 14
十二要素原则 . 14
代码库 . 15
依赖 . 15
配置 . 16
x ｜ 目录
后端服务 . 17
构建、发布、运行  17
进程 . 17
端口绑定 . 18
并发 . 18
易处理 . 18
开发/ 生产环境一致 . 19
日志 . 19
管理进程 . 19
总结  20
第2 章　训练营：Spring Boot 和Cloud Foundry21
什么是Spring Boot  21
Spring Initializr 入门  21
Spring Tool Suite 入门  30
安装Spring Tool Suite（STS）. 30
使用Spring Initializr 创建一个新项目  31
Spring 指南大全 . 36
遵循STS 中的指南 . 38
配置 . 40
Cloud Foundry 平台 . 52
总结 . 66
第3 章　符合十二要素程序风格的配置. 67
令人迷惑的“配置”合并 . 67
Spring 框架对配置的支持  67
PropertyPlaceholderConfigurer  68
Environment 接口和@Value 注解 . 69
Profile  71
启动配置 . 73
使用Spring Cloud Config Server 进行中心化、日志型的配置. 76
Spring Cloud Config Server . 76
Spring Cloud Config 客户端  78
安全 . 79
目录 ｜ xi
可刷新的配置 . 79
总结  83
第４章　测试. 85
测试的构成 . 86
在Spring Boot 中进行测试 . 86
集成测试 . 88
测试切片 . 89
测试中的Mock . 89
使用@SpringBootTest 中的Servlet 容器  93
测试分片 . 94
端到端测试 . 102
测试分布式系统  102
消费者驱动的契约测试 . 104
Spring Cloud Contract . 105
总结  113
第5 章　迁移遗留的应用程序. 115
契约  115
迁移应用程序环境  116
开箱即用的构建包（Buildpacks） . 116
自定义的构建包  117
容器化的应用程序  118
将应用程序迁移到云上的微重构  119
连接后端服务  120
用Spring 实现服务平等  121
总结  133
第Ⅱ部分　Web 服务
第6 章　REST API. 137
伦纳德· 理查森的成熟模型  137
使用Spring MVC 实现简单的REST API . 139
内容协商  142
xii ｜ 目录
读写二进制数据  142
Google Protocol Buffers  145
错误处理 . 150
超媒体 . 152
媒体类型和模式  158
API 版本 . 159
编写REST API 文档 . 162
客户端  167
用于临时浏览和交互的REST 客户端 . 167
RestTemplate . 171
总结 . 177
第7 章　路由 179
DiscoveryClient 接口  180
Cloud Foundry Route 服务  190
总结  195
第8 章　边缘服务. 197
Greetings 服务  198
一个简单的边缘服务 . 200
Netflix Feign  202
使用Netflix Zuul 进行过滤和代理 . 204
自定义Zuul 过滤器 . 214
边缘服务的安全  218
OAuth . 219
服务端应用程序  220
HTML5 和JavaScript 单页面应用程序 . 221
没有用户的应用  221
受信任的客户端  221
Spring Security  222
Spring Cloud Security . 227
一个Spring Security OAuth 授权服务器 . 227
保护Greetings 资源服务器的安全  232
创建一个受OAuth 保护的单页面应用程序  238
总结 . 247
目录 ｜ xiii
第Ⅲ部分　数据整合
第9 章　数据管理. 251
数据建模 . 251
关系数据库管理系统（RDBMS）  252
NoSQL. 253
Spring Data . 253
Spring Data 应用程序的结构 . 254
域类 . 254
库  254
为领域数据组织Java 包  255
使用JDBC 访问RDBMS 数据 . 258
Spring 的JDBC 支持 . 259
Spring Data 示例 . 261
Spring Data JPA 264
Account Service . 264
集成测试 . 274
Spring Data MongoDB . 275
Order Service . 275
集成测试 . 282
Spring Data Neo4j . 284
Inventory Service . 284
集成测试 . 294
Spring Data Redis  297
高速缓存 . 298
总结  302
第10 章　消息系统. 303
Spring Integration 的事件驱动架构 . 304
消息端点 . 305
使用简单的组件构建复杂的系统  306
消息代理、桥接、竞争消费者模式和事件溯源 . 314
发布—订阅目的地  314
点对点目的地  315
xiv ｜ 目录
Spring Cloud Stream  315
流生产者 . 316
流消费者 . 321
总结  323
第11 章　批处理和任务 325
批处理工作  325
Spring Batch . 326
我们的第一个批处理作业 . 327
调度  336
通过消息传递远程分区Spring 批处理作业 . 337
任务管理 . 346
通过Workflow 进行的以工作流为中心的整合  348
使用消息传递的分布式. 362
总结 . 362
第12 章　数据集成. 363
分布式事务  364
故障隔离和优雅的降级 364
saga 模式 . 369
CQRS（命令查询责任分离）  369
投诉API  371
投诉统计API  383
Spring Cloud Data Flow  385
Stream . 387
任务 . 390
REST API  391
实现Data Flow 客户端  392
总结  407
第IV 部分　生产
第13 章　可观测的系统. 411
你构建，你运行 . 412
目录 ｜ xv
谋杀神秘微服务  413
十二要素运维 . 413
新方式 . 414
可观测性  416
推与拉的可观测性和解析率  416
使用Spring Boot Actuator 捕获应用程序的当前状态  417
度量  418
通过/info 端点识别服务 . 431
健康检查 . 432
审计事件  436
应用程序日志  439
指定日志输出  440
指定日志级别  441
分布式跟踪 . 445
用Spring Cloud Sleuth 寻找线索  446
多少数据是足够的  447
OpenZipkin ：一张图片胜过千丝万缕 . 448
跟踪其他平台和技术 . 454
仪表板  455
使用Hystrix 仪表板监控下游服务  455
Codecentric 的Spring Boot Admin  459
Ordina Microservices 仪表板 . 462
Pivotal Cloud Foundry 的AppsManager  463
修复  465
总结 . 467
第14 章　服务代理.469
创建后台服务  470
平台视图  472
使用Spring Cloud Cloud Foundry Service Broker 实现服务代理  473
简单的Amazon S3 服务代理  473
服务目录 . 474
管理服务实例  476
服务绑定 . 482
保护服务代理  486
xvi ｜ 目录
部署 . 487
使用BOSH 发布 . 487
使用Cloud Foundry 发布  488
注册Amazon S3 Service Broker . 489
创建Amazon S3 服务实例  490
消费服务实例  491
S3 客户端应用程序 . 493
运行测试 . 496
总结  496
第15 章　持续交付.497
持续集成之外  497
John Allspaw 在Flickr 以及后来的Etsy . 498
Netflix 的Adrian Cockroft  499
亚马逊的持续交付  500
流水线  500
测试  501
持续交付微服务 502
工具  503
Concourse . 503
容器 . 504
持续交付微服务 . 504
安装Concourse . 505
基本的管道设计  506
持续集成 . 518
消费者驱动的协约测试  518
User 微服务流水线  519
数据 . 522
生产 . 523
第V 部分　附录
附录A　在Java EE 中使用Spring Boot527
索引. 552
云原生Java