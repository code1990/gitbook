第10章　消息驱动的微服务：Spring Cloud Stream	344
快速入门	344
核心概念	349
-- 绑定器	350
-- 发布-订阅模式	351
-- 消费组	353
-- 消息分区	354
使用详解	355
-- 开启绑定功能	355
-- 绑定消息通道	356
-- 消息生产与消费	360
-- 响应式编程	366
-- 消费组与消息分区	368
-- 消息类型	370
绑定器详解	373
-- 绑定器SPI	373
-- 自动化配置	374
-- 多绑定器配置	374
--  RabbitMQ与Kafka绑定器	376
配置详解	376
-- 基础配置	377
-- 绑定通道配置	377
-- 绑定器配置	379



第8章　微服务与消息驱动	173
8.1　Spring Cloud Stream介绍	174
8.1.1　关于Stream框架	174
8.1.2　Stream框架的组成部分	174
8.1.3　消息代理中间件	174
8.2　RabbitMQ框架	175
8.2.1　RabbitMQ和AMQP	175
8.2.2　下载与运行	176
8.2.3　编写生产者	177
8.2.4　编写消费者	179
8.2.5　交换器、绑定与队列	180
8.3　Apache Kafka框架	181
8.3.1　关于Kafka	181
8.3.2　运行Kafka服务器	182
8.3.3　编写生产者	182
8.3.4　编写消费者	184
8.3.5　消费者组	185
8.4　开发消息微服务	185
8.4.1　准备工作	186
8.4.2　编写生产者	187
8.4.3　编写消费者	188
8.4.4　更换绑定器	189
8.4.5　Sink、Source与Processor	190
8.4.6　消费者组	191
8.5　本章小结	192



第5章  构建响应式消息通信组件	124
5.1  消息通信系统简介	125
5.2  使用Spring Cloud Stream构建消息通信系统	126
5.2.1  Spring Cloud Stream基本架构	126
5.2.2  Spring Cloud Stream中的Binder组件	130
5.2.3  使用Source组件实现消息发布者	135
5.2.4  使用@StreamListener注解实现消息消费者	137
5.3  引入Reactive Spring Cloud Stream实现响应式 消息通信系统	139
5.3.1  Reactive Spring Cloud Stream组件	139
5.3.2  Reactive Spring Cloud Stream示例	141
5.4  本章小结	147



第10章 消息驱动：Spring Cloud Stream274
10.1 消息队列274
10.2 基础应用276
10.2.1 声明和绑定通道276
10.2.2 自定义通道276
10.2.3 接收消息276
10.2.4 配置278
10.3 源码分析278
10.3.1 动态注册BeanDefinition279
10.3.2 绑定服务282
10.3.3 获取绑定器284
10.3.4 绑定生产者289
10.3.5 消息发送的流程291
10.3.6 StreamListener注解的处理293
10.3.7 绑定消费者298
10.3.8 消息的接收304
10.4 进阶应用306
10.4.1 Bin

第12章　消息驱动：Spring Cloud Stream130
12.1　Stream应用模型130
12.2　示例131
12.3　代码解析133
12.4　Spring Integration支持137
12.5　Binder解析138
12.6　常用配置141
12.7　小结142