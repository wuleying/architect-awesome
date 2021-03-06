# 《后端架构师技术图谱》

* [Introduction](README.md)

* [数据结构](chapter/1/README.md)
    * [队列](chapter/1/1.md)
        * [java队列——queue详细分析](snapshot/1.1/1.md)
        * [LinkedList、ConcurrentLinkedQueue、LinkedBlockingQueue对比分析](snapshot/1.1/2.md)
    * [集合](chapter/1/2.md)
        * [Java Set集合的详解](snapshot/1.2/1.md)
    * [链表、数组](chapter/1/3.md)
    * [字典、关联数组](chapter/1/4.md)
    * [栈](chapter/1/5.md)
    * [树](chapter/1/6.md)
        * [二叉树](chapter/1/6.1.md)
        * [完全二叉树](chapter/1/6.2.md)
        * [平衡二叉树](chapter/1/6.3.md)
        * [二叉查找树（BST）](chapter/1/6.4.md)
        * [红黑树](chapter/1/6.5.md)
        * [B-，B+，B*树](chapter/1/6.6.md)
        * [LSM 树](chapter/1/6.7.md)
    * [BitSet](chapter/1/7.md)
    
* [常用算法](chapter/2/README.md)
    * [排序、查找算法](chapter/2/1.md)
        * [选择排序](chapter/2/1.1.md)
        * [冒泡排序](chapter/2/1.2.md)
        * [插入排序](chapter/2/1.3.md)
        * [快速排序](chapter/2/1.4.md)
        * [归并排序](chapter/2/1.5.md)
        * [希尔排序](chapter/2/1.6.md)
        * [堆排序](chapter/2/1.7.md)
        * [计数排序](chapter/2/1.8.md)
        * [桶排序](chapter/2/1.9.md)
        * [基数排序](chapter/2/1.10.md)
        * [二分查找](chapter/2/1.11.md)
        * [Java 中的排序工具](chapter/2/1.12.md)
    * [布隆过滤器](chapter/2/2.md)
    * [字符串比较](chapter/2/3.md)
        * [KPM 算法](chapter/2/3.1.md)
    * [深度优先、广度优先](chapter/2/4.md)
    * [贪心算法](chapter/2/5.md)
    * [回溯算法](chapter/2/6.md)
    * [剪枝算法](chapter/2/7.md)
    * [动态规划](chapter/2/8.md)
    * [朴素贝叶斯](chapter/2/9.md)
    * [推荐算法](chapter/2/10.md)
    * [最小生成树算法](chapter/2/11.md)
    * [最短路径算法](chapter/2/12.md)
    
* [并发](chapter/3/README.md)
    * [多线程](chapter/3/1.md)
    * [线程安全](chapter/3/2.md)
    * [一致性、事务](chapter/3/3.md)
        * [事务 ACID 特性](chapter/3/3.1.md)
        * [事务的隔离级别](chapter/3/3.2.md)
    * [锁](chapter/3/4.md)
        * [Java中的锁和同步类](chapter/3/4.1.md)
        * [公平锁 & 非公平锁](chapter/3/4.2.md)
        * [悲观锁 & 乐观锁 & CAS](chapter/3/4.3.md)
        * [ABA 问题](chapter/3/4.4.md)
        * [CopyOnWrite容器](chapter/3/4.5.md)
        * [RingBuffer](chapter/3/4.6.md)
        * [可重入锁 & 不可重入锁](chapter/3/4.7.md)
        * [互斥锁 & 共享锁](chapter/3/4.8.md)
        * [死锁](chapter/3/4.9.md)
        
* [操作系统](chapter/4/README.md)
    * [计算机原理](chapter/4/1.md)
    * [进程](chapter/4/2.md)
    * [线程](chapter/4/3.md)
    * [协程](chapter/4/4.md)
    * [Linux](chapter/4/5.md)
    
