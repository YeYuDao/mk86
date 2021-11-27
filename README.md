# mk86
Spring Cloud+Vue前后端分离开发企业级在线视频系统
Spring Cloud+Vue前后端分离开发企业级在线视频系统
[![下载地址](https://img.mukewang.com/szimg/5fced78f0970285305400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 课程导学与准备工作 

#### 本章主要介绍为何要带大家学习一个前后端分离的企业级在线视频系统课程，通过本课程学习不仅会掌握Spring Cloud+Vue前后端分离架构，还会掌握到视频文件的处理，包括文件上传、断点续传、文件存储、视频点播、视频加密等核心技术，之后会为大家介绍本课程内容具体安排，最后给出如何学好这门课程的一些学习建议。希望大家...
1-1 课前必读（不看会错过一个亿）

1-2 课程介绍及学习指导 (15:46)

1-3 线上环境体验 (10:38)

1-4 代码生成器初体验 (14:38)

1-5 开发环境准备 (10:58)

1-6 总体架构介绍 (07:33)

1-7 如何利用源码进行学习 (09:50)


### 第2章 使用Maven搭建SpringCloud项目

#### 本章将介绍使用Maven搭建SpringCloud微服务项目，学习微服务核心组件：注册中心Eureka和路由Gateway。
2-1 使用Eureka搭建注册中心 (14:36)

2-2 搭建业务模块-system (18:58)

2-3 搭建路由模块-gateway (13:05)


### 第3章 SpringBoot项目技术整合

#### 本章将介绍单个SpringBoot的纯后端应用的搭建，集成Mybatis框架及代码生成器，并集成热部署DevTools，学习单个应用的环境搭建及提高开发效率的准备。
3-1 集成持久层框架Mybatis (22:31)

3-2 项目优化 (16:42)

3-3 搭建服务模块-server (20:20)

3-4 集成mybatis generator (18:33)


### 第4章 使用Vue cli 4搭建管理控台

#### 本章将介绍Vue cli和bootstrap的使用。Vue是MVVM框架，其代码结构类似于Angular、微信小程序。Bootstrap是一个响应式框架，一套代码可适应PC，手机屏幕。本章使用Vue cli 4 + Bootstrap 3搭建控台管理应用，学习单页面应用搭建及响应式设计。...
4-1 使用vue cli创建admin项目 (14:13)

4-2 集成bootstrap后台管理模板ace (25:30)

4-3 集成路由vue-router (18:04)

4-4 控台欢迎页面开发 (26:33)


### 第5章 单表管理功能前后端开发

#### 本章将演示控台单表增删改查的前后端开发，重点学习前后端数据交互，Vue ajax库axios的使用，使用Vue自定义组件制作分页组件，Mybatis分页插件pagehelper的使用等功能。介绍常用的公共组件的使用，包括前端确认框、提示框、等待框，后端复制工具类、统一日志AOP等。...
5-1 大章列表查询功能开发1 (21:27)

5-2 大章列表查询功能开发2 (19:48)

5-3 大章列表查询功能开发3 (22:10)

5-4 分页功能开发 (19:28)

5-5 前端分页组件的使用 (20:51)

5-6 增加新增大章功能 (27:04)

5-7 修改删除大章功能 (19:14)

5-8 集成前端通用组件 (23:42)

5-9 代码优化 (24:50)


### 第6章 通用代码生成器开发

#### 本章将演示代码生成器的制作，学习模板引擎freemarker的使用。通过代码生成器可以快速生成dto、service、controller和vue界面代码，再配合上mybatis generator，可以快速完成单表的增删改查管理功能，极大的提高开发效率。另外，本章的知识也可应用于静态页面生成、导出复杂excel等涉及文件生成的场景。...
6-1 代码生成器原理介绍 (06:54)

6-2 controller层和service层代码生成 (16:16)

6-3 dto层代码生成 (14:56)

6-4 前端vue界面代码生成 (19:30)

6-5 字段校验和通用字段的处理 (22:25)

6-6 前端枚举代码生成 (24:40)

6-7 生成器综合示例 (15:16)

6-8 生成器升级作业 (04:52)


### 第7章 核心业务功能开发

#### 本章将演示核心业务功能开发，包括课程、章、节、分类的管理功能，学习前端页面跳转及参数传递，Vue过滤器，前端树形展示插件zTree，富文本框的使用，Spring事务，通用排序功能解决方案等。
7-1 课程管理功能开发 (29:27)

7-2 课程时长的保存和显示 (18:51)

7-3 分类管理功能开发 (27:14)

7-4 课程和分类关联保存和显示 (27:19)

7-5 课程内容功能开发 (17:32)

7-6 课程代码优化 (18:25)

7-7 讲师管理功能开发 (21:35)

7-8 分类管理如何改成用无限级树的方式


### 第8章 文件上传功能开发

#### 本章将演示文件模块的开发，会使用SpringBoot + Vue完成文件上传功能，上传的图片支持实时预览显示。文件上传是系统操作中常见的功能，文件有大有小，不可避免带来带宽的问题，单独的文件模块很好的解决这个问题。
8-1 完成基本的文件上传功能 (17:08)

8-2 讲师头像的保存与显示 (09:49)

8-3 文件上传组件开发1 (11:27)

8-4 文件上传组件开发2 (12:42)

8-5 增加文件管理功能1 (11:16)

8-6 增加文件管理功能2 (11:15)

8-7 文件上传组件的使用 (16:22)

8-8 作业讲解：课程内容中增加文件管理 (20:07)


### 第9章 大文件断点续与极速秒传

#### 本章将在上一章的基础上增加大文件断点续传功能。作为一个视频网站，一个文件从几十M到上G，上传一个大文件受网络影响很大，一次上传成功的几率很小，为此我们会在本章完善文件上传功能，支持断点续传并且上传文件时，检查文件是否上传过实现极速秒传。...
9-1 分片传输的试探 (13:18)

9-2 分片上传功能开发1 (19:33)

9-3 分片上传功能开发2 (23:45)

9-4 分片合并功能开发 (13:07)

9-5 分片检查与极速秒传 (24:55)

9-6 文件上传流程图 (03:35)


### 第10章 基于阿里云OSS的文件上传

#### 在线视频课程的核心内容就是视频，保障视频不外泄是程序的重中之重，所以我们需要对视频做加密处理，本章我们选择阿里云视频加密，阿里云视频点播是对OSS的包装，支持防盗链和视频加密。
10-1 阿里云OSS简介 (10:14)

10-2 基于OSS接口的文件上传 (20:06)

10-3 阿里云视频点播服务介绍 (10:13)

10-4 基于OSS原生SDK上传视频到点播1 (19:51)

10-5 基于OSS原生SDK上传视频到点播2 (08:57)

10-6 视频授权播放功能开发 (16:20)


### 第11章 用户管理与登录

#### 本章将演示用户管理及控台登录功能的开发，登录拦截是一个管理控台最基本的权限拦截，防止出现未登录用户直接访问控台界面或接口，同时保障系统内部用户的信息安全，介绍单点登录功能的开发，单点登录SSO（Single Sign On）在大型网站设计中非常常见，用户只需要登录一次就可以访问所有相互信任的应用系统，是提升用户体...
11-1 增加用户管理功能 (22:17)

11-2 密码的加密传输与加密存储 (20:05)

11-3 基本的登录功能开发 (21:41)

11-4 退出登录与记住登录 (20:41)

11-5 增加登录图形验证码 (17:02)

11-6 单点登录功能开发 (18:01)

11-7 前后端登录拦截 (17:49)

11-8 用户登录流程图 (06:51)

11-9 用户管理，在创建用户的时候，能否直接选择角色

11-10 如何实现邮箱注册功能？


### 第12章 通用权限设计

#### 本章演示通用权限功能开发，不依赖任何使用第三方框架，使用经典的资源、角色、用户关联，灵活且维护，可以细粒度的控制菜单、按钮、接口的权限，适用于通用后台管理系统的权限管理。
12-1 通用权限解决方案介绍 (15:53)

12-2 资源配置管理 (24:27)

12-3 角色权限管理 (27:46)

12-4 登录时获取资源权限 (17:17)

12-5 权限拦截功能开发 (19:51)


### 第13章 网站开发

#### 本章将制作用于学员使用的网站，学习BootStrap的网站模板的使用，可以让程序员即使不会美工也可以写出漂亮的网站。
13-1 网站模块的搭建 (09:33)

13-2 集成bootstrap官方模板 (15:06)

13-3 首页开发-1 (12:45)

13-4 首页开发-2 (11:39)

13-5 课程列表页面开发 (14:06)

13-6 分类筛选功能开发 (21:21)

13-7 课程详情页面开发 (16:16)

13-8 章节显示与视频播放 (19:54)

13-9 增加会员注册功能 (15:35)

13-10 增加登录与退出登录功能 (23:59)

13-11 增加发送短信验证码功能 (16:59)

13-12 完善登录注册校验功能 (19:03)

13-13 增加立即报名功能 (08:54)


### 第14章 项目优化

#### 至此整个项目的主框架和主业务都开发完成了，这一章将对项目做一些优化，比如控台报表显示，spring boot多环境配置，缓存的使用等。
14-1 项目初始化 (06:40)

14-2 控台欢迎页开发 (11:37)

14-3 前后端多环境配置 (14:37)

14-4 前后端缓存的使用 (06:25)

14-5 控台欢迎页面报表完善

14-6 如何增加老师端的控台


### 第15章 课程总结

#### 本章将带大家回顾总结课程重点难点，在课程问答区老师等着与你进一步交流，有问题欢迎大家到课程问答区提问。
15-1 课程总结 (03:44)


### 第16章 项目功能升级

#### 本章是对课程做的升级，核心是对部分功能升级优化，比如优化验证码的清晰度，优化登录token超时的问题，关闭播放器模态框时停止播放，还会分享学习Vue事件总线、Vue新增属性的数据绑定等新的技能。
16-1 已提交的代码讲解 (11:23)

16-2 验证码图片清晰度优化 (05:37)

16-3 Vue CLI多环境编译 (14:55)

16-4 新增视频时没有触发绑定 (07:35)

16-5 关闭播放器模态框时停止播放 (19:24)

16-6 登录token超时优化 (12:26)

16-7 Vue事件总线使用案例 (13:54)


### 第17章 生产打包与发布

#### 本章是对课程做的升级，核心是掌握如何将整个项目发布到生产环境，通过外网来访问，项目演示地址：www.courseimooc.com，控台地址：admin.courseimooc.com 测试用户test/test。
17-1 注册中心&配置中心Nacos (14:21)

17-2 注册中心&配置中心Nacos2 (13:08)

17-3 阿里云部署方案介绍 (03:28)

17-4 RDS购买与配置 (17:09)

17-5 ECS购买与配置 (12:29)

17-6 JDK安装与Nacos安装 (14:10)

17-7 后台模块打包与发布1 (14:50)

17-8 后台模块打包与发布2 (17:44)

17-9 Nginx安装与Vue项目发布 (20:17)

17-10 域名配置1 (16:15)

17-11 域名配置2 (22:36)


[下载地址](https://51xueit.vip "下载地址")
