第5章　服务容错保护：Spring Cloud Hystrix	130
快速入门	131
原理分析	135
-- 工作流程	135
-- 断路器原理	144
-- 依赖隔离	148
使用详解	151
-- 创建请求命令	151
-- 定义服务降级	154
-- 异常处理	157
-- 命令名称、分组以及线程池划分	158
-- 请求缓存	159
-- 请求合并	166
属性详解	172
-- Command属性	174
-- collapser属性	184
-- threadPool属性	185
Hystrix仪表盘	187
Turbine集群监控	192
-- 构建监控聚合服务	192
-- 与消息代理结合	196

7 使用Hystrix 实现微服务的容错处理. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 85
7.1 实现容错的手段85
7.1.1 雪崩效应85
7.1.2 如何容错86
7.2 使用Hystrix 实现容错88
7.2.1 Hystrix 简介88
7.2.2 通用方式整合Hystrix 89
7.2.3 Hystrix 断路器的状态监控与深入理解91
7.2.4 Hystrix 线程隔离策略与传播上下文93
7.2.5 Feign 使用Hystrix 96
7.3 Hystrix 的监控101
7.3.1 Feign 项目的Hystrix 监控102
7.4 使用Hystrix Dashboard 可视化监控数据103
7.5 使用Turbine 聚合监控数据105
7.5.1 Turbine 简介105
7.5.2 使用Turbine 监控多个微服务105
7.5.3 使用消息中间件收集数据108

第6章　Hystrix 服务容错处理  84
6.1　Hystrix  84
6.1.1　Hystrix的简单使用  84
6.1.2　回退支持  85
6.1.3　信号量策略配置  86
6.1.4　线程隔离策略配置  86
6.1.5　结果缓存  87
6.1.6　缓存清除  88
6.1.7　合并请求  89
6.2　在 Spring Cloud 中使用Hystrix  91
6.2.1　简单使用  91
6.2.2　配置详解  92
6.2.3　Feign整合Hystrix服务容错  95
6.2.4　Feign中禁用Hystrix  97
6.3　Hystrix 监控  97
6.4　整合 Dashboard 查看监控数据  98
6.5　Turbine 聚合集群数据  100
6.5.1　Turbine使用  100
6.5.2　context-path导致监控失败  101
6.6　本章小结  102





第6章　Spring Cloud的保护机制	99
6.1　概述	100
6.1.1　实际问题	100
6.1.2　传统的解决方式	101
6.1.3　集群容错框架Hystrix	101
6.1.4　Hystrix的功能	102
6.2　第一个Hystrix程序	103
6.2.1　准备工作	103
6.2.2　客户端使用Hystrix	103
6.2.3　调用错误服务	105
6.2.4　Hystrix的运作流程	106
6.3　Hystrix的使用	108
6.3.1　命令执行	108
6.3.2　属性配置	110
6.3.3　回退	111
6.3.4　回退的模式	112
6.3.5　断路器开启	113
6.3.6　断路器关闭	116
6.3.7　隔离机制	118
6.3.8　合并请求	121
6.3.9　请求缓存	125
6.4　在Spring Cloud中使用Hystrix	127
6.4.1　整合Hystrix	128
6.4.2　命令配置	130
6.4.3　默认配置	131
6.4.4　缓存注解	132
6.4.5　合并请求注解	134
6.4.6　Feign与Hystrix整合	136
6.4.7　Hystrix监控	140
6.5　本章小结	142



第5章 Spring Cloud Netflix Hystrix与服务容错 86
5.1 服务消费者容错思想和模式 87
5.1.1 服务消费者容错的需求 87
5.1.2 服务隔离 88
5.1.3 服务熔断 90
5.1.4 服务回退 91
5.2 使用Hystrix实现服务容错 91
5.2.1 引入Hystrix 92
5.2.2 使用Hystrix实现服务隔离 93
5.2.3 使用Hystrix实现服务熔断 96
5.2.4 使用Hystrix实现服务回退 99
5.3 Hystrix基本原理 101
5.3.1 服务隔离 101
5.3.2 服务熔断 103
5.3.3 Hystrix配置项 105



