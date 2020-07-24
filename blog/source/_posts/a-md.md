---
title: 某地不能上github的解决办法之修改host
date: 2020-07-25 03:08:32
tags:

---
1.上网搜索DNS查询工具
2.输入github的域名，点击【检测】，得到一个DNS地址
3.进入电脑的C盘的C:\Windows\System32\drivers\etc目录下，找到hosts文件
4.在hosts文件上右键，打开属性窗口，取消勾选【只读】属性
5.修改hosts文件的权限，点击“安全”，点击“编辑”
6.勾选对应用户的“完全控制”、“修改”权限，全部打钩，否则无法对hosts文件进行改动。
7.用记事本打开hosts文件，将查询的DNS以x.x.x.x   github.com的格式添加到最后，重新访问即可