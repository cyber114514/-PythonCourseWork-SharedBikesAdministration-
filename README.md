## 北邮python大作业-共享单车管理系统
### 功能介绍
为了实现简单，与课程实验要求更贴近，故改写共享单车管理系统。
1. 权限管理
权限分为客户和staff，客户只能租赁和归还共享单车，staff可以删除和增加共享单车。
2. 租赁与归还
使用bool量存放租赁状态，当被占用时拒绝新的租赁请求。
3. 删除与增加
以id作为主键。
4. 后续可添加功能
租金计算、损坏报修、再做一个数据库来放订单

### 数据结构&对象关系
用户只有类user，其中身份字段代表权限。
单车类中包括id、租赁状态。

### 技术栈
#### 前端：(react)
#### 后端：python、flask框架
#### 数据库：pymysql

#### 5月20号补充:
1. 链接数据库定义游标过于重复，后期可封装减少冗余
