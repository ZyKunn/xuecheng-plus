# 51学成在线项目
- 技术栈：Nginx、SpringBoot、Spring Cloud、Spring Security、MinIO、MyBatis-Plus、MQ、Redis、Elasticsearch
- 共分为七个模块

## 前端资源：
网盘链接：https://pan.baidu.com/s/1XSdezXLuC3UdaxAqjjJ2wg?pwd=2077 提取码：2077

## 项目基础环境搭建：
- 对应的文章地址：https://zykunn.github.io/MyBlog/notes/project/02/%E7%AC%AC1%E7%AB%A0-%E9%A1%B9%E7%9B%AE%E4%BB%8B%E7%BB%8D_%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BAv3.1/
## 内容管理模块
- 对应的文章地址：https://zykunn.github.io/MyBlog/notes/project/02/%E7%AC%AC2%E7%AB%A0-%E5%86%85%E5%AE%B9%E7%AE%A1%E7%90%86%E6%A8%A1%E5%9D%97v3.1/
- 前置知识SpringCloud的相关笔记：https://zykunn.github.io/MyBlog/notes/microservices/01/day01-SpringCloud01/
## 媒资管理模块
- 这部分采用MinIO构建分布式文件系统
- 对应的文章地址：https://zykunn.github.io/MyBlog/notes/project/02/%E7%AC%AC3%E7%AB%A0-%E5%AA%92%E8%B5%84%E7%AE%A1%E7%90%86%E6%A8%A1%E5%9D%97v3.1/
## 课程发布模块
- 对应的文章地址：https://zykunn.github.io/MyBlog/notes/project/02/%E7%AC%AC4%E7%AB%A0-%E8%AF%BE%E7%A8%8B%E5%8F%91%E5%B8%83v3.1/
- 这部分最后还用到了ElasticSearch完成搜索结果高亮，但是课程中讲的不是很详细，我的博客中也有详细介绍ElasticSearch的笔记：https://zykunn.github.io/MyBlog/notes/microservices/01/day05-Elasticsearch01/
## 认证授权模块（解决微信登录）
- 对应的文章地址：https://zykunn.github.io/MyBlog/notes/project/02/%E7%AC%AC5%E7%AB%A0-%E8%AE%A4%E8%AF%81%E6%8E%88%E6%9D%83v3.1/
## 选课学习模块
- 这部分还接入了支付宝的沙箱支付环境，可以模拟真实的用户扫码支付
- 支付结果也支持基于RabbitMQ实现异步消息通知处理 
- 对应的文章地址：https://zykunn.github.io/MyBlog/notes/project/02/%E7%AC%AC6%E7%AB%A0-%E9%80%89%E8%AF%BE%E5%AD%A6%E4%B9%A0v3.1/
- RabbitMQ的前置知识也可以参阅我这篇文章：https://zykunn.github.io/MyBlog/notes/microservices/01/day04-MQ/
## 项目优化
- 这部分主要是用Redis来缓存一些热点数据，粗略介绍了一点缓存穿透、缓存雪崩、缓存击穿和分布式锁的实现
- 对应的文章地址：https://zykunn.github.io/MyBlog/notes/project/02/%E7%AC%AC8%E7%AB%A0-%E9%A1%B9%E7%9B%AE%E4%BC%98%E5%8C%963.1/
- 但是这里的Redis讲解很潦草，建议看我这篇文章深入学习一下Redis：https://cyborg2077.github.io/2022/10/22/RedisPractice/
