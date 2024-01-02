# JavaWeb网上购书系统

#### 介绍
采用JSP、Servlet、MySQL、Tomcat8.0开发的网上购书系统。

#### 软件架构
网上书城主要功能如下：

(1)    前台（客户购买）部分：

①   用户管理：注册会员、登录、激活、退出、修改密码；

②   分类显示：显示所有1级和2级分类；

③   图书显示：按分类查询图书、通过关键字搜索图书、高级搜索图书、查看某本图书的详细；

④   购物车管理：向购物车中添加图书、修改购物车中图书数量、删除购物车中图书、我的购物车；

⑤   订单管理：通过购物车中图书生成订单、查看我的订单、查看某个订单的详细、订单支付、确认收货、取消未付款订单。

(2)    后台（管理员管理）部分：

①   分类管理：查看所有分类、添加1级分类、添加2级分类、修改1级分类、修改2级分类、删除1级分类、删除2级分类；

②   图书管理：按分类搜索图书、高级搜索图书、添加新图书、查看图书详细信息、编辑图书、删除图书；

③   订单管理：按状态搜索订单、查看订单详细信息、取消订单、发货；

本系统采用的是JSP、Servlet、MySQL、Tomcat8.0开发，用Dreamweaver进行前台网页界面设计、采用JDBC方式与后台数据库进行连接，完成数据的添加、修改、删除、查询等功能。由于JSP、Servlet功能强大，而MySQL灵活易维护在开发方面具有方便快捷、使用灵活的特点，以及目前的广泛实际应用，因此使用JSP、Servlet、MySQL是开发轻平台的最佳组合从而说明本系统在技术方面可行。
### 前台界面
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114057_8a862c33_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114105_b00e5b4e_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114113_e90f006b_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114119_dfe17762_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114127_a85def9c_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114133_b9eec63e_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114144_80989657_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114152_e2f60e39_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114159_d7faf535_5340558.png "屏幕截图.png")
### 后台界面
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114211_92975531_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114235_af11c761_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114242_3888677a_5340558.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114248_fde3599a_5340558.png "屏幕截图.png")
### 数据库
数据库表设计主要是把概念结构设计时设计好的基本E-R图转换为与选用DBMS产品所支持的数据模型相符合的逻辑结构。它包括数据项、记录及记录间的联系、安全性和一致性约束等等。导出的逻辑结构是否与概念模式一致，从功能和性能上是否满足用户的要求，要进行模式评价。
![输入图片说明](https://images.gitee.com/uploads/images/2021/0621/114307_c92d03d1_5340558.png "屏幕截图.png")






