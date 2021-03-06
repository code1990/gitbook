第6章　声明式服务调用：Spring Cloud Feign	199
快速入门	200
参数绑定	202
继承特性	205
Ribbon配置	209
全局配置	209
指定服务配置	209
重试机制	210
Hystrix配置	211
全局配置	211
禁用Hystrix	211
指定命令配置	212
服务降级配置	212
其他配置	214

6 使用Feign 实现声明式REST 调用. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66
6.1 Feign 简介67
6.2 为服务消费者整合Feign 67
6.3 自定义Feign 配置69
6.4 手动创建Feign 72
6.4.1 修改用户微服务72
6.4.2 修改电影微服务76
6.5 Feign 对继承的支持78
6.6 Feign 对压缩的支持79
6.7 Feign 的日志80
6.8 使用Feign 构造多参数请求82
6.8.1 GET 请求多参数的URL 82
6.8.2 POST 请求包含多个参数83



第5章　声明式REST客户端Feign  70
5.1　使用 Feign 调用服务接口  70
5.1.1　在Spring Cloud中集成Feign  71
5.1.2　使用Feign调用接口  71
5.2　自定义 Feign的配置  72
5.2.1　日志配置  72
5.2.2　契约配置  73
5.2.3　Basic认证配置  74
5.2.4　超时时间配置  75
5.2.5　客户端组件配置  75
5.2.6　GZIP压缩配置  76
5.2.7　编码器解码器配置  77
5.2.8　使用配置自定义Feign的配置  78
5.2.9　继承特性  78
5.2.10　多参数请求构造  80
5.3　脱离 Spring Cloud 使用 Feign  80
5.3.1　原生注解方式  81
5.3.2　构建Feign对象  82
5.3.3　其他配置  83
5.4　本章小结  83



第5章　REST客户端Feign	72
5.1　REST客户端	73
5.1.1　使用CXF调用REST服务	73
5.1.2　使用Restlet调用REST服务	74
5.1.3　Feign框架介绍	75
5.1.4　第一个Feign程序	76
5.1.5　请求参数与返回对象	77
5.2　使用Feign	78
5.2.1　编码器	79
5.2.2　解码器	80
5.2.3　XML的编码与解码	80
5.2.4　自定义编码器与解码器	83
5.2.5　自定义Feign客户端	83
5.2.6　使用第三方注解	85
5.2.7　Feign解析第三方注解	86
5.2.8　请求拦截器	89
5.2.9　接口日志	89
5.3　在Spring Cloud中使用Feign	90
5.3.1　Spring Cloud整合Feign	91
5.3.2　Feign负载均衡	93
5.3.3　默认配置	93
5.3.4　自定义配置	94
5.3.5　可选配置	97
5.3.6　压缩配置	98
5.4　本章小结	98



第11章　服务间通信：Spring Cloud Netflix Ribbon和Spring Cloud OpenFeign　　162
11.1　Spring Cloud Netflix Ribbon的使用　　162
11.2　Spring Cloud OpenFeign　　164
11.3　自定义OpenFeign配置　　166
11.4　Spring Cloud OpenFeign熔断　　167
11.4.1　Spring Cloud Netflix Hystrix简介　　167
11.4.2　Spring Cloud Netflix Hystrix的使用　　168
11.4.3　OpenFeign集成Hystrix熔断器　　172
11.5　小结　　173



第5章　声明式REST客户端Feign 65
5.1　使用Feign调用服务接口 65
5.1.1　在Spring Cloud中集成Feign 66
5.1.2　使用Feign调用接口 66
5.2　自定义Feign的配置 67
5.2.1　日志配置 67
5.2.2　契约配置 69
5.2.3　Basic认证配置 69
5.2.4　超时时间配置 70
5.2.5　客户端组件配置 71
5.2.6　GZIP压缩配置 72
5.2.7　编码器解码器配置 72
5.3　脱离Spring Cloud 使用Feign 73
5.3.1　原生注解方式 73
5.3.2　构建Feign对象 74
5.3.3　其他配置 75
5.4　本章小结 76

第5章　RESTful客户端：Feign45
5.1　使用Feign45
5.2　进阶场景46
5.2.1　配置与默认实现46
5.2.2　Feign整合Hystrix47
5.2.3　数据压缩48
5.2.4　日志48
5.3　小结49

第7章 声明式调用Feign 99
7．1 写一个Feign客户端 99
7．2 FeignClient详解 103
7．3 FeignClient的配置 104
7．4 从源码的角度讲解Feign的工作原理 105
7．5 在Feign中使用HttpClient和OkHttp 108
7．6 Feign是如何实现负载均衡的 110
7．7 总结 112

第5章 声明式RESTful客户端：Spring Cloud OpenFeign88
5.1 基础应用88
5.1.1 微服务之间的交互88
5.1.2 OpenFeign简介89
5.1.3 代码示例89
5.2 源码分析91
5.2.1 核心组件与概念91
5.2.2 动态注册BeanDefinition92
5.2.3 实例初始化98
5.2.4 函数调用和网络请求107
5.3 进阶应用111
5.3.1 Decoder与Encoder的定制化111
5.3.2 请求/响应压缩112
5.4 本章小结113

第7章　声明式调用Feign 101
7.1　写一个Feign客户端 101
7.2　FeignClient详解 105
7.3　FeignClient的配置 106
7.4　从源码的角度讲解Feign的工作
原理 107
7.5　在Feign中使用HttpClient和
OkHttp 110
7.6　Feign是如何实现负载均衡的 112
7.7　总结 114