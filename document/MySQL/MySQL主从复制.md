##数据库

    容量问题、一致性问题、故障转移、分库分表、分布式事务、XA/柔性事务

###主从复制原理

#### 主库写 binlog
#### 从库 relay log
    
    1、异步复制

    2、半同步复制，保证Source和Replica最终一致 至少有一个从库保证数据同步

    3、组复制：基于分布式Paxos协议实现组复制
    
    
    a
    