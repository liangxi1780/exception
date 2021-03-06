# ddd-cargo
领域驱动货物需求示例

## 需求-节选自《领域驱动设计第7章》
假设我们正在为一家货运公司开发新的软件，最初的需求包括三项基本功能：
1. 事先预约货物
2. 跟踪客户货物的主要处理流程
3. 当货物到达其处理过程中的某个位置时，自动向客户寄送发票

## DDD、CQRS架构图
![](./ddd.png)

## DDD、CQRS代码结构
![](./ddd_package.png)

## 示例
ddd-cargo-example是一个单Maven模块的项目，DDD+CQRS落地示例，基于SpringBoot开发。

下面我们以ddd-cargo-example为例来演示如何落地：

1. 修改`/ddd-cargo-example/src/main/resources/application.properties`数据库连接

2. 初始化数据库脚本文件`/ddd-cargo-example/mysql_init.sql`

3. 运行`/ddd-cargo-example/src/main/java/com/deepoove/cargo/CargoApplication.java`

4. 浏览器访问`http://u.720life.cn/g/8bd8603eb20ab01233f1f6fdd61cc4fd8100dab7bc49da125fe4ba02165fade290d555c3409bd6b40222cd69558c96e0 

#### 查询Cargo
![](./cargo_home.png)
#### 预订Cargo
![](./cargo_book.png)
#### Cargo事件
![](./cargo_event.png)
#### 追踪Cargo
![](./cargo_track.png)

## 文章
Blog：[领域驱动设计DDD和CQRS落地](http://u.720life.cn/g/e14ef8becd7aca957e0312c8738391e0e86917ea2ce705c489fb4917dc0728e6c25f2dcf6b3d3a038301cf19abc793cd) 




 # 良心友情链接

[腾讯QQ群快速检索](http://u.720life.cn/s/8cf73f7c)

[软件免费开发论坛](http://u.720life.cn/s/bbb01dc0)