* [设计模式](chapter/5/README.md)
    * [设计模式的六大原则](chapter/5/1.md)
    * [23种常见设计模式](chapter/5/2.md)
    * [应用场景](chapter/5/3.md)
    * [单例模式](chapter/5/4.md)
    * [责任链模式](chapter/5/5.md)
    * [MVC](chapter/5/6.md)
    * [IOC](chapter/5/7.md)
    * [AOP](chapter/5/8.md)
    * [UML](chapter/5/9.md)
    * [微服务思想](chapter/5/10.md)
        * [康威定律](chapter/5/10.1.md)
        
* [运维 & 统计 & 技术支持](chapter/6/README.md)
    * [常规监控](chapter/6/1.md)
    * [APM](chapter/6/2.md)
    * [统计分析](chapter/6/3.md)
    * [持续集成(CI/CD)](chapter/6/4.md)
        * [Jenkins](chapter/6/4.1.md)
        * [环境分离](chapter/6/4.2.md)
    * [自动化运维](chapter/6/5.md)
        * [Ansible](chapter/6/5.1.md)
        * [puppet](chapter/6/5.2.md)
        * [chef](chapter/6/5.3.md)
    * [测试](chapter/6/6.md)
        * [TDD 理论](chapter/6/6.1.md)
        * [单元测试](chapter/6/6.2.md)
        * [压力测试](chapter/6/6.3.md)
        * [全链路压测](chapter/6/6.4.md)
        * [A/B Test](chapter/6/6.5.md)
    * [虚拟化](chapter/6/7.md)
        * [KVM](chapter/6/7.1.md)
        * [Xen](chapter/6/7.2.md)
        * [OpenVZ](chapter/6/7.3.md)
    * [容器技术](chapter/6/8.md)
        * [Docker](chapter/6/8.1.md)
    * [云技术](chapter/6/9.md)
        * [OpenStack](chapter/6/9.1.md)
    * [DevOps](chapter/6/10.md)
    * [文档管理](chapter/6/11.md)
    
* [中间件](chapter/7/README.md)
    * [Web Server](chapter/7/1.md)
        * [Nginx](chapter/7/1.1.md)
        * [OpenResty](chapter/7/1.2.md)
        * [Apache Httpd](chapter/7/1.3.md)
        * [Tomcat](chapter/7/1.4.md)
            * [架构原理](chapter/7/1.4.1.md)
            * [调优方案](chapter/7/1.4.2.md)
        * [Jetty](chapter/7/1.5.md)
    * [缓存](chapter/7/2.md)
        * [本地缓存](chapter/7/2.1.md)
    * [客户端缓存](chapter/7/3.md)
        * [Memcached](chapter/7/3.1.md)
        * [Redis](chapter/7/3.2.md)
            * [架构](chapter/7/3.2.1.md)
            * [回收策略](chapter/7/3.2.2.md)
        * [Tair](chapter/7/3.3.md)
    * [消息队列](chapter/7/4.md)
        * [消息总线](chapter/7/4.1.md)
        * [消息的顺序](chapter/7/4.2.md)
        * [RabbitMQ](chapter/7/4.3.md)
        * [RocketMQ](chapter/7/4.4.md)
        * [ActiveMQ](chapter/7/4.5.md)
        * [Kafka](chapter/7/4.6.md)
        * [Redis 消息推送](chapter/7/4.7.md)
        * [ZeroMQ](chapter/7/4.8.md)
    * [定时调度](chapter/7/5.md)
        * [单机定时调度](chapter/7/5.1.md)
        * [分布式定时调度](chapter/7/5.2.md)
    * [RPC](chapter/7/6.md)
        * [Dubbo](chapter/7/6.1.md)
        * [Thrift](chapter/7/6.2.md)
        * [gRPC](chapter/7/6.3.md)
    * [数据库中间件](chapter/7/7.md)
        * [Sharding Jdbc](chapter/7/7.1.md)
    * [日志系统](chapter/7/8.md)
        * [日志搜集](chapter/7/8.1.md)
    * [配置中心](chapter/7/9.md)
    * [API 网关](chapter/7/10.md)
    
