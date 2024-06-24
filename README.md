# 仓库介绍
此仓库只用于打卡学习

# 苍穹外卖项目介绍

> 苍穹外卖详细教程地址: [黑马程序员最新Java项目实战《苍穹外卖》](https://www.bilibili.com/video/BV1TP411v7v6/)

《苍穹外卖》项目的定位是一款为餐饮企业（餐厅、饭店）定制的软件产品。该项目是一个在线外卖订购系统，顾客可以通过网站或者手机 App 订购餐点。该项目可以提供以下的功能：

用户可以注册和登录账号，浏览餐厅列表，选择菜单，并下单和支付；
餐厅可以注册账号并进行菜单管理，接收和处理订单；
后台管理员可以管理餐厅和用户账号信息，处理订单和投诉，生成销售报表等。
苍穹外卖项目需要具备以下的技术要求：

网站和小程序的设计和开发；
数据库管理系统的设计和实现；
支付系统的接入和开发；
苍穹外卖项目的优点是方便快捷、节省时间，满足了人们日常用餐的需求；缺点是可能存在繁琐的细节和服务质量的不确定性。

## 项目架构
项目的整体架构分为前端和后端，开发模式为前后端分离开发模式：
![image](https://github.com/Gawainren/sky-take-out/assets/101917141/cb18a44b-9185-4869-af6b-a69c1757f800)

![image](https://github.com/Gawainren/sky-take-out/assets/101917141/00cb2b29-f87a-45f6-9ec9-6253d6d27893)


## 功能模块
项目中的业务功能模可划分为管理端和用户端两大模块，模块内业务功能细分如下：
![image](https://github.com/Gawainren/sky-take-out/assets/101917141/690d80e4-91ad-4307-b1fb-5e719733c99a)



项目管理端截图

|                                                              |                                                              |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/f21bc21e-2457-4b1c-b509-0a726dd159ed)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/3d205078-c96d-429d-b73e-ed7a650d5c78)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/ff34e907-ee6c-4c41-86d6-8bd4c2329866)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/0195cbb0-e972-4b1c-a4d4-917e29b268e3)|
|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/68fdcc9b-3c71-43d2-8c0b-fbba34ef3cde)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/bb189ff5-4eec-435d-b496-b86268e0b39d)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/2df0ee77-b3d7-491e-b057-92ce5707e436)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/e4854152-3335-4e5c-87cd-3fd00e239ef7)|
|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/ebe9a45d-2d23-44ff-acd3-474691e766cd)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/e69db599-b825-425c-9764-b6ded381ace4)|![image](https://github.com/Gawainren/sky-take-out/assets/101917141/6a100ba3-83b5-4e8c-ba66-b354402f5148)|





### 1). 管理端

餐饮企业内部员工使用。 主要功能有：

| 模块      | 描述                                                         |
| --------- | ------------------------------------------------------------ |
| 登录/退出 | 内部员工必须登录后，才可以访问系统管理后台                   |
| 员工管理  | 管理员可以在系统后台对员工信息进行管理，包含查询、新增、编辑、禁用等功能 |
| 分类管理  | 主要对当前餐厅经营的 菜品分类 或 套餐分类 进行管理维护， 包含查询、新增、修改、删除等功能 |
| 菜品管理  | 主要维护各个分类下的菜品信息，包含查询、新增、修改、删除、启售、停售等功能 |
| 套餐管理  | 主要维护当前餐厅中的套餐信息，包含查询、新增、修改、删除、启售、停售等功能 |
| 订单管理  | 主要维护用户在移动端下的订单信息，包含查询、取消、派送、完成，以及订单报表下载等功能 |
| 数据统计  | 主要完成对餐厅的各类数据统计，如营业额、用户数量、订单等     |


​	

### 2). 用户端

移动端应用主要提供给消费者使用。主要功能有：

| 模块        | 描述                                                         |
| ----------- | ------------------------------------------------------------ |
| 登录/退出   | 用户需要通过微信授权后登录使用小程序进行点餐                 |
| 点餐-菜单   | 在点餐界面需要展示出菜品分类/套餐分类， 并根据当前选择的分类加载其中的菜品信息，供用户查询选择 |
| 点餐-购物车 | 用户选中的菜品就会加入用户的购物车，主要包含 查询购物车、加入购物车、删除购物车、清空购物车等功能 |
| 订单支付    | 用户选完菜品/套餐后，可以对购物车菜品进行结算支付，这时就需要进行订单的支付 |
| 个人信息    | 在个人中心页面中会展示当前用户的基本信息，用户可以管理收货地址，也可以查询历史订单数据 |


# 技术选型

关于本项目的技术选型， 我们将会从 用户层、网关层、应用层、数据层 这几个方面进行介绍，主要用于展示项目中使用到的技术框架和中间件等。项目中使用到的技术框架和中间件如下：

1. 用户层

   本项目中在构建系统管理后台的前端页面，我们会用到H5、Vue.js、ElementUI、apache echarts(展示图表)等技术。而在构建移动端应用时，我们会使用到微信小程序。

2. 网关层

   Nginx是一个服务器，主要用来作为Http服务器，部署静态资源，访问性能高。在Nginx中还有两个比较重要的作用： 反向代理和负载均衡， 在进行项目部署时，要实现Tomcat的负载均衡，就可以通过Nginx来实现。

3. 应用层

   SpringBoot： 快速构建Spring项目， 采用 “约定优于配置” 的思想， 简化Spring项目的配置开发。

   SpringMVC：SpringMVC是spring框架的一个模块，springmvc和spring无需通过中间整合层进行整合，可以无缝集成。

   Spring Task： 由Spring提供的定时任务框架。

   httpclient： 主要实现了对http请求的发送。

   Spring Cache： 由Spring提供的数据缓存框架

   JWT： 用于对应用程序上的用户进行身份验证的标记。

   阿里云OSS： 对象存储服务，在项目中主要存储文件，如图片等。

   Swagger： 可以自动的帮助开发人员生成接口文档，并对接口进行测试。

   POI： 封装了对Excel表格的常用操作。

   WebSocket： 一种通信网络协议，使客户端和服务器之间的数据交换更加简单，用于项目的来单、催单功能实现。

4. 数据层

   MySQL： 关系型数据库， 本项目的核心业务数据都会采用MySQL进行存储。

   Redis： 基于key-value格式存储的内存数据库， 访问速度快， 经常使用它做缓存。

   Mybatis： 本项目持久层将会使用Mybatis开发。

   pagehelper： 分页插件。

   spring data redis： 简化java代码操作Redis的API。

5. 工具

   git： 版本控制工具， 在团队协作中， 使用该工具对项目中的代码进行管理。

   maven： 项目构建工具。

   junit：单元测试工具，开发人员功能实现完毕后，需要通过junit对功能进行单元测试。

   postman： 接口测工具，模拟用户发起的各类HTTP请求，获取对应的响应结果。	
   	


