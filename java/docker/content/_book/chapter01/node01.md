12 Docker 入门. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 197
12.1 Docker 简介197
12.2 Docker 的架构197
12.3 安装Docker 199
12.3.1 系统要求199
12.3.2 移除非官方软件包199
12.3.3 设置Yum 源199
12.3.4 安装Dokcer 200
12.3.5 卸载Docker 201
12.4 配置镜像加速器201
12.5 Docker 常用命令202
12.5.1 Docker 镜像常用命令202
12.5.2 Docker 容器常用命令204
13 将微服务运行在Docker 上. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 209
13.1 使用Dockerfile 构建Docker 镜像209
13.1.1 Dockerfile 常用指令210
13.1.2 使用Dockerfile 构建镜像215
13.2 使用Docker Registry 管理Docker 镜像217
13.2.1 使用Docker Hub 管理镜像217
13.2.2 使用私有仓库管理镜像219
13.3 使用Maven 插件构建Docker 镜像220
13.3.1 快速入门221
13.3.2 插件读取Dockerfile 进行构建222
13.3.3 将插件绑定在某个phase 执行223
13.3.4 推送镜像224
13.4 常见问题与总结226
14 使用Docker Compose 编排微服务. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 227
14.1 Docker Compose 简介227
14.2 安装Docker Compose 227
14.2.1 安装Compose 228
14.2.2 安装Compose 命令补全工具228
14.3 Docker Compose 快速入门229
14.3.1 基本步骤229
14.3.2 入门示例229
14.3.3 工程、服务、容器230
14.4 docker-compose.yml 常用命令230
14.4.1 build 230
14.4.2 command 231
14.4.3 dns 231
14.4.4 dns_search 231
14.4.5 environment 231
14.4.6 env_file 232
14.4.7 expose 232
14.4.8 external_links 232
14.4.9 image 232
14.4.10 links 232
14.4.11 networks 233
14.4.12 network_mode 233
14.4.13 ports 233
14.4.14 volumes 233
14.4.15 volumes_from 234
14.5 docker-compose 常用命令234
14.5.1 build 234
14.5.2 help 235
14.5.3 kill 235
14.5.4 logs 235
14.5.5 port 235
14.5.6 ps 235
14.5.7 pull 235
14.5.8 rm 236
14.5.9 run 236
14.5.10 scale 236
14.5.11 start 236
14.5.12 stop 236
14.5.13 up 236
14.6 Docker Compose 网络设置237
14.6.1 基本概念237
14.6.2 更新容器237
14.6.3 links 238
14.6.4 指定自定义网络238
14.6.5 配置默认网络239
14.6.6 使用已存在的网络239
14.7 综合实战：使用Docker Comose 编排Spring Cloud 微服务240
14.7.1 编排Spring Cloud 微服务240
14.7.2 编排高可用的Eureka Server 243
14.7.3 编排高可用Spring Cloud 微服务集群及动态伸缩245
14.8 常见问题与总结247



第6章 初识Docker 77
6.1 Docker概述 78
6.1.1 什么是Docker 78
6.1.2 Docker的特点 78
6.1.3 Docker与虚拟机的区别 79
6.2 Docker的安装要求 79
6.3 Docker的安装方式 80
6.3.1 在线安装 80
6.3.2 离线安装 82
6.3.3 脚本文件安装 83
6.3.4 安装时的问题及解决方法 84
6.4 Docker的运行机制 85
6.4.1 Docker的引擎 85
6.4.2 Docker的架构 85
6.5 Docker的底层技术 87
6.6 本章小结 87
第7章 Docker的使用 88
7.1 Docker入门程序 89
7.2 Dockerfile介绍 92
7.2.1 Dockerfile基本结构 92
7.2.2 Dockerfile常用指令 93
7.2.3 dockerignore文件 95
7.3 Docker客户端常用指令 96
7.3.1 Docker常用操作指令 96
7.3.2 Docker管理指令 101
7.4 Docker镜像管理 102
7.4.1 Docker镜像管理工具 102
7.4.2 Docker Hub远程镜像管理 103
7.4.3 Docker Registry本地私有仓库搭建 106
7.4.4 Docker Registry本地私有仓库配置 107
7.5 本章小结 112
第8章 Docker中的网络与数据管理 113
8.1 Docker网络管理 114
8.1.1 Docker默认网络管理 114
8.1.2 自定义网络介绍 115
8.1.3 自定义bridge网络 116
8.1.4 容器之间的网络通信 118
8.2 Docker Swarm集群 122
8.2.1 Docker Swarm概述 122
8.2.2 Docker Swarm使用 123
8.3 Docker数据管理 127
8.3.1 Docker数据存储机制 127
8.3.2 Docker数据存储方式 129
8.4 Volumes数据卷管理 129
8.4.1 Volumes数据卷的优势 129
8.4.2 Volumes数据卷使用 130
8.5 本章小结 134