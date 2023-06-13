 <center>
     <h1>张玮</h1>
 </center>

## 个人信息 

* 性 别：男&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;年 龄：23  
* 手 机：13357810972 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;    邮 箱：1162239341@qq.com    
* 专 业：通信工程 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 岗 位：Java开发工程师

## 工作及教育经历
       
* 南京理工大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2021.9~至今&emsp;&emsp;&emsp;&emsp;&ensp;&ensp; 通信工程-研究生         
* 南京信息工程大学&emsp;&emsp;&emsp;&emsp;&emsp;2017.9~2021.6&emsp;&emsp;&emsp;&emsp; 电子信息工程-本科  

## 专业技能

* 熟练使用 java，掌握python，了解 C++,PHP 等编程语言；
* 熟悉网络编程和多线程编程，对TCP/IP，HTTP等网络协议有一定的理解，并了解XML和HTML语言；
* 熟练使用MySQL，熟悉MySQL索引；
* 熟悉Redis的使用，熟悉持久化和过期淘汰策略；
* 熟练使用Spring Boot、Spring、Mybatis等常用框架；
* 对数据结构、算法有一定了解；
* 了解计算机基础，如计算机网络、操作系统。

## 项目经历

1. 校园兼职论坛 - 独立开发 - 202301 - 202302
    * 技术选型：SpringBoot + MySQL + Redis + Kafka + Elasticsearch + Spring Security；
    * 使用Redis存储登录 ticket 和验证码，解决分布式 session 问题；
    * 构建 Trie 数据结构，实现对发表帖子评论的敏感词过滤；
    * 使用 Redis 的 set 实现点赞，zset 实现关注，HyperLogLog 统计UV，Bitmap 统计DAU；
    * 使用 kafka 实现点赞关注后的异步系统通知和帖子、评论数据异步上传到ES服务器；
    * 使用 Elasticsearch 对帖子搜索功能进行重构，通过IK中文分词器增加增量索引和全局索引，实现搜索关键词高亮显示等功能；
    * 使用 Spring Security 用于管理项目中的登录权限，从而实现置顶、加精、删除；
    * 技术难点之一：热帖排行模块，使用 Redis 缓存 score 值，并使用 Quartz 定时更新热帖排行榜。
2. 校园点评 - 独立开发 - 202302 - 202304
    * 功能：实现了发布并查看商家，探店，点赞，关注等功能，业务可以帮助商家从校园引流，增加曝光度，也可以为用户提供查看附近促销活动的消费场所；
    * 包括登录模块、查询商户模块、优惠券秒杀模块、博客模块、签到模块和订阅模块。
    * 技术选型：SpringBoot + MySql + MyBatis-Plus + RabbitMQ + Redis；
    * 商户查询使用 Redis 缓存,并解决缓存穿透、缓存击穿和缓存雪崩问题；
    * 用 Redis 缓存库存量和CAS解决优惠券超卖问题、采用set判断实现一人一单，Redis 分布式锁解决集群环境下多线程问题；
    * 将每一条秒杀的请求存入消息队列 RabbitMQ 中，将收到的下订单请求一个个的写入数据库中，大大缓解了数据库的连接压力。


## 获奖经历
* 2021年研究生一等奖学金；
* 2022年第八届中国国际“互联网+”大学生创新创业大赛产业赛道江苏省二等奖；
* 申请了两篇发明专利。

## 其他信息 
* 有钻研技术的热情和充沛精力；
* 具备较好的沟通能力和团队协同能力，善于独立思考并反思总结；
* 性格开朗，喜欢运动，爱好健身、骑行，健身五年，骑行百公里。 
