# 基于Servlet+EasyUI+Mysql学生信息管理系统

#### 介绍
基于Servlet+EasyUI+Mysql的学生信息管理系统，快来学习吧!

公众号：springmeng    回复信息：**学生信息文档**  领取源码

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/220101_df041e31_7604956.png "屏幕截图.png")

**资料内容非常详细！**

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/220136_e09e20a8_7604956.png "屏幕截图.png")

## 1. 系统的部署

* 软件安装，在b站**java攀登网001**首页中搜索：部署；需要下载**eclipse**，**navicat**，**mysql**，**jdk1.7**，**tomcat7.0**

* 直接导入源码：需要添加jdk

**添加jdk**：

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/210403_600b2db2_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/210417_9fe520f1_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/210458_c27b1b3f_7604956.png "屏幕截图.png")

再点击finish即可导入项目

如果导入项目后报错，右键项目，选择build path-configure build path，导入jdk

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/210715_042f51b4_7604956.png "屏幕截图.png")

**添加tomcat**：

点击蓝色字

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/210801_627611fc_7604956.png "屏幕截图.png")

选择tomcat7.0后点击next

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/210827_17d1afe6_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/211536_523e7dd1_7604956.png "屏幕截图.png")

点击finish

**导入数据库**

打开navicat，右键点击连接，选择新建数据库

建好数据库之后，右键点击数据库，选择运行sql文件

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215231_4a4ff30a_7604956.png "屏幕截图.png")

选择sql文件的位置，点击开始

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215253_df9b3297_7604956.png "屏幕截图.png")

数据库导入成功！

点击eclipse的菜单-Search-file，将containing text内容改为mysql，点击确定

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215451_91c567e0_7604956.png "屏幕截图.png")

修改数据库连接的用户名和密码

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215623_019024d5_7604956.png "屏幕截图.png")

点击add and remove

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215712_5b3634c5_7604956.png "屏幕截图.png")

将项目加进来，点击finish

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215736_e7a2113b_7604956.png "屏幕截图.png")

右键-start即可启动项目！

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215817_b7f06e3d_7604956.png "屏幕截图.png")

输入地址即可访问

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215856_cdb655ae_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/215914_5816b460_7604956.png "屏幕截图.png")

* 有问题评论区留言

## 2. 系统介绍

### 2.1 技术介绍

知识点：jsp servlet，MySQL数据库的基本操作，前端easyui框架

适合人群：java初学者，在校学生(已经学过java基础语法，对html有简单的了解，熟悉js，jquery语法)

工具：eclipse，MySQL

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/220701_6b4c52df_7604956.png "屏幕截图.png")

### 2.2 功能介绍

**学生信息管理**：可以对学生信息进行添加，删除，查询等操作

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/220758_3cc9d943_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/220849_5f190d3f_7604956.png "屏幕截图.png")

**班级信息管理**：提供添加，修改，删除，搜索的功能

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/220926_41ee556c_7604956.png "屏幕截图.png")

**教师信息管理**：

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/221133_48f3c73f_7604956.png "屏幕截图.png")

**课程信息管理**：

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/221143_8e9fbd3a_7604956.png "屏幕截图.png")

**选课信息管理**：

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/221156_4a66d7b2_7604956.png "屏幕截图.png")

**请假信息管理**：

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/221310_be1e6931_7604956.png "屏幕截图.png")

**成绩信息管理**

分为成绩列表和成绩统计

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/221251_990e426e_7604956.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/221400_bcf7e50b_7604956.png "屏幕截图.png")

**系统管理**

## 3. 如何对系统进行二次开发

需要大家有servlet的基础，如果不会，可以在**java攀登网001**中搜索servlet进行学习

### 3.1 以登录功能为例

先将登录页面写出来，点击登录的时候会触发submitButton方法，再详细定义submitButton方法

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/222109_1da9610e_7604956.png "屏幕截图.png")

将用户输入的用户名和密码信息保存到data，然后用ajax请求到后台

![输入图片说明](https://images.gitee.com/uploads/images/2020/1223/222221_2fd396af_7604956.png "屏幕截图.png")

**欢迎大家一起交流学习，共同进步。技术交流群，请加小孟微信：**

<div align=center><img width="250" height="250" src="https://images.gitee.com/uploads/images/2020/1219/203754_ef21dcd8_7604956.png"/></div>
