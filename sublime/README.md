# Sublime3 无法安装插件

## 错误描述
Package Control  
There are no packages available for installation  
Please see https://packagecontrol.io/doc/troubleshooting for help

## 错误截图
![图片未找到](https://github.com/happyzero/notebook/sublime/PackageControlError.jpg)

## 原因
Package Control被墙掉了

##解决办法：

1. 点击 Preferences->Package Setting->Package Control->Settings - User

2. 添加如下内容：

```
"channels":
[
    "http://cst.stu.126.net/u/json/cms/channel_v3.json"
]
```