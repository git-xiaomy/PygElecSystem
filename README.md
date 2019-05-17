# PygElecSystem
这是一个基于Go语言、Beego框架开发的B2C模式的电商系统。目前系统功能还在逐步完善当中，会持续更新。




+ [技术特色](#技术特色)
+ [开发环境](#开发环境)
+ [功能模块](#功能模块)
+ [安装](#安装)
+ [用法](#用法)
+ [后续](#后续)


## 技术特色
主要用到的技术包括:Beego,Go,jQuery,Ajax,javascript,路由过滤拦截,FastDFS,Nginx,redis等。在用户注册时使用阿里云短信验证码验证注册，并在注册成功时使用邮箱激活用户，同时在后台管理中使用了分布式文件系统--FastDFS进行图片的存储，使用Nginx作为图片的访问服务器，在购物车模块中使用redis进行存储，并在支付时接入支付宝等第三方支付的接口。

## 开发环境
Linux系统下开发，主要开发工具包括:Linux,Git,GoLand,mysql,redis等。

## 功能模块
系统主要功能模块包括:用户注册,用户登录,主页商品展示,商品管理,购物车,订单管理,订单支付等等。

## 安装
### 系统安装
整个项目是在Linux系统下进行开发，使用的是VMware14.1.1+Ubuntu18.04,安装包下载链接如下：

+ [VMware14](https://my.vmware.com/cn/web/vmware/info/slug/desktop_end_user_computing/vmware_workstation_pro/14_0)
这里记得要针对你电脑选择不同的版本，for windows或者for Linux.

+ [Ubuntu18.04](https://www.ubuntu.com/download/desktop)
### 开发环境安装
+ **Go语言安装**
---
+ **IDE安装**
---
+ **Beego框架安装**
---
+ **Mysql安装**
---
+ **Redis安装**
---
+ **FastDFS安装**
---
+ **Nginx安装**
## 用法
后续更新

## 后续
目前系统功能还在逐步完善中,因为是个人项目,所以会不定期更新,有兴趣的朋友们希望可以关注并fork一下,欢迎大家一起参与其中，谢谢大家。
