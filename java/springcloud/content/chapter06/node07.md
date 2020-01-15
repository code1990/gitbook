第5章　访问数据库　82
5.1　配置数据源　83
5.1.1　启动默认数据源　83
5.1.2　配置自定义数据源　83
5.2　使用JdbcTemplate操作数据库　86
5.3　使用JPA（Hibernate）操作数据　90
5.3.1　概述　90
5.3.2　开发JPA　90
5.4　整合MyBatis框架　96
5.4.1　MyBatis简介　96
5.4.2　MyBatis的配置　97
5.4.3　Spring Boot整合MyBatis　101
5.4.4　MyBatis的其他配置　104
第6章　聊聊数据库事务处理　107
6.1　JDBC的数据库事务　108
6.2　Spring声明式事务的使用　110
6.2.1　Spring声明式数据库事务约定　110
6.2.2　@Transactional的配置项　111
6.2.3　Spring事务管理器　113
6.2.4　测试数据库事务　114
6.3　隔离级别　118
6.3.1　数据库事务的知识　118
6.3.2　详解隔离级别　120
6.4　传播行为　124
6.4.1　传播行为的定义　125
6.4.2　测试传播行为　126
6.5　@Transactional自调用失效问题　130
第7章　使用性能利器——Redis　134
7.1　spring-data-redis项目简介　135
7.1.1　spring-data-redis项目的设计　135
7.1.2　RedisTemplate　137
7.1.3　Spring对Redis数据类型操作的封装　139
7.1.4　SessionCallback和RedisCallback接口　141
7.2　在Spring Boot中配置和使用Redis　142
7.2.1　在Spring Boot中配置Redis　142
7.2.2　操作Redis数据类型　143
7.3　Redis的一些特殊用法　148
7.3.1　使用Redis事务　148
7.3.2　使用Redis流水线　149
7.3.3　使用Redis发布订阅　150
7.3.4　使用Lua脚本　153
7.4　使用Spring缓存注解操作Redis　156
7.4.1　缓存管理器和缓存的启用　156
7.4.2　开发缓存注解　157
7.4.3　测试缓存注解　163
7.4.4　缓存注解自调用失效问题　165
7.4.5　缓存脏数据说明　165
7.4.6　自定义缓存管理器　166
第8章　文档数据库——MongoDB　168
8.1　配置MongoDB　169
8.2　使用MongoTemplate实例　170
8.2.1　搭建开发环境　170
8.2.2　使用MongoTemplate操作文档　173
8.3　使用JPA　178
8.3.1　基本用法　178
8.3.2　使用自定义查询　180



