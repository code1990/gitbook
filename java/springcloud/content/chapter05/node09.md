第13章  集成NoSQL数据库，实现搜索引擎  /339
13.1  Elasticsearch——搜索应用服务器  /339
∣13.1.1  什么是搜索引擎  /339
∣13.1.2  用数据库实现搜索功能  /339
∣13.1.3  认识Elasticsearch  /343
∣13.1.4  Elasticsearch应用案例  /343
∣13.1.5  对比Elasticsearch与MySQL  /343
∣13.1.6  认识ElasticSearchRepository  /344
∣13.1.7  认识ElasticsearchTemplate  /345
∣13.1.8  认识注解@Document  /345
∣13.1.9  管理索引  /347
13.2  【实例55】用ELK管理Spring Boot应用程序的日志  /348
∣13.2.1  安装Elasticsearch  /348
∣13.2.2  安装Logstash  /349
∣13.2.3  安装Kibana  /350
∣13.2.4  配置Spring Boot项目  /350
∣13.2.5  创建日志计划任务  /351
∣13.2.6  用Kibana查看管理日志  /352
13.3  【实例56】在Spring Boot中集成Elasticsearch，实现增、删、改、查功能  /353
∣13.3.1  集成Elasticsearch  /353
∣13.3.2  创建实体  /353
∣13.3.3  实现增、删、改、查文档的功能  /355
13.4  Elasticsearch查询  /356
∣13.4.1  自定义方法  /356
∣13.4.2  精准查询  /357
∣13.4.3  模糊查询  /359
∣13.4.4  范围查询  /362
∣13.4.5  组合查询  /362
∣13.4.6  分页查询  /363
∣13.4.7  聚合查询  /364
13.5  【实例57】实现产品搜索引擎  /365
13.6  Solr——搜索应用服务器  /367
∣13.6.1  了解Solr  /367
∣13.6.2  安装配置Solr  /367
∣13.6.3  整合Spring Boot和Solr  /368
13.7  【实例58】在Sping Boot中集成Solr，实现数据的增、删、改和查  /369
∣13.7.1  创建User类  /369
∣13.7.2  测试增、删、改、查功能  /369
13.8  对比Elasticsearch和Solr  /372

第13章　Elasticsearch
13.1　Elasticsearch介绍
13.1.1　安装Elasticsearch
13.1.2　Elasticsearch的基本概念
13.2　使用REST访问Elasticsearch
13.2.1　添加文档
13.2.2　根据主键查询
13.2.3　根据主键更新
13.2.4　根据主键删除
13.2.5　搜索文档
13.2.6　联合多个索引搜索
13.3　使用RestTemplate访问ES
13.3.1　创建Book
13.3.2　使用RestTemplate获取搜索结果
13.4　Spring Data Elastic
13.4.1　安装Spring Data
13.4.2　编写Entity
13.4.3　编写Dao
13.4.4　编写Controller