### JAVA ORM

#### Minidao

MiniDao 是一款超级轻量的JAVA持久层框架，具备Mybatis一样的标签和SQL灵活性。最大优点：可无缝集成Hibernate项目，支持事务统一管理，有效解决Hibernate项目，实现灵活的SQL分离问题。

#### EBean

- 原始SQL：可方便的使用原始sql，并以懒加载的方式返回全属性的bean。
- 结果分页：使用findRowCount()或findPageList()很容易处理结果分页。
- 支持大型查询：使用findIterate()分批处理大量数据，不必全部加载到内存中。
- 批量插入：通过设置JDBC batch size可以调整每个事物中的批量插入数。
- DB加密：使用@Encrypt注解可以透明的实现DB加密。
- 支持JSON：内置JSON支持。
- 自动查询优化：支持“自动抓取”(autofetch)，查询自动调优。
- 无状态更新：填充一个bean对象，然后不必查询直接更新数据，这对于支持REST很有用。
- 批量更新/删除：可以使用批量/删除更新语句，大大提高效率。
- 事件监听：Ebean从版本4.0.1开始支持
- 读审计：ReadAudit功能是当数据被读取时记录日志（可用于审计）。


- 二级缓存：可显著提升性能。

[参考文章](http://blog.csdn.net/jsshaojinjie/article/details/52129740)

### 分库分表

#### sharding-jdbc

Sharding-JDBC是一个开源的分布式数据库中间件，它无需额外部署和依赖，旧代码迁移成本几乎为零。Sharding-JDBC作为面向开发的微服务云原生基础类库，完整的实现了分库分表、读写分离和分布式主键功能，并初步实现了柔性事务。

[优点](http://shardingjdbc.io/index_zh.html)：

- 分库分表、读写分离（主从）
- TCC事务
- 分布式主键（以时间序列）
- 可适用于任何基于java的ORM框架、连接池
- 目前支持MySQL，Oracle，SQLServer和PostgreSQL

![](/var/folders/jq/xmm7f3ds2ql5h2k85hz904rh0000gn/T/ro.nextwave.Snappy/ro.nextwave.Snappy/64BA05E9-921F-4C94-B07C-6A093E8994F6.png)

[GitHub](https://github.com/shardingjdbc)

[infoq](http://www.infoq.com/cn/news/2016/01/sharding-jdbc-dangdang)

### 数据库连接池

##### Druid

##### HiKariCP

### Web测试工具

#### 单元测试

Jest

AVA

Mocha

Karma

#### 集成测试

Enzyme

#### 功能测试

WebDriverIO

Nightwatch

Storybook

Gremlins.js

#### 服务端测试

K6

SuperTest

### 可持久DB

##### RocksDB 

RocksDB 是一个来自 Facebook 的可嵌入式的支持持久化的 key-value 存储系统，也可作为 C/S 模式下的存储数据库，但主要目的还是嵌入式。RocksDB 基于 LevelDB 构建。

##### Ceph

分布式存储系统

##### Hazelcast

缓存数据库、以SQL的方式获取数据、分布式、key-value、内存数据库

##### InfluxDB

着力于高性能地查询与存储时序型数据。InfluxDB被广泛应用于存储系统的监控数据。

提供了一个类似于SQL的查询语言并且一系列内置函数方便用户进行数据查询

### 分布式系统监视

##### Zabbix

Zabbix 是一个基于 Web 界面的提供分布式系统监视以及网络监视功能的企业级的开源解决方案。

### 调用框架

##### Aibton-framework

基于 Spring 的统一 API 调用框架，规范开发，让项目更好维护，代码复用率更高。集成了基础开发工具类，编码更简单。基本上零配置，直接使用，与 Spring 搭配更简单哦。

### 微服务框架

##### jboot

Java微服务框架

##### Spring boot

Java微服务框架

### 文档工具

##### ShowDoc

### 可视化系统开发工具集 

##### X-Series

#### 在线代码编辑器

##### CodeMirror

### 代码质量

##### sonarqube

代码质量工具，具有代码重复率，Bug率，漏洞等检查功能

### Mock工具

##### easy-mock

大搜车出品的基于前端mock调用数据工具，可以提高前端开发效率

### 机器学习

##### xgboost

分布式梯度增强库，秘诀就在于算法能并行计算、近似建树、对稀疏数据的有效处理以及内存使用优化。

XGBoost 支持在多台机器上进行分布式训练，包括 AWS，GCE，Azure 和 Yarn 集群。可以与 Flink，Spark 和其他云数据流系统集成。

XGBoost 可以处理回归、分类和排序等多种任务。由于它在预测性能上的强大且训练速度快，XGBoost 已屡屡斩获 Kaggle 各大竞赛的冠军宝座。