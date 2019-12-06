# Java-tourism-ecommerce-project
This project is a tourism e-commerce project, with the main functions of booking hotels, air tickets and apps. Mainly to provide a platform for such a tourism business
# 项目整体描述
该项目为旅游电商类项目，这个项目有点像咱们现在所能看到的“携程旅行”他们所提供的一些功能，比如说：可以订酒店、订机票、在app上也可以，就是为这样一个旅游类业务提供一个这样的平台。
# 采用业务架构
基于java分布式架构
后端用的是SSM，就是SpringMVC+Mybatis，后端还有一块使用solr做的，大部分的任务的话，就是正常的这些增删改查业务处理。还有另外一块为了提高搜索的效率，在项目当中引入了solr搜索引擎，这个是单独拆出来去做的，后端的话主要是这两块技术。
# 业务模块
用户模块、支付模块、登录模块、酒店模块、机票模块等
# 主要技术
SSM框架、前后端分离、solr搜索引擎技术、Token登录、Maven多项目构建、Nginx反向代理实现负载均衡、Redis缓存、代码生成器、图片自动裁剪技术(Tengine+Lua+GraphicsMagick)

