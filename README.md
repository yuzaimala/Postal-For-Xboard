# Postal-For-Xboard

## 介绍

为Xboard提供通过Postal API发送邮件的功能 \
与SMTP协议相比，Postal API提供了更高的发送速度和更低的延迟

## 安装

1. 下载文件MailService.php
   ，替换Xboard目录下的`/app/Services/MailService.php` \
2. 在Xboard网站根目录下执行以下命令
    ```bash
    composer require postal/postal
    ```

## 配置

在管理员面板`系统配置`-`邮件`中进行配置

`SMTP服务器地址`为Postal面板地址，结尾无需加`/` \
`SMTP密码`为Postal API Key \
`发件地址` 为发送邮件的发件地址 \
其余设置请留空

## 问题

如果您在使用过程中遇到任何问题，欢迎提出Issue


原项目：https://github.com/SideCloudGroup/Postal-For-V2Board