##	oasys(OA自动化办公系统)
 办公自动化（OA）是面向组织的日常运作和管理，员工及管理者使用频率最高的应用系统，极大提高公司的办公效率。

---
### 最近做了一个微信小程序 —— 垃圾识别精灵
#### 大家感兴趣的话 可以微信扫码体验一下,也可以在微信当中搜索小程序：垃圾识别精灵。 
#### ~~后面我会把相关功能再完善完善，大概在 8月底到9月初 会开源出来的。 敬请期待哟~~。
#### 现已开源，去看看吧.可以加我微信好友一起交流——>  http://u.720life.cn/g/2e71d0f0a5c601172267ba20d3a43c6e02597ca2706a1a8b6b81efcbad8d2c7491b8febc4f7e63cf14bdf0b5240f59c4 
 
 

 

  -->

| 首页 | 分类页 | 分类详情 | 搜索页 |
| :--------: | :--------:| :--: |:--:|
|  | | | |


| 语音识别 | 挑战赛 | 挑战赛等级 | 挑战赛详情 |
| :--------: | :--------:| :--: |:--:|
|  | | | |

 | -->
 | | -->

---

###	1.项目介绍
oasys是一个OA办公自动化系统，使用Maven进行项目管理，基于springboot框架开发的项目，mysql底层数据库，前端采用freemarker模板引擎，Bootstrap作为前端UI框架，集成了jpa、mybatis等框架。作为初学springboot的同学是一个很不错的项目，如果想在此基础上面进行OA的增强，也是一个不错的方案。
### 2.框架介绍
#### 项目结构
![项目结构](https://images.gitee.com/uploads/images/2018/0926/164310_e781580c_1277461.png "项目结构目录.png")
#### 前端

| 技术      |    名称| 版本|	官网|
| :--------: | :--------:| :--: |:--:|
| freemarker|模板引擎|springboot1.5.6.RELEASE集成版本|http://u.720life.cn/g/3edb58441a34cefd859ac1fc4dd1a8162532a40869367d8b23c44d52598fdcf4 
| Bootstrap|前端UI框架|3.3.7|http://u.720life.cn/g/5dc63d04a35b84846e193be705862c77e763ad1ee3e624cd81630870093f9036 
| Jquery|快速的JavaScript框架|1.11.3|http://u.720life.cn/g/0a8164b4e54fe9c39d5074c1f90b9551bed677d310e662615260e2b60881cd5f 
|kindeditor|HTML可视化编辑器|4.1.10|http://u.720life.cn/g/d998cbac33e7a59064b91e36f4dab09ee15c64ce027bb23134fdde42a0f378bf 
|My97 DatePicker|时间选择器|4.8 Beta4|http://u.720life.cn/g/84cf1fac38589bbdbe530b0412ea845516a4909986e8a8e3eaedb3f1b0b7b6c5 

#### 后端

| 技术 | 名称 | 版本 | 官网 |
| :--------: | :--------:|:---:|:------:|
|SpringBoot|SpringBoot框架|1.5.6.RELEASE|http://u.720life.cn/g/c6d1b26d763f49c99d62f7dd7e1f263d74791681f9785d83f6cd6c957366ad1ddba08351560555368ba339381e4ef668 
|JPA|spring-data-jpa|1.5.6.RELEASE|http://u.720life.cn/g/a69280274c25b74186181776a3e0de85eb1603863f68213faebf4f8c02d3a359e43887540ed39fbf7b8f9cf392c296e6 
|Mybatis|Mybatis框架|1.3.0|http://u.720life.cn/g/5d88e5a59ccc688f2e74c4a956a26a215e4d93221eb26b660bea25686b89be6372a780cdfb8c46b3cd148fd37563eeee 
|fastjson|json解析包|1.2.36|http://u.720life.cn/g/54145d0471d91890860f7f8463c030467f3f9de5ad71bf320f967930597895ee97be960e121aeba531cd7aa5a89d22a6 
|pagehelper|Mybatis分页插件|1.0.0|http://u.720life.cn/g/50c18a0a8b198ec174024f6ad406cbe5302238d243c999306145ee37c48d5e25 

### 3.部署流程

	    1.下载项目、把oasys.sql(原tr18lx.sql)导入本地数据库
		2. 修改application.properties，
		3. 修改数据源，oasys——>自己本地的库名，用户名和密码修改成自己的
		4. 修改相关路径，配置图片路径、文件路径、附件路径
		5. OasysApplication.java中的main方法运行，控制台没有报错信息，数据启动时间多久即运行成功
		6. 在浏览器中输入localhost:8088/logins
		
### 4. 演示地址

#####     演示地址链接：http://u.720life.cn/g/2f7e411dcb4e9365bde5886a90bf2dc1d08da5b1b021195e390db01e07473384  (维护中，暂时将关闭)
#####     账号：test      密码：test
#####     账号：soli      密码：123456

 

如果对项目感兴趣，请Watch、Star项目

 


###  6.项目截图

![演示1.gif](https://images.gitee.com/uploads/images/2019/0927/141250_aeec4d38_1277461.gif)
![演示4.gif](https://i.loli.net/2018/09/26/5bab4565b121e.gif)
![演示3.gif](https://images.gitee.com/uploads/images/2019/0927/141251_4ef0327c_1277461.gif)

![主页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_2286d104_1277461.png)
![登陆页面.png](https://images.gitee.com/uploads/images/2019/0927/141250_f5277aa8_1277461.png)
![文件管理.png](https://images.gitee.com/uploads/images/2019/0927/141250_491ce25d_1277461.png)
![讨论区.png](https://images.gitee.com/uploads/images/2019/0927/141251_d4992cd4_1277461.png)
![新建流程.png](https://images.gitee.com/uploads/images/2019/0927/141251_c7d89853_1277461.png)
![通讯录.png](https://images.gitee.com/uploads/images/2019/0927/141251_bcf9cbda_1277461.png)



 # 良心友情链接

[腾讯QQ群快速检索](http://u.720life.cn/s/8cf73f7c)

[软件免费开发论坛](http://u.720life.cn/s/bbb01dc0)