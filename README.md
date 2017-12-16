# java-Servlet
java Servlet购物车小项目，有商品列表和商品详情、购物车及浏览商品记录

## 注意事项
如果数据显示不出来的话，又没有报错的，那么问题就出现在连接数据库中了，在DBhelp.java中查看是否写错了账号和密码 再检查连接mysql驱动是否存在，在WEB-INF/lib中查看。
数据库命名为：shopping ;数据表：java-Servlet/WebContent/sql/items.sql

## 相关截图
![相关截图](show.gif)

## 出现问题
如果你是第一次用eclipse打开这个git clone的项目，部署到tomcat上发现选不了choose an existing server。出现这种问题，配置好你下载好的tomcat版本就行了（选择正确安装tomcat目录就行），配置好了后会发现在eclipse的项目同级目录上出现一个Servers目录
