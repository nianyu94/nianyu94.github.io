---
title: "如何在 Windows 10 系统安装霞鹜文楷"
author: "念予"
date: 2022-08-12T13:16:21+08:00

tags : [                                    
"霞鹜文楷",
]
categories : [                              
"霞鹜文楷",
]
---

# LXGW WenKai / 霞鹜文楷

霞鹜文楷是一款开源中文字体，具体的介绍可查看：https://github.com/lxgw/LxgwWenKai

![img](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/documentation/wenkai-1.png)

# 安装并使用霞鹜文楷

进入 [Release](https://github.com/lxgw/LxgwWenKai/releases) 界面下载对应版本的 TTF 格式文件，右键—为所有用户安装。

桌面点击右键—个性化—字体

![image-20220823165501158](https://github.com/nianyu94/nianyu94.github.io/tree/main/content-images/1/image-20220823165501158.png)

但是安装完成后，系统的字体并没有发生改变，重启也无济于事。

那如何使用已安装的字体呢？

1. 按win+r打开运行窗口，输入regedit，点击确定打开Windows的注册表编辑器
2. 在打开的注册表编辑器中依次找到fonts，右侧列表中找到我们安装的字体。选中字体点击右键，选择修改，复制该字体的数值数据

![image-20220823172633657](https://github.com/nianyu94/nianyu94.github.io/tree/main/content-images/1/image-20220823172633657.png)

![image-20220823172933967](https://github.com/nianyu94/nianyu94.github.io/tree/main/content-images/1/image-20220823172933967.png)

3. 依次找到`Microsoft YaHei & Microsoft YaHei UI （TrueType）`，`Microsoft YaHei Bold & Microsoft YaHei UI Bold（TrueType）` 和 `Microsoft YaHei Light & Microsoft YaHei UI Light （TrueType）` 分别替换为霞鹜文楷对应的三种字体的数值数据。