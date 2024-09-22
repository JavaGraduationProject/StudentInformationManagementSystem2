# 全目录

[更多系统、论文，供君选择 ~~>](https://www.yuque.com/wisebit/blog)

# 23.StudentInformationManagementSystem2

<p>群: 983063232(入群获取sql文件)</p>
<p>QQ: 206157502(加好友获取sql文件)</p>

<p><h1 align="center">23.学生信息管理系统</h1></p>


<p align="center">
	<img src="https://img.shields.io/badge/jdk-1.8-orange.svg"/>
    <img src="https://img.shields.io/badge/Spring-1.8-lightgrey.svg"/>
    <img src="https://img.shields.io/badge/SpringMvc-1.8-lightgrey.svg"/>
    <img src="https://img.shields.io/badge/Mybatis-1.8-lightgrey.svg"/>
</p>

# 简介

> 本代码来源于网络,仅供学习参考使用,请入群(983063232)后联系群主索要sql文件!
>
> 提供1.远程部署/2.修改代码/3.设计文档指导/4.框架代码讲解等服务
>
> 前台首页地址: http://localhost:8080/
>
> 学生: 123456 密码: 123456
>
> 老师: 002 密码:123456
>
> 管理员: admin   密码: 123456

# 详情 
>由SpringMVC+MyBatis为主要框架，mysql8.0配置主从复制实现读写分离，主机丛机分别为腾讯云的服务器，而项目部署在阿里云上。前端主要由bootstrap完成，背景用particles.js插件。数据库交互查询用到pagehelper分页。在添加修改相关功能时通过ajax来验证其主键是否存在可用。代码层次清晰，输入框约束较高，已配置登录拦截。

>------------------------------------------------------------------------------------------------------------------------
**新增：**
* 增加分页查询
* 输入框约束
  学号、身份证、课程编号、教师编号只能输入数字，并且有最大输入限制，其中学号固定12位，若小于12位将会有提示。姓名只能输入中文。几乎所有输入框不能输入空格等约束
* 下拉框联动
  添加、修改课程采用二级联动，即所属系别——所属专业；
  添加、修改学生采用三级联动，即系别——专业——班级。（三级联动代码有些复杂，因为JavaScript学的不好=-=）。
* ajax+springmvc验证
  用于验证学号、课程编号、教师编号是否存在并给出提示信息等。
  其中课程安排时间地点排重功能正在开发中····
* 登录拦截
  在handler层配置拦截器，对各角色进行登录拦截，即未登录用户不能直接通过相应url访问。


## 环境

- <b>IntelliJ IDEA 2021.3</b>

- <b>Mysql 5.7.26</b>

- <b>Tomcat 7.0.73</b>

- <b>JDK 1.8</b>




## 缩略图

![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/cc828167-bb5b-4941-a19a-951715406371.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/09681fe0-e5be-42ae-9daf-b4e6606c20db.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/b7aaf3b3-11cb-409a-a183-22eff01af7c1.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/93f3d1fc-3563-4fa4-a773-f510d29831f1.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/8bdce23c-d9f4-4cd4-a294-179857517a44.png)





