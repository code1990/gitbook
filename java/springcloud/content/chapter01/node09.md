第11章　分布式服务跟踪：Spring Cloud Sleuth	386
快速入门	386
-- 准备工作	386
-- 实现跟踪	389
跟踪原理	390
抽样收集	392
与Logstash整合	394
与Zipkin整合	397
--  HTTP收集	398
-- 消息中间件收集	402
-- 收集原理	404
-- 数据存储	414
--  API接口	417



10 使用Spring Cloud Sleuth 实现微服务跟踪. . . . . . . . . . . . . . . . . . . . . . . . . . . . 167
10.1 为什么要实现微服务跟踪167
10.2 Spring Cloud Sleuth 简介168
10.3 整合Spring Cloud Sleuth 170
10.4 Spring Cloud Sleuth 与ELK 配合使用172
10.5 Spring Cloud Sleuth 与Zipkin 配合使用176
10.5.1 Zipkin 简介176
10.5.2 编写Zipkin Server 176
10.5.3 微服务整合Zipkin 178
10.5.4 使用消息中间件收集数据181
10.5.5 存储跟踪数据183



第11章　Sleuth 服务跟踪  197
11.1　Spring Cloud 集成 Sleuth  197
11.2　整合 Logstash  198
11.2.1　ELK 简介  198
11.2.2　输出 JSON 格式日志  198
11.3　整合 Zipkin  200
11.3.1　Zipkin 数据收集服务  200
11.3.2　项目集成 Zipkin 发送调用链数据  201
11.3.3　抽样采集数据  203
11.3.4　异步任务线程池定义  203
11.3.5　TracingFilter  204
11.3.6　监控本地方法  205
11.3.7　过滤不想跟踪的请求  206
11.3.8　用 RabbitMq 代替 Http 发送调用链数据  206
11.3.9　用 Elasticsearch 存储调用链数据  207
11.4　本章小结  208





第 13章 服务链路追踪Spring Cloud Sleuth 184
13．1 为什么需要Spring Cloud Sleuth 184
13．2 基本术语 184
13．3 案例讲解 186
13．3．1 启动Zipkin Server 187
13．3．2 构建服务提供者 187
13．3．3 构建服务消费者 189
13．3．4 项目演示 191
13．4 在链路数据中添加自定义数据 192
13．5 使用RabbitMQ 传输链路数据 192
13．6 在MySQL数据库中存储链路数据 194
13．7 在ElasticSearch中存储链路数据 195
13．8 用Kibana展示链路数据 196



第10章　微服务跟踪	219
10.1　概述	220
10.1.1　实际问题与Sleuth	220
10.1.2　服务跟踪系统	220
10.1.3　Sleuth的基本概念	220
10.1.4　项目准备	221
10.2　Sleuth整合Zipkin	222
10.2.1　Zipkin简介	222
10.2.2　构建Zipkin服务器项目	223
10.2.3　配置微服务	224
10.2.4　查看数据	225
10.2.5　使用MySQL保存数据	228
10.2.6　使用消息采集数据	230
10.3　Sleuth整合ELK	232
10.3.1　关于ELK	232
10.3.2　下载ELK	233
10.3.3　运行Elasticsearch	233
10.3.4　使用Logstash读取JSON	234
10.3.5　使用Kibana展示数据	235
10.3.6　使用Logback转换JSON	237
10.4　本章小结	240



第10章 Spring Cloud Sleuth与服务监控 207
10.1 服务监控与Spring Cloud Sleuth 207
10.1.1 服务监控基本原理 207
10.1.2 引入Spring Cloud Sleuth 209
10.2 整合Spring Cloud Sleuth与Zipkin 215
10.2.1 Zipkin基本结构 215
10.2.2 引入Zipkin 216
10.2.3 使用Zipkin跟踪服务调用链路 218
10.2.4 使用Zipkin实现自定义跟踪 226
10.3 本章小结 228

第8章 Spring Cloud Stream与事件驱动 151
8.1 事件驱动架构与模型 152
8.1.1 基本事件驱动架构与实现机制 152
8.1.2 事件驱动与领域模型 155
8.2 引入Spring Cloud Stream 157
8.2.1 Spring Cloud Stream基本架构 157
8.2.2 Spring Cloud Stream与Spring Integration 159
8.2.3 Spring Cloud Stream与消息中间件 162
8.3 实现消息发布者 165
8.3.1 消息发送场景与实现流程 165
8.3.2 在服务中添加消息发布者 166
8.4 实现消息消费者 170
8.4.1 消息消费场景与实现流程 170
8.4.2 在服务中添加消息消费者 172
8.5 本章小结 177



第12章　服务链路追踪：Spring Cloud Sleuth　　175
12.1　Spring Cloud Sleuth简介　　175
12.2　利用链路追踪监听网络请求　　176
12.2.1　服务端的实现　　176
12.2.2　客户端集成Spring Cloud Sleuth　　179
12.3　通过消息中间件实现链路追踪　　180
12.4　存储追踪数据　　182
12.5　小结　　184

第9章　调用链追踪：Spring Cloud Sleuth89
9.1　术语解释90
9.2　Zipkin简介91
9.3　使用Zipkin93
9.4　Span进阶场景97
9.4.1　自定义日志采样策略97
9.4.2　Span的生命周期98
9.4.3　重命名Span99
9.4.4　自定义Span100
9.5　其他场景与配置101
9.6　小结104

第11章　服务链路追踪
Spring Cloud Sleuth 147
11.1　为什么需要Spring Cloud Sleuth 147
11.2　基本术语 147
11.3　案例讲解 148
11.3.1　构建Zipkin Server 148
11.3.2　构建User Service 149
11.3.3　构建Gateway Service 151
11.3.4　项目演示 152
11.4　在链路数据中添加自定义数据 153
11.5　使用RabbitMQ 传输链路数据 154
11.6　在MySQL数据库中存储链路数据 155
11.6.1　使用Http传输链路数据，
并存储在MySQL数据
库中 156
11.6.2　使用RabbitMQ传输链路
数据，并存储在MySQL
数据库中 157
11.7　在ElasticSearch中存储链路数据 158
11.8　用Kibana展示链路数据 159