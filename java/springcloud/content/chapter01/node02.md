第4章　客户端负载均衡：Spring Cloud Ribbon	73
客户端负载均衡	73
RestTemplate详解	75
-- GET请求	75
-- POST请求	77
-- PUT请求	79
-- DELETE请求	79
源码分析	80
-- 负载均衡器	91
-- 负载均衡策略	109
配置详解	123
--自动化配置	124
-- Camden版本对RibbonClient配置的优化	125
-- 参数配置	127
-- 与Eureka结合	127
重试机制	128



5 使用Ribbon 实现客户端侧负载均衡. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 56
5.1 Ribbon 简介56
5.2 为服务消费者整合Ribbon 57
5.3 使用Java 代码自定义Ribbon 配置60
5.4 使用属性自定义Ribbon 配置63
5.5 脱离Eureka 使用Ribbon 64



第4章　客户端负载均衡 Ribbon  52
4.1　Ribbon  52
4.1.1　Ribbon模块  52
4.1.2　Ribbon 使用  53
4.2　RestTemplate 结合 Ribbon 使用  54
4.2.1　使用 RestTemplate 与整合 Ribbon  54
4.2.2　RestTemplate 负载均衡示例  57
4.2.3　@LoadBalanced 注解原理  58
4.2.4　Ribbon API 使用  62
4.2.5　Ribbon 饥饿加载  63
4.3　负载均衡策略介绍  64
4.4　自定义负载策略  65
4.5　配置详解  66
4.5.1　常用配置  66
4.5.2　代码配置 Ribbon  67
4.5.3　配置文件方式配置Ribbon  67
4.6　重试机制  68
4.7　本章小结  69

第4章　客户端负载均衡Ribbon 47
4.1　Ribbon 47
4.1.1　Ribbon模块 47
4.1.2　Ribbon使用 48
4.2　RestTemplate结合Ribbon使用 49
4.2.1　使用RestTemplate与整合Ribbon 49
4.2.2　RestTemplate负载均衡示例 52
4.2.3　@LoadBalanced注解原理 53
4.2.4　Ribbon API使用 57
4.2.5　Ribbon饥饿加载 58
4.3　负载均衡策略介绍 59
4.4　自定义负载策略 60
4.5　配置详解 61
4.5.1　常用配置 61
4.5.2　代码配置Ribbon 62
4.6　重试机制 63
4.7　本章小结 64



第6章 负载均衡Ribbon 82
6．1 RestTemplate简介 82
6．2 Ribbon简介 83
6．3 使用RestTemplate和Ribbon来消费服务 83
6．4 LoadBalancerClient简介 86
6．5 源码解析Ribbon 88



第4章　负载均衡	47
4.1　Ribbon介绍	48
4.1.1　Ribbon简介	48
4.1.2　Ribbon子模块	48
4.1.3　负载均衡器组件	48
4.2　第一个Ribbon程序	49
4.2.1　编写服务	49
4.2.2　编写请求客户端	51
4.2.3　Ribbon的配置	52
4.3　Ribbon的负载均衡机制	53
4.3.1　负载均衡器	53
4.3.2　自定义负载规则	54
4.3.3　Ribbon自带的负载规则	56
4.3.4　Ping机制	57
4.3.5　自定义Ping	59
4.3.6　其他配置	59
4.4　在Spring Cloud中使用Ribbon	60
4.4.1　准备工作	60
4.4.2　使用代码配置Ribbon	61
4.4.3　使用配置文件设置Ribbon	63
4.4.4　Spring使用Ribbon的API	64
4.5　RestTemplate负载均衡	66
4.5.1　@LoadBalanced注解概述	66
4.5.2　编写自定义注解以及拦截器	66
4.5.3　使用自定义拦截器以及注解	68
4.5.4　在控制器中使用RestTemplate	69
4.6　本章小结	71



第4章 Spring Cloud Netflix Ribbon与负载均衡 67
4.1 负载均衡 68
4.1.1 负载均衡的类型 68
4.1.2 负载均衡的算法 70
4.2 使用Ribbon实现客户端负载均衡 71
4.2.1 Spring Cloud Netflix Ribbon简介 71
4.2.2 使用DiscoveryClient查找服务 72
4.2.3 通过RestTemplate调用服务 74
4.3 Ribbon基本架构 78
4.3.1 Ribbon核心机制 79
4.3.2 Ribbon负载均衡策略 81
4.3.3 @LoadBalanced注解与RestTemplate 82
4.3.4 @RibbonClient注解与自定义负载均衡策略 83
4.4 本章小结 85



第4章  服务治理与负载均衡    58
4.1  什么是服务治理   58
4.2  构建服务治理——Eureka   59
4.2.1  搭建微服务Parent工程   60
4.2.2  搭建服务治理服务器——Eureka服务器       62
4.2.3  搭建服务提供者——注册服务       64
4.2.4  搭建服务消费者——获取服务       68
4.3  使用客户端负载均衡——Ribbon      72
4.3.1  什么是客户端负载均衡   72
4.3.2  启用Ribbon      74
4.3.3  负载均衡测试   75
4.4  使用Feign简化微服务调用       77
4.5  深入Eureka  80
4.5.1  服务注册及相关原理       80
4.5.2  Eureka自我保护模式       82
4.5.3  注册一个服务实例需要的时间       84
4.5.4  Eureka高可用集群及示例       84
4.5.5  多网卡及IP指定      88
4.5.6  Eureka服务访问安全       89
4.6  深入Ribbon  90
4.6.1  Ribbon客户端负载均衡原理   90
4.6.2  Ribbon负载均衡策略及配置   92
4.6.3  直接使用Ribbon API       94
4.7  深入Feign    96
4.7.1  Feign的参数绑定     96
4.7.2  Feign中的继承  97
4.7.3  Feign与Swagger的冲突  98
4.8  微服务健康监控   99
4.9  异构服务解决方案——Sidecar   101



第7章 客户端负载均衡器：Spring Cloud Netflix Ribbon162
7.1 负载均衡162
7.2 基础应用163
7.3 源码分析165
7.3.1 配置和实例初始化165
7.3.2 与OpenFeign的集成167
7.3.3 负载均衡器LoadBalancerClient171
7.3.4 ILoadBalancer173
7.3.5 负载均衡策略实现177
7.4 进阶应用184
7.4.1 Ribbon API184
7.4.2 使用Netty发送网络请求185
7.4.3 只读数据库的负载均衡实现186
7.5 本章小结187



第4章　客户端负载均衡：Ribbon40
4.1　使用Ribbon40
4.2　进阶场景42
4.2.1　使用配置类42
4.2.2　使用配置文件42
4.2.3　默认实现43
4.3　小结44



第6章　负载均衡Ribbon 84
6.1　RestTemplate简介 84
6.2　Ribbon简介 85
6.3　使用RestTemplate和Ribbon来消费
服务 85
6.4　LoadBalancerClient简介 88
6.5　源码解析Ribbon 90