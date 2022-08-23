# 学生信息管理系统

扫描下方 ，回复“**学生9**”，获取源码

![https://gitee.com/](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205281253739.png)

## 1、项目介绍

学生信息管理系统拥有三种角色，分别为学生、教师和管理员，功能更加完善，可以作为初学者参照学习课程设计。

- 学生：班级通讯录查询、个人信息查看修改、成绩查询、密码修改

- 教师：教师通讯录查询、个人信息查看修改、成绩登记、成绩查询、考试统计、密码修改

- 管理员：学生信息管理、教师信息管理、班级信息管理、年级信息管理、课程信息管理、成绩统计分析、系统管理：（修改密码、 系统设置、 退出系统）


## 2、项目技术

servlet、jsp、esayui等

## 3、开发工具

eclipse、idea、MyEclipse

## 4、功能介绍

### 4.1 登录界面

![登录界面](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111216.png)

登录界面有三种角色可以选择，分别为学生、老师和管理员，经过密码、用户名和验证码校验通过之后，网页会跳转到不同的角色功能页面。

### 4.2 管理员-成绩统计

![管理员-成绩统计](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111501.jpg)

管理员可以添加和删除考试安排、根据班级信息查看成绩等。成绩统计页面显示了 该考试中学生的姓名、学号以及各科成绩。科目均可以在后台修改。

### 4.3 管理员-添加学生界面

![管理员-学生列表](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111518.jpg)

管理员可以添加、删除和修改学生信息，还可以通过年级和班级条件筛选学生。同时此页面使用了分页技术，每页显示10个学生的信息。教师信息的管理和学生信息管理功能相同，详情可以看项目运行视频。

### 4.4 管理员-系统设置

![管理员-系统设置](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111523.jpg)

系统设置界面中，管理员可以设置该项目的名字，还可以设置通知信息，这些信息都将会分别在老师界面和学生界面显示。同时还可以禁止教师和学生登录系统。

### 4.5 学生相关界面

![学生-成绩查询](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111531.jpg)

![学生-个人信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111537.jpg)

![学生-学生通讯录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111542.jpg)

学生界面主要有三个，分别为成绩查看、班级通讯录查看和个人信息页面。在个人信息页面，学生可以修改自己的信息和密码。

### 4.6 教师相关界面

![教师-成绩统计](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111550.jpg)

![教师-成绩登记](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111553.jpg)

![教师-个人信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111556.jpg)

教师相关页面中，教师可以查看和修改自身信息和密码。同时教师可以对自己负责的课程进行成绩登记以及修改等功能。![教师-教师通讯录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515111559.jpg)

### 4.7文档目录

![文档目录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202208152135557.jpg)





