﻿# Document-management
一个文档管理系统，可在线打开PDF文件。

这是一个简易的文件管理系统，支持在线打开PDF文件，需要上传PDF到服务器上，且只支持上传PDF文件。
使用的技术为Django+PDF.js。
![login.PNG](https://raw.githubusercontent.com/jsonhua1111/images/master/images/login.PNG)
使用者下载项目到本地，配置好环境后，需创建一个账户用于登录。
![upload.PNG](https://raw.githubusercontent.com/jsonhua1111/images/master/images/upload.PNG)
物理，语文，数学，英语为测试方便，使用者可以自行修改。
![view.PNG](https://raw.githubusercontent.com/jsonhua1111/images/master/images/view.PNG)
此页面提供分类，以及关键字模糊查询。
删除：此处可以判断是否管理员登录，如果管理员登录则会出现删除，一般用户登录不会出现。

此项目还有很多不足之处，如管理员注销，并未在前端页面体现出来，只提供了接口。本人不善前端，所以页面非常丑，欢迎大家批评指正。