* [网络](chapter/8/README.md)
    * [协议](chapter/8/1.md)
        * [OSI 七层协议](chapter/8/1.1.md)
        * [TCP/IP](chapter/8/1.2.md)
        * [HTTP](chapter/8/1.3.md)
        * [HTTP2.0](chapter/8/1.4.md)
        * [HTTPS](chapter/8/1.5.md)
    * [网络模型](chapter/8/2.md)
        * [Epoll](chapter/8/2.1.md)
        * [NIO](chapter/8/2.2.md)
        * [kqueue](chapter/8/2.3.md)
    * [连接和短连接](chapter/8/3.md)
    * [框架](chapter/8/4.md)
    * [零拷贝（Zero-copy）](chapter/8/5.md)
    * [序列化(二进制协议)](chapter/8/6.md)
        * [Hessian](chapter/8/6.1.md)
        * [Protobuf](chapter/8/6.2.md)
        
* [数据库](chapter/9/README.md)
    * [基础理论](chapter/9/1.md)
        * [数据库设计的三大范式](chapter/9/1.1.md)
    * [MySQL](chapter/9/2.md)
        * [原理](chapter/9/2.1.md)
        * [InnoDB](chapter/9/2.2.md)
        * [优化](chapter/9/2.3.md)
        * [索引](chapter/9/2.4.md)
            * [聚集索引, 非聚集索引](chapter/9/2.4.1.md)
            * [复合索引](chapter/9/2.4.2.md)
            * [自适应哈希索引(AHI)](chapter/9/2.4.3.md)
        * [explain](chapter/9/2.5.md)
    * [NoSQL](chapter/9/3.md)
        * [MongoDB](chapter/9/3.1.md)
        * [Hbase](chapter/9/3.2.md)
        
* [搜索引擎](chapter/10/README.md)
    * [搜索引擎原理](chapter/10/1.md)
    * [Lucene](chapter/10/2.md)
    * [Elasticsearch](chapter/10/3.md)
    * [Solr](chapter/10/4.md)
    * [sphinx](chapter/10/5.md)
    
* [性能](chapter/11/README.md)
    * [性能优化方法论](chapter/11/1.md)
    * [容量评估](chapter/11/2.md)
    * [CDN 网络](chapter/11/3.md)
    * [连接池](chapter/11/4.md)
    * [性能调优](chapter/11/5.md)
    * [流式计算](chapter/11/6.md)
        * [Storm](chapter/11/6.1.md)
        * [Flink](chapter/11/6.2.md)
        * [Kafka Stream](chapter/11/6.3.md)
        * [应用场景](chapter/11/6.4.md)
    * [Hadoop](chapter/11/7.md)
        * [HDFS](chapter/11/7.1.md)
        * [MapReduce](chapter/11/7.2.md)
        * [Yarn](chapter/11/7.3.md)
    * [Spark](chapter/11/8.md)
    
* [安全](chapter/12/README.md)
    * [web 安全](chapter/12/1.md)
        * [XSS](chapter/12/1.1.md)
        * [CSRF](chapter/12/1.2.md)
        * [SQL 注入](chapter/12/1.3.md)
        * [Hash Dos](chapter/12/1.4.md)
        * [脚本注入](chapter/12/1.5.md)
        * [漏洞扫描工具](chapter/12/1.6.md)
        * [验证码](chapter/12/1.7.md)
    * [DDoS 防范](chapter/12/2.md)
    * [用户隐私信息保护](chapter/12/3.md)
    * [加密解密](chapter/12/4.md)
        * [对称加密](chapter/12/4.1.md)
        * [哈希算法](chapter/12/4.2.md)
        * [非对称加密](chapter/12/4.3.md)
    * [服务器安全](chapter/12/5.md)
    * [数据安全](chapter/12/6.md)
        * [数据备份](chapter/12/6.1.md)
    * [网络隔离](chapter/12/7.md)
        * [内外网分离](chapter/12/7.1.md)
        * [登录跳板机](chapter/12/7.2.md)
    * [授权](chapter/12/8.md)
        * [RBAC](chapter/12/8.1.md)
        * [OAuth2.0](chapter/12/8.2.md)
        
