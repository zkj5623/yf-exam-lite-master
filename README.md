<<<<<<< HEAD
# yf-exam-lite-master

#### 介绍
https://gitee.com/zhou-kangjian/rep03.git

#### 软件架构
软件架构说明


#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
=======
# 云帆培训考试系统 开源版

# 项目演示
开源版本：https://lite.yfhl.net  
管理账号：admin/admin    
学员账号：person/person   
注意事项：演示环境数据每天晚上会重新初始化，不要往上面导入重要数据；如果账号密码被改无法登录，请联系我们；或等到第二天再访问 :joy: 

# 商业版本
如果开源版本无法满足您的需求，或者有需求需要定制，可以考虑我们的商业版本。

云帆在线学习考试系统是一款基于JAVA开发的，使用SpringBoot+Vue开发的一款多角色在线培训考试系统平台，系统集成了用户管理、角色管理、部门管理、题库管理、试题管理、试题导入导出、考试管理、在线考试、错题训练、积分商城、报名考试、课程管理、在线学习、题库训练、刷题训练等功能，考试流程完善，操作简单，易用。    
商业版演示地址：https://exam.yfhl.net   
商业版官网地址：https://www.yfhl.net/?plan=osyf


# 商业版咨询
郭经理：     
    邮箱：835487894@qq.com   
    手机：18603038204  
    微信号：gyh_yinzi 
    
![输入图片说明](%E5%9B%BE%E7%89%87.png)       

# 开源版介绍
一款多角色在线培训考试系统，系统集成了用户管理、角色管理、部门管理、题库管理、试题管理、试题导入导出、考试管理、在线考试、错题训练等功能，考试流程完善。

# 技术栈
SpringBoot / Shiro / Vue / MySQL

# 产品功能

## 系统完善：完善的权限控制和用户系统
权限控制：基于Shiro和JWT开发的权限控制功能。    
用户系统：用户管理、部门管理、角色管理等。    

## 多角色：多角色支持    
考试端：学生学员角色、支持在线考试、查看分数、训练错题。    
管理端：题库管理、试题管理、考试管理、用户部门管理、查看考试情况等等。    

## 定员考试：考试权限定义    
完全公开：任何人员都可以参与考试。    
指定部门：只有选中部门的人员才可以看到考试。    

## 多题型：常用题型支持    
支持题型：单选题、多选题、判断题。    
难易程度：普通、困难。    

## 便捷组卷：题库组卷    
题库组卷：指定题库、分数、数量；题目、选项随机排序、杜绝作弊    


# 环境要求
JDK 1.8+  [点此下载](https://cdn.yfhl.net/java-win/jdk-8u181-windows-x64.exe)        
Mysql5.7+  [点此下载](https://cdn.yfhl.net/java-win/mysql-installer-community-5.7.31.0.msi)    

# 安装资源
1、安装JDK1.8    
https://cdn.yfhl.net/java-win/jdk-8u181-windows-x64.exe     

2、安装MySQL    
https://cdn.yfhl.net/java-win/mysql-installer-community-5.7.31.0.msi    
-- 安装过程可能需要VC++    
-- https://www.microsoft.com/zh-CN/download/details.aspx?id=40784    
-- 安装数据库管理工具    
https://cdn.yfhl.net/java-win/SQLyog.12.3.1.0.zip    

# 安装视频    
https://www.ixigua.com/7041491265027834381?utm_source=xiguastudio

# 快速运行  
1、下载编译好的jar包到本目录（或您自行编译）：https://cdn.yfhl.net/lite/exam-api.jar  
2、自行安装MySQL数据库（版本最好是5.7），将`安装资源中`的`数据库初始化.sql`导入到安装好的数据库  
3、安装Java环境，要求JDK版本大于1.8  
4、请修改外置配置文件：application-local.yml 改成您自己的MySQL配置  
5、Windows通过start.bat运行，Linux运行start.sh运行  
6、如果无意外，可通过：http://localhost:8101 访问到项目了  
7、管理员账号密码：admin/admin 学员账号：person/person  
 
# 其它支持
网站：https://www.yfhl.net/?plan=osyf
QQ交流群：865330294

![输入图片说明](https://images.gitee.com/uploads/images/2020/1207/173238_e6c22c67_2189748.jpeg "17-32-10.jpg")
![主界面](https://images.gitee.com/uploads/images/2020/1019/182239_4a87af30_2189748.jpeg "222.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/182532_04c42741_2189748.jpeg "444.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/182543_44dcc2d7_2189748.jpeg "555.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/182551_4d404492_2189748.jpeg "666.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/183109_fdc30de8_2189748.jpeg "777.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/183117_30b44530_2189748.jpeg "888.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/183023_2f3baeb9_2189748.jpeg "999.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/183032_f5016335_2189748.jpeg "1010.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/183040_38fd74ed_2189748.jpeg "1111.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2020/1019/183047_a31619cd_2189748.jpeg "1212.jpg")

# 开源版&商业版对比
![输入图片说明](https://cdn.yfhl.net/lite/compare1.png)
>>>>>>> f1d2b97 (第一次提交)
