# MyRedis
1. Redis是什么？
    * 完全开源免费的，用C语言编写的，是一个单线程，高性能的（Key-Value）的内存数据库，基于内存运行并支持持久化的nosql数据库
2. Redis能干嘛？
    * 主要是用来做缓存，但不仅仅只用做缓存，比如redis的计数器生成分布式唯一主键，Redis实现分布式锁，队列，会话缓存。
3. Redis怎么玩？
4. 下载网站
- https://redis.io/download
- https://github.com/tporadowski/redis/releases

互联网需求的3高

- 高并发

- 高可扩

- 高性能

传统的ACID

- 原子性
- 一致性
- 独立性
- 持久性

CAP

- C-强一致性
- A-可用性
- P-分区容错性

Redis: 远程字典服务器

切换数据库

```
数据库默认16个，数据库是0到15
select 2  # 切换到第三个数据库
```

查看数据库中几个key

```
dbsize
keys * # 查看所有的key
```

清除当前库

```
flushdb
```

清除所有库

```
flushall
```

Redis的五大数据类型

```
字符串(string)
列表(list)
集合(set)
哈希(hash)
有序集合zset(sorted set)
```











# Windows的Redis

开启服务器

```
redis-server.exe redis.windows.conf
```

客户端访问服务器

```
redis-cli.exe -h 127.0.0.1 -p 6379
```



# Linux的Redis



































