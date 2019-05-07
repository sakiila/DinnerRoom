# DinnerRoom
一个前台结算，前台点餐，后台综合信息管理，后厨配菜的完整项目

部署说明：
1.创建mysql数据库，数据库名称为dinner，导入数据建表语句
2.项目导入IDEA或Eclipse开发工具，修改数据连接配置文件DinnerRoom/resource/applicationContext.xml中数据库连接配置（22-26行）
4将项目放入web容器（tomcat）中启动

运行环境
Eclispse/Idea+JDK1.8+Mysql+Tomcat8
项目技术
Spring+Struts+hibernate+Bootstrap+Jquery

前台账户：lisi   lisi

后台账户：admin   admin

点餐页面：http://localhost:8080/DinnerRoom/diancan

后台登录页面：http://localhost:8080/DinnerRoom/login.jsp

后厨配菜页面：http://localhost:8080/DinnerRoom/houchu.jsp
