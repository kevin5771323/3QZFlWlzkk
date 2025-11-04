# 家庭事务管理微信小程序+SSM

## 前言

在快节奏的生活中，家庭事务的管理变得越来越重要。本项目旨在为用户提供一个便捷、高效的家庭事务管理工具，通过微信小程序的形式，实现家庭成员间的信息共享与协同。

## 内容介绍

家庭事务管理微信小程序基于SSM框架，主要功能包括：家庭成员管理、事务分类、事务发布与提醒、进度跟踪等。通过本小程序，用户可以轻松发布家庭事务，分配任务，实时了解事务进度，提高家庭协作效率。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为一段关于事务发布的核心代码：

```java
// Controller层
@PostMapping("/addAffair")
public Result addAffair(@RequestBody Affair affair) {
    boolean flag = affairService.addAffair(affair);
    if (flag) {
        return Result.ok("事务发布成功！");
    } else {
        return Result.error("事务发布失败！");
    }
}

// Service层
public boolean addAffair(Affair affair) {
    affair.setCreateTime(new Date());
    affair.setUpdateTime(new Date());
    return affairMapper.insert(affair) > 0;
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/347756/4/3100/121651/68c5737eFbc201d97/23faa98c01597fc9.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325087/4/19682/7776/68c57355F20029fc4/eea3829570b1704c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348262/2/2826/19342/68c57355Fc6e347c2/b463270e26ea8337.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/331738/1/12907/10910/68c57356F2d518ad7/f1ec00c79898bde5.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/336884/16/10450/10625/68c57356Fb48a2d1d/6200d793f97a0a4c.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339759/6/10353/9514/68c57356F03d446ab/8d6567ea90c5c03d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/322769/18/9554/66654/68c57356F4dcaa7b5/649e709c474cc01a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/323619/28/19497/18897/68c57357Fa91a0918/8c3146460356fbd6.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/345747/34/2924/34205/68c57357F2676d063/385136c652065dfb.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/342952/11/2549/14503/68c57357F147be59f/cfc31b1f339612fc.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