第6章　Hystrix 服务容错处理 77
6.1　Hystrix 77
6.1.1　Hystrix的简单使用 77
6.1.2　回退支持 78
6.1.3　信号量策略配置 79
6.1.4　线程隔离策略配置 79
6.1.5　结果缓存 80
6.1.6　缓存清除 81
6.1.7　合并请求 83
6.2　在Spring Cloud中使用Hystrix 84
6.2.1　简单使用 84
6.2.2　配置详解 85
6.2.3　Feign整合Hystrix服务容错 88
6.2.4　Feign中禁用Hystrix 90
6.3　Hystrix监控 91
6.4　整合Dashboard查看监控数据 92
6.5　Turbine聚合集群数据 94
6.5.1　Turbine使用 94
6.5.2　context-path导致监控失败 95
6.6　本章小结 95

第5章  微服务容错保护——Hystrix       102
5.1  什么是微服务容错保护      102
5.2  快速启动Hystrix  103
5.2.1  引入Hystrix依赖     104
5.2.2  开启Hystrix支持     104
5.2.3  修改UserService实现      104
5.2.4  容错测试   105
5.2.5  服务降级的两种实现方式       107
5.2.6  在Feign中使用Hystrix回退   109
5.3  Hystrix容错机制分析  110
5.3.1  Hystrix整体处理流程      111
5.3.2  HystrixCommand与HystrixObservableCommand   113
5.3.3  断路器原理分析       115
5.3.4  Hystrix异常——HystrixBadRequestException       117
5.4  服务隔离      117
5.4.1  线程池隔离与信号量隔离       118
5.4.2  服务隔离的颗粒度   119
5.4.3  服务隔离配置   119
5.4.4  小结   120
5.5  服务降级模式      121
5.5.1  快速失败   121
5.5.2  静默失败   121
5.5.3  返回默认值       122
5.5.4  返回组装的值   122
5.5.5  返回远程缓存   123
5.5.6  主/从降级模式  124
5.6  请求缓存      127
5.7  请求合并      128
5.8  Hystrix监控  130
5.8.1  Hystrix仪表盘   131
5.8.2  Turbine仪表盘集群监控  133
5.8.3  Turbine与消息服务器集成      136

第6章 断路器：Hystrix114
6.1 基础应用114
6.1.1 RestTemplate与Hystrix115
6.1.2 OpenFeign与Hystrix117
6.2 Hystrix原理118
6.2.1 服务雪崩118
6.2.2 断路器119
6.2.3 服务降级操作120
6.2.4 资源隔离121
6.2.5 Hystrix实现思路122
6.3 源码解析123
6.3.1 封装HystrixCommand123
6.3.2 HystrixCommand类结构129
6.3.3 异步回调执行命令129
6.3.4 异步执行命令和同步执行命令137
6.3.5 断路器逻辑137
6.3.6 资源隔离143
6.3.7 请求超时监控148
6.3.8 失败回滚逻辑150
6.4 进阶应用152
6.4.1 异步与异步回调执行命令152
6.4.2 继承HystrixCommand153
6.4.3 请求合并157
6.5 本章小结161

第6章　熔断器：Hystrix50
6.1　为什么要有熔断50
6.2　熔断原理52
6.3　使用Hystrix55
6.4　Hystrix数据监控58
6.4.1　健康指示器58
6.4.2　监控面板59
6.4.3　聚合监控61
6.5　小结62

第8章 熔断器Hystrix 113
8．1 Hystrix简介 113
8．2 Hystrix解决的问题 113
8．3 Hystrix的设计原则 115
8．4 Hystrix的工作机制 115
8．5 在RestTemplate和Ribbon上使用熔断器 116
8．6 在Feign上使用熔断器 117
8．7 使用Hystrix Dashboard监控熔断器的状态 118
8．7．1 在RestTemplate中使用Hystrix Dashboard 118
8．7．2 在Feign中使用Hystrix Dashboard 121
8．8 使用Turbine聚合监控 122

第8章　熔断器Hystrix 115
8.1　什么是Hystrix 115
8.2　Hystrix解决了什么问题 115
8.3　Hystrix的设计原则 117
8.4　Hystrix的工作机制 117
8.5　在RestTemplate和Ribbon上使用
熔断器 118
8.6　在Feign上使用熔断器 119
8.7　使用Hystrix Dashboard监控熔断器的
状态 120
8.7.1　在RestTemplate中使用Hystrix Dashboard 120
8.7.2　在Feign中使用
Hystrix Dashboard 123
8.8　使用Turbine聚合监控 124