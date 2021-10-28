# java高级工程师、技术专家、架构师等职位面试题
 
仅供学习与面试使用，写的不好的地方欢迎大家指出。

> 注1：基础的内容或者大家都熟知的经常会被问到的东西去看[javaguide](https://github.com/Snailclimb/JavaGuide)哥的文章就够了，当然本人能力有限不可能把各个方面都研究的很透彻，如果有错误的地方，欢迎指出，如果您也有面试方面的东西可以一块分享。


持续更新中...

# 目录
### 1. java篇
   - #### 基础内容
     - [ClassLoader 和 Class.forName() 的区别](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/java%E5%9F%BA%E7%A1%80/classloader%E5%92%8Cclassforname.md)
     - [java 动态代理过程](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/java%E5%9F%BA%E7%A1%80/%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86.md)
     - [java 8 新特性面试点](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/java%E5%9F%BA%E7%A1%80/java8.md)
     

   - #### 集合模块
      - [HashMap与HashSet](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/collection/HashMap.md)
      - [LinkedHashMap 与 LinkedHashSet](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/collection/LinkedHashMap.md)
      - [TreeMap 和 TreeSet](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/collection/TreeMap.md)
      - [ConcurrentHashMap、ConcurrentSkipListMap、CopyOnWriteArrayList](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/collection/ConcurrentHashMap.md)
   - #### 同步，并发等
      - 锁/并发控制器:
        - [synchronized](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/sync/synchronized.md)，
        - [AbstractQueuedSynchronizer（AQS）、ReentrantLock、ReentrantReadWriteLock、compareAndSwap(CAS)](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/sync/aqs.md)
      - [线程、线程池ThreadPoolExecutor](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/sync/ThreadPoolExecutor.md)
      - [ThreadLocal](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/sync/ThreadLocal.md)
   - #### jvm
     - [jvm内存结构](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/jvm/jvmstruct.md)
     - [java内存模型](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/jvm/jvmmodel.md)
     - [垃圾收集算法和垃圾收集器（CMS，G1，ZGC）](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/jvm/gc.md)
     - [类结构、类加载过程、类加载器（双亲委派模型）](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/jvm/class.md)
     - [JVM 参数，调优，OOM问题排查](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/jvm/param.md)
     - [一个Java对象占用多大内存](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/java%E5%9F%BA%E7%A1%80/object.md)

2. ### 框架篇
   - #### spring
      - [spring IOC，AOP，spring bean 生命周期和作用范围，springboot 启动过程、自动装配过程，如何实现自定义注解、自定义注解方法返回支持哪些类型，注解如何生效的，BeanFactory，ApplicationContext，FactoryBean区别 ](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/spring/springboot.md)
      - [springboot 内置容器Tomcat、Jetty、undertow、Reactor Netty](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/spring/properties.md)
   - #### jpa/hibernate/mybatis
     - [jpa 实现原理？如何将方法翻译为sql语句的？](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/spring/jpa.md)
     - [jpa save 方法如何识别是insert还是 update？](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/spring/jpasave.md)
     - hibernate
     - mybatis
   - #### 消息队列kafka，rocketMQ，rabbitmq
     - [消息顺序性如何保证、重复消息问题、消息丢失问题、消息堆积问题](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/mq/mq.md)
     - [kafka，rocketMQ，rabbitmq 集群](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/mq/info.md)
   - #### zookeeper
     - [zookeeper 数据结构、Paxos算法，Zab协议，分布式锁，集群](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/mq/zk.md)

   - #### redis
     - [redis 数据类型及使用场景，如何批量删除key，布隆过滤器等](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/redis/redis.md)
     - [单线程速度快的原因、持久化机制（RDB、AOF）](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/redis/rdbaof.md)
     - [过期时间TTL说明，内存淘汰机制（LRU，LFU）](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/redis/ttl.md)
     - [缓存穿透、缓存雪崩、缓存击穿，数据库和缓存一致性问题是如何解决？](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/redis/other.md)
     - [redis 分布式锁，锁的续期问题等（redisson），各分布式锁对比](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/redis/lock.md)
     - [主从模式、哨兵模式、集群模式（cluster）](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/redis/cluster.md)
     
   - #### elasticsearch
     - [基础概念，文档搜索和写入过程，删除或更新过程](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/es/es.md)
     - [支持的数据类型](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/es/type.md)
     - [倒排序索引原理](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/es/sort.md)
     - [深度分页](https://gitee.com/javajov/java-senior-engineer-interview/blob/master/es/page.md)
     - 集群
   - ### clickhouse
     - clickhouse 是什么？
     - 数据库、elasticsearch、clickhouse 三种存储结构对比

3. ### 数据库篇
   - #### 索引
     - 索引结构，为什么是B+树，聚集索引，普通索引
     - sql执行过程，sql优化，什么情况下索引会失效
   - #### 事务隔离级别
     - 并发事务的问题（脏读、幻读、不可重复读）
     - 事务的隔离级别
     - mysql如何解决不可重复读
   - 分库分表
   - 分布式事务
     - cap、base 理论，分布式事务解决方案等

4. ### 微服务
   - #### dubbo
     - 组件，核心原理
     - 负载均衡策略
     - 拒绝策略
   - #### spring cloud
     - 组件，核心原理
     - 与dubbo对比
   - #### hystrix/sentinel
     - 熔断、限流、降级
5. ### 算法篇
   - LRU 算法
   - 回文字符串判断
   - 公共子串
6. ### 网络篇
   - Http，https，tcp，udp
   - tcp如何保证可靠性
   - tcp粘包问题

7. ### 其他
   - linux 常用命令
   - netty
   - IO模型
   - HBase
   - Spark
   - docker
   - Kubernetes

8. ### 代码审查如何优化代码等

