# mall-admin-web

## 说明

> 基于Vue+Element的电商后台管理系统，完整实现了整个流程。

> 该项目为前后端分离项目，搭建步骤具体参考后端项目[传送门](https://github.com/macrozheng/mall)。

> 如果该项目对您有帮助，您可以点右上角 "Star" 支持一下，谢谢！

> 该项目已由`CODING`特别赞助，支持的可以点下赞助商链接，谢谢！

> 项目交流QQ群：[553018255](http://qm.qq.com/cgi-bin/qm/qr?k=M5Edq2TiJL_ShcOEeYjwcmdGmq4zZrd_)、[959351312(满)](http://qm.qq.com/cgi-bin/qm/qr?k=V6xu5c12j9qhnMUNdDRzakNxRKzOxibQ)。

> 码云项目地址：[http://u.720life.cn/g/2e71d0f0a5c601172267ba20d3a43c6ed413e6dac79d5ae837bc13284a4aebcc8dda2d868faa3c3bd09c4df1d0f05322f1eadb092f803e07b3cf8756befb132882aae3e577237bb872c3c9c1b28a4ee7e49bf2f0165d512d7794326015a4d9cd) 

## 前言

`mall`项目后台管理系统的前端项目
[传送门](https://github.com/macrozheng/mall)。

## 特别赞助商

 
 
   
  
 

## 项目介绍

`mall-admin-web`是一个电商后台管理系统的前端项目，基于Vue+Element实现。
主要包括商品管理、订单管理、会员管理、促销管理、运营管理、内容管理、统计报表、财务管理、权限管理、设置等功能。

### 项目演示

项目在线演示地址：[http://u.720life.cn/g/602cbbd93ce6eec9ce45e915b1e17775b4c0f31f9e7e5d4e158615bf48f5166e3bf6caf05f07144337d62c6be808ef1afe3682aeb6e2a303ce9cb591ec8cd5b2)   

![https://github.com/macrozheng/mall/blob/master/document/resource/mall-admin.gif](https://github.com/macrozheng/mall/blob/master/document/resource/mall-admin.gif)

### 技术选型

技术 | 说明 | 官网
----|----|----
Vue | 前端框架 | [http://u.720life.cn/g/1c3db3fec6433a3fb191bb48af91f3bb58506fe6fda7fee3bc588c5d923330e1c904bf70386b6091645a6f5ab81d3fdd) 
Vue-router | 路由框架 | [http://u.720life.cn/g/7bedfe02707a57b283aa65bf169b40682a747d47f5d654d0391ab02f5151f6a03c3ab5f7e085ce9133be51985f7a94f79719da142a24b88fbb6c7b6a243cc67d) 
Vuex | 全局状态管理框架 | [http://u.720life.cn/g/acea3f53396a46112876052cae0a3648c5a594267fbc558f22b31edb28156520f4932623b796052b99ffb6574ddfbab4) 
Element | 前端UI框架 | [http://u.720life.cn/g/5fa51553afae358345e9f20b5a6e741523048e74b4ab81a1119ff03e2a07a7154ba078769a1a29225192a35e1a18c9deec19dc418558328a3ac42e304a77cc3e) 
Axios | 前端HTTP框架 | [http://u.720life.cn/g/54145d0471d91890860f7f8463c030466f36394fcc65d84c36d6a174db10c95c9163df79a39202f44f7dc6d929540394ae045d22ba45c27e27c684750d8aaf89) 
v-charts | 基于Echarts的图表框架 | [http://u.720life.cn/g/04bb650c6b9547d2ac7f61bed3e715035cf29f6075d5c54d9b717103eaed057bea64138fb017dc16412506e31d9f98005867a7a7996d69717f2e8bbe9d216724) 
Js-cookie | cookie管理工具 | [http://u.720life.cn/g/54145d0471d91890860f7f8463c0304601a18a0a98543c227ccab0f66e611f00e60f5a3254a2e9a1676de9767237f3683d242dd739f61d59533d26bb1f27bb30def8466b3c044e17c50697bfa474e520) 
nprogress | 进度条控件 | [http://u.720life.cn/g/54145d0471d91890860f7f8463c0304621051bfe8a14df709920d1b59773b4a178cbb80671632dcda64a40ff135fc618e5eaf957774ec611aee5322d925b7e23adfbd89c4f07e6bfb0890271546c30aa) 
vue-element-admin | 项目脚手架参考 | [http://u.720life.cn/g/54145d0471d91890860f7f8463c0304603c6efa7d0c1ce77680f5b6f938bd6cef34ff16f07f41bac24a733d838a1bd0f9561a816bb01de15270e8843b8eab9dcec7a7e86efe4a39715502c262eecdd9ffe381e236b0cb705f760f24dfcbe3afd) 

### 项目布局

``` lua
src -- 源码目录
├── api -- axios网络请求定义
├── assets -- 静态图片资源文件
├── components -- 通用组件封装
├── icons -- svg矢量图片文件
├── router -- vue-router路由配置
├── store -- vuex的状态管理
├── styles -- 全局css样式
├── utils -- 工具类
└── views -- 前端页面
    ├── home -- 首页
    ├── layout -- 通用页面加载框架
    ├── login -- 登录页
    ├── oms -- 订单模块页面
    ├── pms -- 商品模块页面
    └── sms -- 营销模块页面
```

## 搭建步骤
- 下载node并安装：[http://u.720life.cn/g/6dd25ec2eceebbb6348ad519a7343cbcc5c8f7ce82ebe0f8d2124294c3523c4f4db1bc94719789402538831ec8d524c4c0143c157d71248a7746d0de9baea229ddc05a90fd364618297d32d9dee8bc24bc20cc686c2651895f7d81efcee27416a3c52f0f6d7e97ccfa57498305e02c26 
- 该项目为前后端分离项目，访问本地访问接口需搭建后台环境，搭建请参考后端项目[传送门](http://u.720life.cn/g/54145d0471d91890860f7f8463c03046792cbfb2e1cb72d9aec12faeaa3f53b493edd723f853ea93b9a80ae2239380cc 
- 访问在线接口无需搭建后台环境，只需将config/dev.env.js文件中的BASE_API改为[http://39.98.190.128:8080](http://39.98.190.128:8080)即可;
- 克隆源代码到本地，使用IDEA打开，并完成编译;
- 在IDEA命令行中运行命令：npm install,下载相关依赖;
- 在IDEA命令行中运行命令：npm run dev,运行项目;
- 访问地址：[http://u.720life.cn/g/e71094f6077cb9592da5b56893f0ad140fa29a940ff7f08955ef7e9bd912a44df8e3205c0a6620243bd2602cdb3647c8)  即可打开后台管理系统页面;
- 如果遇到无法运行该命令，需要配置npm的环境变量，如在path变量中添加：C:\Users\zhenghong\AppData\Roaming\npm。

## 许可证

[MIT](http://u.720life.cn/g/54145d0471d91890860f7f8463c03046792cbfb2e1cb72d9aec12faeaa3f53b4f9efd9a81e2cdd5b348c56cc4067ca311dc77a05aaa34ab032a2e40ae5bae915) 

Copyright (c) 2018-2019 macrozheng



 # 良心友情链接

[腾讯QQ群快速检索](http://u.720life.cn/s/8cf73f7c)

[软件免费开发论坛](http://u.720life.cn/s/bbb01dc0)