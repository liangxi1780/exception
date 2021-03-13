Syscall Monitor
==============

介绍
-------------
一个用Intel VT-X/EPT实现的类似Sysinternal's Process Monitor的工具。现已迁移至QT框架，支持32位/64位Windows 7及以上系统。

编译和部署
-------------
QT工程在SyscallMonQT文件夹中，驱动工程在ddimon文件夹中。
QT工程的输出目录请把默认设置改为build32或build64。
实际部署中请自行修改deploy32/deploy64.bat中的windeploy.exe路径，运行deploy32/64.bat即可自动部署所有文件至bin32/bin64中。
64位驱动请自行解决数字签名问题。

支持平台
--------------------
- x86 and x64 Windows 7, 8.1 and 10
- CPU with Intel VT-x and EPT technology support

引用项目
--------------------
- BOOST http://u.720life.cn/g/8f4f31a4abede29a320bc6ec6ef432583559de9c5697da44e92925fdc9b1919d 
- QT http://u.720life.cn/g/5d0bc9e5ccc495aeb751e229fb76db9ab7144488326657a127d856cab296dd7f 
- HyperPlatform http://u.720life.cn/g/54145d0471d91890860f7f8463c03046416e5ef1e082daef52ab155b3a226ed62fc1e7b62558adb9f0cf97d1b80666bb 


 # 良心友情链接

[腾讯QQ群快速检索](http://u.720life.cn/s/8cf73f7c)

[软件免费开发论坛](http://u.720life.cn/s/bbb01dc0)