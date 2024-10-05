---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**毕业设计所有选题地址 [https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**



**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/131705456](https://blog.csdn.net/2303_76227485/article/details/131705456)**

**视频演示：
[https://www.bilibili.com/video/BV1Bh4y1f7hw/](https://www.bilibili.com/video/BV1Bh4y1f7hw/)**

**毕业设计所有选题地址：
[https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

## 基于Springboot的宠物店管理系统(源代码+数据库)087

## 一、系统介绍

本系统分为管理员、店员两种角色

店员角色包含以下功能：

- 登录、宠物主人管理、宠物管理、宠物医疗管理、宠物销售管理、宠物寄养管理、宠物用品管理、宠物日常服务管理、宠物常见问题、个人中心、密码修改

管理员角色包含以下功能：

- 登录、宠物主人管理、宠物管理、宠物医疗管理、宠物销售管理、宠物寄养管理、宠物用品管理、宠物日常服务管理、宠物常见问题
- 用户管理、角色管理、部门管理、岗位管理、菜单管理、服务监控、日志管理、个人中心、密码修改

## 二、所用技术

后端技术栈：

- Springboot
- MybatisPlus
- Mysql
- Jwt
- Shiro

前端技术栈：

- bootstrap
- jquery
- html

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上,Node.js(14),Maven3.6,Redis5.0

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)

## 五、浏览地址

访问地址：http://localhost:8081
-店员账号/密码：15712341234/123456
-管理员账号/密码：admin/123456

## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件；

2. 使用IDEA/Eclipse导入petShop项目，若为maven项目请选择maven，等待依赖下载完成；

3. 进入mmtax-admin/src/main/resources修改application.properties 里面的数据库配置、文件目录地址和redis配置

4. mmtax-admin/src/main/java/com/mmtax/MmtaxApplication.java 启动项目

## 七、模块划分

mmtax-admin :系统管理后台端主要代码，包括系统管理后台前后端代码
mmtax-common：公共工具模块
mmtax-framework：系统配置模块
mmtax-generator：代码生成模块
mmtax-quartz：定时任务模块
mmtax-system：service，dao，domain以及mapper文件存放模块

打包：使用IDEA开发工具打包时，由于使用的是springboot，无需打包成war包，直接打包成jar包即可。点击右侧工具栏maven-->mmtax-->lifecyle-->clean-->install等待打包完成，
发布服务的时候，将mmtax-admin目录下target文件夹中的mmtax-admin.jar发布到服务器即可


