### **苍穹外卖——总结**

#### **概述**

从开始项目到结束，共计花了14天时间。

最开始3天学习了git的基本使用，创建本地仓库、和远程仓库建立连接、将项目提交推送至远程仓库。

11天用于学习苍穹外卖本身：

除了基本的crud之外（商品管理、地址簿管理），

**学习**：订单相关业务逻辑（订单状态管理、来单提醒、客户催单、再来一单），redis缓存营业状态、以及搭配spring cache小程序端分类商品数据，spring task定时处理订单，websocket建立长连接、实现客户向管理端推送订单提醒消息，httpclient调用外部API，POI实现读写生成excel报表数据。

**复习**：条件分页查询，登录下发jwt令牌，拦截器的注册、拦截请求，threadlocal管理当前用户id，AOP统一填充公共字段，Spring IOC容器管理bean对象，引入外部资源注册为bean对象，阿里云OSS上传图片，maven构建项目。

**待学习**：内网穿透、swagger接口测试



#### **技术栈**

用户层：Nodejs, Vue, ElementUI, 微信小程序, Apache Echarts

网关层：Nginx

应用层：SpringBoot, SpringMVC, SpringTask, httpclient, Spring Cache, JWT, 阿里云OSS, Swagger, POI, Web Socket

数据层：mysql, redis, mybatis, pagehelper, spring data redis

工具：git, maven, junit, apifox
