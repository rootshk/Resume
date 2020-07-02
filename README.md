# 个人简介-JAVA 工程师
- 姓名：沈鸿铿
- 性别：男
- 毕业院校：广州华夏职业学院
- 学历：大专
- 户籍地：广东茂名
- 期望地：广州

# 联系方式
- 手机：13288993990
- Email：hk374790498@gmail.com 


# 工作经历
## 信用生活(广州)智能科技有限公司-后端(2020-06 ~ 至今)

### 卡核心系统后台开发(Java)
* 贷中系统研发、维护及实施
```
开发技术: SpringBoot, Redis, MySql, Oracle, Swagger2, Apollo, SpringCloud...
```

## 广州范普科技有限公司-后端(2019年9月 ~ 2020-03月)

### 桌面云邮件后台开发 (Java)
* 项目通过邮件拦截转发, 使企业内网邮件可在外网无缝查看
* 通过拦截内部邮件, 达到外网可见的同时, 实现隐私安全(隐藏邮件细节)
* 负责项目: 0到1的基础框架搭建, 数据库表设计, AOP切面开发, 第三方接口联调等
* 负责模块: 域名白名单, 敏感词, 拦截统计, 邮件记录, 邮件发送, 用户鉴权
* 使用MyBatis-Plus作为持久层组件, 完成数据持久化前的自动处理
* 利用Spring的HandlerMethodArgumentResolver使开发者用入参的方式获取当前用户, 写出优雅代码
* 由于MyBatis需要编写大量Mapper, 故自行分装一套基于对象的动态查询工具类, 提高代码可读性
* 分装BaseEntity实体类, BaseService等基础接口, 极大减少代码量(利用泛型)
* 通过实现HandlerInterceptorAdapter, 拦截前后台服务请求, 对请求进行日志记录, 输出, 及权限过滤
* 通过使用MQ, 规避邮件发送时由于存在CPU处理密集型任务导致响应时间过长的问题
* 利用@ControllerAdvice实现了代码内部直接throw亦可返回统一全局错误码
* 对每个具体功能编写针对性的@Test单元测试, 保证代码的稳定可靠
```
开发技术:  SpringBoot, Redis, MySQL, Swagger2, MyBatis-Plus, Netty, FastJSON...等
```

### SAAS商城后台开发 (Java)
* 该项目是一个用于实现线下门店美瞳试装到线上购买的SAAS商城
* 负责模块: 商品, 订单, 购物车, 支付, 促销, 文章, 版本控制, 权限管理等
* 使用Spring Data JPA为持久层, 利用EmptyInterceptor实现入库出库时的多商户查询
* 项目使用Cloud Gateway实现多服务转发
* 使用ApplicationContext.getMessage实现国际化
* 利用@Convert实现bean到sql的无感知切换
* 利用AOP实现多商户动态查询
* 负责项目: 数据原型开发, 逻辑实现, 测试优化及Elasticsearch搜索逻辑实现
* 平台包括试装程序及商城程序, 支持分应用授权
* 对每个具体功能编写针对性的@Test单元测试, 保证代码的稳定可靠
```
开发技术: SpringBoot, Redis, PostgreSQL, Swagger2, Spring Data JPA, RabbitMQ, Elasticsearch等
项目亮点：两个程序之间的'信息互通'通过RabbitMQ实现, 原本多达7张表的SQL查询通过引入ES解决
```

### 康肤医美小程序后台开发 (Java)
* 该项目是一个主沟通,重服务的线上商城项目
* 负责项目数据原型开发, 逻辑实现, 测试优化
* 为小程序端提供实时聊天API及商城服务支持
```
开发技术: SpringBoot, Redis, PostgreSQL, Swagger2, Spring Data JPA, WebSocket等
项目亮点：聊天系统使用WebSocket降低外部MQ依赖, 降低后期维护成本
```

### 会议预约小程序开发 (Java)
* 该项目是科技园孵化器为入驻客户提供的一体化管理软件
* 负责项目数据原型开发, 逻辑实现, 测试优化, 前后端分离的API接口
* 房源库存精准限制及签到打卡功能
```
开发技术: SpringBoot, Redis, PostgreSQL, Swagger2, Spring Data JPA等
项目亮点：会议室单间库存采用独立表结构保证查询性能
```

### 微信公众号抽奖类引流项目开发 (Java)
* 此项包含了亚马逊中国及中邮的两个公众号拉新活动
* 负责项目数据原型开发, 逻辑实现, 测试优化, 前后端分离的API接口
* 活动拉新用户新增5000+
```
开发技术: SpringBoot, Redis, PostgreSQL, Swagger2, Spring Data JPA等
项目亮点：支持分渠道, 分奖池, 分概率的抽奖设置,
利用Redis原子性保证库存防止超售, 通过Redis压栈出栈进行请求削峰
```

## 广州福苷禄商贸有限公司-后端( 2018年3月~2019年07月)

### 商城支付支撑系统 (Java)
* 该项目为公司基础支持系统, 为商城及其他服务提供 收款/核算/第三方支付 整合为一体的聚合服务
* 项目底层框架搭建,编码及优化, 属于独立开发
* RESTful接口及清算系统的开发
* 业务系统的对接联调, 稳定性测试
```
开发技术: SpringCloud, Redis, MySQL, Swagger2, Spring Data JPA
项目亮点：支持多支付插件集成, 水平扩展性强, 同时支持单体/集群部署
```

