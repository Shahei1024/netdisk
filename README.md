# netdisk

作者联系方式,wechat:13469882774
刚学习JDBC做了简易网盘项目，可以拿来练练手

运行环境：windows server 2012

开发环境：IDEA 2020.3

环境：MySQL8.0.22\Tomcat9.0.40\Maven

jdk版本：jdk14.0

jar包依赖：略

新用户首次登录需要注册用户名：DBUtils工具类写入数据库，第二次登陆时通过用户名密码登录进入主界面

相比较于version-1仅仅只有上传下载功能的web应用，version-2做了如下改进：取消了用session进行客户端持久性连接，改用用户名+密码的方式来管理用户；version-2增加了数据库端，可以存放用户信息。
