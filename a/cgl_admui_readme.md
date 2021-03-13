# AdmUI

![输入图片说明](https://git.oschina.net/uploads/images/2017/0520/235240_4891b6cc_1353370.png "在这里输入图片标题")

>你还在为项目的用户体验和UI的颜值发愁吗？

>曾经，我们也是，公司的各个部门，每做一个项目都要对应的搭一套前端的项目，

>对于只擅长写后台的代码汪来说，这个过程相当的苦恼，各种问题让你抓狂不已，

>我们一怒之下，找了当下比较流行的技术，又不想跟Bootstrap千篇一律，

>于是我们采用了Google Material Design做为设计语言，开发了适用于中后台管理类型的UI Template项目，

>你只需要根据自己的需要，简单的修改几个配置就能搞出一个华丽的前端UI  :tw-1f600: 


>你可以打开这个链接看一下效果，http://u.720life.cn/g/b22fb3d9b009b8a2edff61d1c6eb13cce02832cd2b099c83cf32c3fdf7ccb1f768e226b736d6b47843adb21e55069742 


所以,

AdmUI它是一个中后台管理UI快速开发模板，采用Bootstrap、AngularJS等技术，已完成项目整体基础搭建，只需要在`App/modules`下添加自己的view和js你就可以开始干活了  :tw-1f60b: 。

你需要熟（control+c）悉（control+v）并使用的技术：

1. Bootstrap 3，http://u.720life.cn/g/e23be2821e5181a1a46a005bc6e93d9defdf99ca32552b6780c0e93b692ebec7 
1. AngularJS 1.5.x，http://u.720life.cn/g/bfa55acf2f2b960576f394bd1c2b16a4ce79a3570985f4e4797a1114a5b62975 
1. AngularJS Material 1.0.4，http://u.720life.cn/g/afa137df0c66eb85aadcf3a5790d905983053ccf8142e1e79dd2f86be242ca4c4f395914e6eb075c2de75931f8ba5ddc 


### 如何开发

Master是基础依赖框架整合分支，最终会生成单独的js和css包，供App开发引用，
Pages是实践项目，包括App开发中所用到的文件。

克隆`pages`分支，在 `app/modules/`目录中添加模块即可，`plugins`是你项目依赖的第三文件组件，运行`npm start`启动项目，默认地址：`localhost:9800`。

#### 环境
1. Node、Npm（介意使用cnpm）
1. grunt、bower


![输入图片说明](https://git.oschina.net/uploads/images/2017/0520/235306_e0ed5ddf_1353370.png "在这里输入图片标题")

### 功能特性

1. 基于 Bootstrap 3
1. 基于AngularJS 1.5.x
1. 以 Google Material Design 为设计语言
1. 支持多Tab切换，可以关闭当前、其它等功能
1. 主菜单动态配置，支持多级
1. 不同的 Material Design Colors ，并且可以在不同的View中使用不同的Color
1. 三种不同的 layouts
1. 集成了AngularJS Material
1. 支持在View中懒加载所需要的依赖文件
1. 响应式实现，适配各种尺寸的屏幕
1. 完全实现了 Material Design Colors
1. 采用 Node、Bower 和 Gulp做为开发工具
1. Less源码
1. 仿Inbox的案例页面
1. 制作了Profile、Gallery、Login、Sample page等页面


## 依赖的技术

 
1. Bootstrap - http://u.720life.cn/g/e23be2821e5181a1a46a005bc6e93d9defdf99ca32552b6780c0e93b692ebec7 
1. jQuery - http://u.720life.cn/g/bf5ee7c5d8e747312b9dff6cfd254723ddc6e61ca9d7f3f3208313e2b2afc0b6 
1. AngularJS - http://u.720life.cn/g/42de713304a7254676f2ec714d9dd45e1e57485b22874f62298be099949f7ebf 
1. AngularJS Material - http://u.720life.cn/g/afa137df0c66eb85aadcf3a5790d90597545fb3c30a54f9fcbfbb996fe46ad71 
1. Bower - http://u.720life.cn/g/0cca3df8bb513066303cc85c81970c12 
1. Gulp - http://u.720life.cn/g/42c4ab571b486d53af2ab7b8bae8086b8181dbde5f085c12e5be0270a023ad42 
1. OC Lazy Load for AngularJs - http://u.720life.cn/g/54145d0471d91890860f7f8463c03046221759fa7a2c6890637167d9d849c92d51c61d7e82a5612a91b71b76332c8362 
1. Animate.css - http://u.720life.cn/g/764520e3352b0658830134172d2e142ad2d659fd98a69148c8359901437008abdd47d75ce1859eea8a2732d1eb29a19c 
1. Flot Chart - http://u.720life.cn/g/a550bd142328983531107615723fc10c37f62c06a49855637a87a5afe6e814e8 
1. magnific-popup - http://u.720life.cn/g/721f1785eaea93500abb4c644948ce9d4393e6cfe8e8587aafac3c2ecee2cfdf181f5e06e735f5b156462969283572d6 
1. Full Calendar - http://u.720life.cn/g/44af96d4dc56b8262b66020c0d83f78e25b9a78a947f7ef128ccd71eeeec63ea 
1. Material Design Icon - http://u.720life.cn/g/3927b7d0d2c169858a082c89b54cb0d18657b41743f7f7c7c42504011302b5e66520d93d202bc394ce1533d5ad7a3d2c51daed8bf3cd165fcdf1c3dd37f0f48704991059f2472d376813eb8b48bb1069 
1. SparkLine Chart - http://u.720life.cn/g/65834812b72627762efcfdd16a0b31e3acd7d5aa47b6322a9718075e3f4bf747db88b58a0dfd1a29f264ebfcd7ef3b76 
1. SummerNote - http://u.720life.cn/g/0a7a8eed651902779c4b9098fa1e8a2cb7cebd744678f026df674244506d4367 
1. Malihu Content Scroller - http://u.720life.cn/g/abb47dea354fa5276f4517be21a4d334b88a13c471eb7ad006da307afb26edb01c4287d8217e474f6730880c84a24983e32490c70f062208a28f55b443673844 
1. Angular Loading Bar - http://u.720life.cn/g/0263b8bac15b616d7bfab00a6b53b01f39b9070dc44c6ba8091e42c7cc7f27d1f141a389cd4cd16cecc5531c8bb1f4420092f334ed8a546bc857acf4c6d31482 
1. Roboto Font - http://u.720life.cn/g/ee2b38aff8b7000e40b3c7bbe8e12b42c8e7460e27672995b036144bd086d0611a5813fb1fbe69fb439328c33ba4669a 


 # 良心友情链接

[腾讯QQ群快速检索](http://u.720life.cn/s/8cf73f7c)

[软件免费开发论坛](http://u.720life.cn/s/bbb01dc0)