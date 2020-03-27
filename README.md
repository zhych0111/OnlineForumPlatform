# 在线论坛系统
本项目为在线论坛系统项目，是一个开源项目，开发的全过程在博客中记录，博客的地址为：[开发博客地址](https://blog.csdn.net/qq_43422111/article/details/105141834)
## 实现框架
本项目前端采用HTML/CSS/JS/Bootstrap进行开发，数据库采用MySQL,服务器端采用Python进行开发，采用Flask框架。
## 项目功能
本次的项目是一个在线论坛系统，字如其名，就是开发一个在线的论坛系统。分为普通用户和管理员两个端，普通用户。需要实现的功能如下：

-   注册：注册账号
-   登录：登录账号进入系统，如果登录普通用户，则只有普通用户的权限，如果是管理员账号，则有管理员账号权限。
-   查看论坛问题列表：查看在线论坛系统中所有已发布的问题.
-   发布问题：
    -   发布自己的问题，等待他人回答
    -   支持富文本输入
    -   支持Markdown输入
-   问题详情页面：显示当前问题的讨论、回复。
-   回答问题：回答他人问题。
-   个人中心：
    -   显示个人账号信息
    -   可以修改个人账号信息
    -   显示个人发帖情况
    -   显示个人回复情况
暂定这些功能，后续再逐渐完善