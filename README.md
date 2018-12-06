## 引言

此项目基于JeeSite，为一个学习项目。

JeeSite 是一个 Java EE 企业级快速开发平台，基于经典技术组合（Spring Boot、Spring MVC、Apache Shiro、MyBatis、Beetl、Bootstrap、AdminLTE）采用经典开发模式，让初学者能够更快的入门并投入到团队开发中去。在线代码生成功能，包括核心模块如：组织机构、角色用户、菜单及按钮授权、数据权限、系统参数、内容管理、工作流等。采用松耦合设计；界面无刷新，一键换肤；众多账号安全设置，密码策略；在线定时任务配置；支持集群，支持SAAS；支持多数据源。

JeeSite 快速开发平台的主要目的是能够让初级的研发人员快速的开发出复杂的业务功能（经典架构会的人多），让开发者注重专注业务，其余有平台来封装技术细节，降低技术难度，从而节省人力成本，缩短项目周期，提高软件安全质量。

JeeSite 自开源以来已被广大爱好者用到了企业、政府、医疗、金融、互联网等各个领域中，JeeSite 依架构简单精良、易于扩展、大众思维的设计模式，深入开发者的内心，并得到一致好评，于[2016](http://www.oschina.net/project/top_cn_2016?sort=1)和[2017](http://www.oschina.net/project/top_cn_2017?sort=1)连续两年获得开源中国《最受欢迎中国开源软件》奖杯，期间也帮助了不少刚毕业的大学生作为入门教材，快速的去实践。

4.x的升级，作者结合了多年总结和经验，以及各方面的应用案例，对架构完成了一次全部重构，也纳入很多新的思想。不管是从开发者模式、底层架构、逻辑处理还是到用户界面，用户交互体验上都有很大的进步，在不忘学习成本、提高开发效率的情况下，安全方面也做和很多工作，包括：身份认证、密码策略、安全审计、日志收集。

### 4.x 新特性：<http://jeesite4.mydoc.io/?t=281645>

* **我们的优势：** 整体架构清晰、稳定技术先进、入门简单、易于维护、易于扩展、安全稳定。

## 技术选型

* 主框架：Spring Boot 2.0、Spring Framework 5.0、Apache Shiro 1.4、J2Cache
* 持久层：Apache MyBatis 3.4、Hibernate Validation 6.0、Alibaba Druid 1.1
* 视图层：Spring MVC 5.0、Beetl 2.7 替换JSP、Bootstrap 3.3、AdminLTE 2.4
* 前端组件：jQuery 1.12、jqGrid 4.7、layer 3.0、zTree 3.5、jquery-validation
* 工具组件：Apache Commons、Logback 1.1、Jackson 2.8、POI 3.14、Quartz 2.2
* 技术选型详情：<http://jeesite4.mydoc.io/?t=273599>

## 内置功能

* <http://jeesite4.mydoc.io/?t=270187>

## 生态系统

* 分布式微服务系统（Spring Cloud）：<https://gitee.com/thinkgem/jeesite4-cloud>
* JFlow工作流引擎：<https://gitee.com/thinkgem/jeesite4-jflow> ：<http://ccflow.org>
* 内容管理模块（CMS）：<https://gitee.com/thinkgem/jeesite4-cms>【敬请期待】

## 快速体验

### 在线演示

1. 地址：<http://demo.jeesite.com/>
2. 账号：system
3. 密码：admin

### 本地运行

1. 环境准备：`JDK 1.8`、`Maven 3.3`、`MySQL 5.7`
2. 下载源码：<https://gitee.com/thinkgem/jeesite4/attach_files>
3. 打开文件：/web`/src/main/resources/config/application.yml` 配置JDBC连接
4. 执行脚本：/web`/bin/init-data.bat` 初始化数据库
5. 执行脚本：/web`/bin/run-tomcat.bat` 启动服务即可
6. 浏览器访问：<http://127.0.0.1:8980/js/>  账号 system 密码 admin
7. 部署常见问题：<http://jeesite4.mydoc.io/?t=284210>

### 开发环境

1. 部署运行：<http://jeesite4.mydoc.io/?t=267354>
2. 常见问题：<http://jeesite4.mydoc.io/?t=284210>

## 开发手册 

* 代码生成 / 快速入门 (Guide)：<http://jeesite4.mydoc.io/?t=316743>
* 持久层 / 数据库操作 (MyBatis)：<http://jeesite4.mydoc.io/?t=267351>
* 业务层 / 数据权限 (Service)：<http://jeesite4.mydoc.io/?t=267352>
* 视图层 / 表单组件 (Beetl)：<http://jeesite4.mydoc.io/?t=267353>
* 功能权限基础文档 (Shiro)：<http://jeesite4.mydoc.io/?t=298473>
* 常用JS类库API (jeesite.js)：<http://jeesite4.mydoc.io/?t=301473>
* 数据表格API (DataGrid.js)：<http://jeesite4.mydoc.io/?t=301488>
* 修改 (默认) 视图，新增主题：<http://jeesite4.mydoc.io/?t=267355>
* 手机 API 接口调用、前后分离：<http://jeesite4.mydoc.io/?t=270527>
* 消息提醒中心使用手册：<http://jeesite4.mydoc.io/?t=323351>
* 常见问题：<http://jeesite4.mydoc.io/?t=284210>

