![gh_17810254f3db_258](https://github.com/user-attachments/assets/61edaf67-3e03-4f3b-9eaf-7efb5fce0cd2)


**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具:SSM + JSP + Tomcat8 + MySQL5.7 + Maven3 + IDEA2022

系统角色：管理员 + 洗衣房商家 + 普通用户

系统功能：管理员（商家管理、服务管理、用户管理、资讯管理、交易管理等）、商家（商品管理、订单管理、评论管理等）、普通用户（注册登录、查看资讯、洗衣清单、个人信息、模拟支付等）

#### 2.项目部署

##### 2.1 后端

- 创建数据库，导入项目中的sql

- 打开IDEA，导入项目xiyi-admin

- 根据本地数据库环境，修改数据库的连接信息src/main/resources/jdbc.properties 1-4行

- idea中配置tomcat，启动项目，运行 http://localhost:8080/ksxy

-  管理员账号/密码： admin/123456

##### 2.2 小程序端

- 打开微信开发工具

- 导入项目 xiyi-miniapp

- 选择测试号即可

- 登录。商家登录账号/密码： 李明1/123456  普通用户账号/密码： jack/123456， 或者查看user表和store表
