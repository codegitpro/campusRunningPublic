### 作者微信：grapro666 QQ：3642795578 (支持部署调试、支持代做毕设和论文)

### 接javaweb、python、小程序、H5、APP、各种管理系统、单片机、嵌入式等开发

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/134043585](https://blog.csdn.net/2303_76227485/article/details/134043585)**

**视频演示：
[https://www.bilibili.com/video/BV1DQ4y1p7Ut/](https://www.bilibili.com/video/BV1DQ4y1p7Ut/)**

**毕业设计所有选题地址：
[https://github.com/codegitpro/allProject](https://github.com/codegitpro/allProject)**

## 基于Java+Springboot+Vue的校园跑腿系统(源码+数据库)105

## 一、系统介绍
本系统前后端分离

本系统分为管理员和用户两个角色

- 用户：
登录，注册，余额充值，密码修改，发布任务，接受任务，订单管理，查看公告，我的评价，个人信息修改。

- 管理后台：
登录，首页统计，学校管理，任务管理，用户管理，评价管理，系统公告管理。

## 二、所用技术
后端技术栈：
- Springboot
- SpringMvc
- mybatisPlus
- mysql

前端技术栈：
- Vue
- elementui
- vue-router
- axios

## 三、环境介绍
基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上, Node.js(14.21), Maven3.6, Vscode

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户功能
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

### 2、管理员功能
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)

## 五、浏览地址

- 前台访问路径：http://localhost:8848/#/login
  用户名密码：20200102/123456  学校选择湖南大学
- 后台访问路径：http://localhost:8848/#/admin
  用户名密码：admin/123456

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql

2. 使用IDEA/Eclipse导入campus-gang-api-master项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

3. 修改resources目录下面application.yml里面的数据库配置

4. com/yqn/CampusGangApplication.java启动后端项目

5. vscode或idea打开campus-gang-web-master项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run serve,执行成功后会显示前台访问地址