* [常用开源框架](chapter/13/README.md)
    * [开源协议](chapter/13/1.md)
    * [日志框架](chapter/13/2.md)
        * [Log4j、Log4j2](chapter/13/2.1.md)
        * [Logback](chapter/13/2.2.md)
    * [ORM](chapter/13/3.md)
    * [网络框架](chapter/13/4.md)
    * [Web 框架](chapter/13/5.md)
        * [Spring 家族](chapter/13/5.1.md)
    * [工具框架](chapter/13/6.md)
    
* [分布式设计](chapter/14/README.md)
    * [扩展性设计](chapter/14/1.md)
    * [稳定性 & 高可用](chapter/14/2.md)
        * [硬件负载均衡](chapter/14/2.1.md)
        * [软件负载均衡](chapter/14/2.2.md)
        * [限流](chapter/14/2.3.md)
        * [应用层容灾](chapter/14/2.4.md)
        * [跨机房容灾](chapter/14/2.5.md)
        * [容灾演练流程](chapter/14/2.6.md)
        * [平滑启动](chapter/14/2.7.md)
    * [数据库扩展](chapter/14/3.md)
        * [读写分离模式](chapter/14/3.1.md)
        * [分片模式](chapter/14/3.2.md)
    * [服务治理](chapter/14/4.md)
        * [服务注册与发现](chapter/14/4.1.md)
        * [服务路由控制](chapter/14/4.2.md)
    * [分布式一致](chapter/14/5.md)
        * [CAP 与 BASE 理论](chapter/14/5.1.md)
        * [分布式锁](chapter/14/5.2.md)
        * [分布式一致性算法](chapter/14/5.3.md)
            * [PAXOS](chapter/14/5.3.1.md)
            * [Zab](chapter/14/5.3.2.md)
            * [Raft](chapter/14/5.3.3.md)
            * [Gossip](chapter/14/5.3.4.md)
            * [两阶段提交、多阶段提交](chapter/14/5.3.5.md)
        * [幂等](chapter/14/5.4.md)
        * [分布式一致方案](chapter/14/5.5.md)
        * [分布式 Leader 节点选举](chapter/14/5.6.md)
        * [TCC(Try/Confirm/Cancel) 柔性事务](chapter/14/5.7.md)
    * [分布式文件系统](chapter/14/6.md)
    * [唯一ID 生成](chapter/14/7.md)
        * [全局唯一ID](chapter/14/7.1.md)
    * [一致性Hash算法](chapter/14/8.md)
    
* [设计思想 & 开发模式](chapter/15/README.md)
    * [DDD(Domain-driven Design - 领域驱动设计)](chapter/15/1.md)
        * [命令查询职责分离(CQRS)](chapter/15/1.1.md)
        * [贫血，充血模型](chapter/15/1.2.md)
    * [Actor 模式](chapter/15/2.md)
    * [响应式编程](chapter/15/3.md)
    * [DODAF2.0](chapter/15/4.md)
    * [Serverless](chapter/15/5.md)
    
* [项目管理](chapter/16/README.md)
    * [架构评审](chapter/16/1.md)
    * [重构](chapter/16/2.md)
    * [代码规范](chapter/16/3.md)
    * [RUP](chapter/16/4.md)
    * [看板管理](chapter/16/5.md)
    * [SCRUM](chapter/16/6.md)
    * [极限编程](chapter/16/7.md)
    * [敏捷开发](chapter/16/8.md)
    * [结对编程](chapter/16/9.md)
    
* [通用业务术语](chapter/17/README.md)

* [技术趋势](chapter/18/README.md)

* [架构师素质](chapter/19/README.md)