### 福禄仓商城(https://shop.fulucang.com) (Java)
* “福禄仓商城”是一个面向大众,价格亲民的在线B2C商城
* (包括APP, 小程序, WEB端)负责数据层,逻辑层,处理后端部分开发工作,配合构架师完成分布式RESTful服务搭建
* 保障商城订单流程的正常无误, 各支付插件的实现与对接, 主用事务确保订单支付完成
* hibernate-search与elasticsearch整合实现分布式搜索
* 项目前期负责前后端界面编写测试, 小程序前后端开发测试与发布.
```
开发技术: Spring Cloud, Spring Boot, Redis, MySQL, WebSocket, Elasticsearch, MongoDB
开发阻碍: 项目转型前由于为实现前后端分离, 导致项目转型时出现各种问题
比如权限控制, 则通过OAuth 2 / JWT解决
项目亮点：当前商城用户量: 5000+, 峰值并发500+
```

### 茶极客小程序(在微信中搜索该小程序即可) (Java)
* “茶极客”是一款提供线上预约,线下聚会的约茶小程序
* 在原有的构架基础上定制开发适应业务代码,及前后端分离API的开发
```
开发技术: SpringBoot, Redis, MySQL, WebSocket, Elasticsearch
开发阻碍: 原框架冗余过多, 功能点不匹配, 整合不到位等问题, 后通过服务化降低耦合
项目亮点：轻量级, 相应快速
```

## 广州苍牙网络科技有限公司-后端小组组长(2017年7月 ~ 2018年2月)

### 网络多人棋牌项目 (Java)
* “网络多人棋牌”是集多个玩法于一体得微信网页游戏,负责后台数据处理及结果展示
* 负责数据层,逻辑层,处理后端部分开发工作,分布式rpc服务搭建
* 负责进行缓存处理,对接又进行改进优化,主用redis缓存
```
开发阻碍：功能实现需要数据库多表联查，后采取inner join方法解决
项目亮点：使用了Redis缓存，解决并发~~~~问题
```
### 大抽奖项目 (Java)
* “大抽奖”是一款休闲娱乐转盘微信网页游戏,负责后台数据处理及结果展示
* 负责数据层,逻辑层,处理后端部分开发工作,分布式rpc服务搭建
* 负责进行缓存处理,对接又进行改进优化,主用redis缓存
```
开发阻碍：不同的抽奖概率需要实时变化，后采取Redis解决
项目亮点：在线人数3000+
```

# 教育情况

## 广州华夏职业学院(2015年9月 ~ 2018年6月)

### 大专 - 计算机网络 （主修课程）
* 计算机网络应用
* JAVA
* 数据库基础
* PHP
* Linux
* 网页设计

# 开源项目和作品

## 开源项目(托管于Github中: https://github.com/rootshk)
  - [review-utils](#): 商城评论导入工具(未开源)(Golang语言)
  - [push-server](https://roothk.top)：消息分发服务脚手架(开发构建中)
  - [url-shortener](https://github.com/rootshk/url-shortener-java)：短地址服务
  - [wechat-MiniCode](https://github.com/rootshk/wechatMiniProgramCode)：微信小程序分享二维码生成服务
  - [local-ddns](https://github.com/rootshk/ddns)：动态DNS解析服务
  - [Elasticsearch-Dict](https://github.com/rootshk/elasticsearch-dict-util)：Elasticsearch远程IK字典更新工具
  - [SpringCloud](https://github.com/rootshk/microservices)：个人分布式服务
  - [dding](https://github.com/rootshk/dding)：远程钉钉打卡服务
  - [weather](https://github.com/rootshk/weather)：天气页面
  - [web-code](https://github.com/rootshk/web-oss)：个人站点源码
  - [SSR-System](https://github.com/rootshk/shadowsocksr-code-systen)：自用SSR后台
  

## 技术文章
- [Blog](https://roothk.top) : 博客https://roothk.top
- [Ngrok方针](http://oss.roothk.top/ngrok/index.html) ：自建ngrok使用指南
- [Ngrok方针](https://www.roothk.top/code/ngrok-help) ：自建ngrok使用指南-博客版
- [GitHub指南](https://www.roothk.top/code/github-help)：初学者的入门指南
- ...

# 技能清单
以下均为我熟练使用的技能

- Web开发：JAVA/PHP/HTML/Golang/WebSocket/JS/Vue
- 技术框架：Spring Cloud/Spring Boot/Spring Data JPA/Spring MVC/Hibernate/Mybatis
- 运行容器: Docker
- 持续集成: Jenkins
- 开发工具：IntelliJ IDEA/VSCode
- 前端框架：Materialize/HTML5/Vue.js
- 数据库相关：MySQL/MariaDB/Redis
- 版本管理工具：Git/SVN
- 单元测试：JUnit
- 云和开放平台：AWS/微信应用开发
      
---      
      
# 联系方式

- 手机：13288993990/13035816039
- Email：hk374790498@gmail.com
