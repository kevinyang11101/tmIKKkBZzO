# 前言

随着移动互联网的快速发展，个人健康信息管理变得越来越重要。本项目是一个基于Spring Boot和微信小程序的个人健康信息管理小程序，旨在帮助用户更好地管理个人健康数据，提高健康管理水平。

# 内容介绍

本项目主要包括以下功能模块：用户管理、健康数据录入、健康数据分析、健康建议等。用户可以通过微信小程序轻松录入个人健康数据，如体重、血压、血糖等，并查看历史数据趋势图。此外，系统还会根据用户的健康数据提供相应的健康建议，帮助用户改善生活习惯，提高健康水平。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，mybatis，微信小程序

## 前端技术：JS、Vue、css3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven: apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一段核心代码，用于实现用户登录功能：

```java
// UserController.java

@RestController
@RequestMapping("/user")
public class UserController {

    @Autowired
    private UserService userService;

    @PostMapping("/login")
    public ResponseEntity<User> login(@RequestBody User user) {
        User result = userService.login(user);
        if (result != null) {
            return ResponseEntity.ok(result);
        } else {
            return ResponseEntity.status(HttpStatus.UNAUTHORIZED).build();
        }
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/331046/23/13103/78471/68c632d2F5899367f/a0874e5f0fe16be0.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/333232/17/13168/11646/68c632aaF27fb9436/ef1637b5370265e3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326881/39/19731/28788/68c632aaFd3a36f07/56a127b9542fc848.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/337366/20/10434/30873/68c632aaF6f809ea9/50ab89fa72d467a6.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/350198/40/3064/12539/68c632aaF7869c0be/28c65676bdef9aef.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340027/3/10663/9947/68c632abF67233ad7/2a597702813478e2.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/330084/3/13175/27493/68c632abF09c9a70e/b878b63a9eb44a68.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/350287/28/2897/7316/68c632acFb1dd73b5/9ca2e9f8e770f442.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/324931/21/19775/80928/68c632acF23981718/09a893ee74db0570.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334822/35/13004/64674/68c632acFe38c6d16/a7d101a43612ded5.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
