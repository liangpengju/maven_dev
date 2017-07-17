
# Maven多模块项目开发实例
maven_dev中包含父聚合项目gseem-parent,没有实际的内容，主要是pom.xml文件中集中定义依赖版本号、依赖包管理、插件管理、插件等可以继承的元素。

gseem-manage是一个多模块的聚合项目，包括4个子模块，parent都是gseem-manage；

gseem-manage-pojo是项目实体类模块，打包方式为jar；

gseem-manage-mapper是项目数据库操作dao模块，对应于mybatis的mapping中的xml文件，打包方式为jar，依赖于gseem-manage-pojo模块；

gseem-manage-service是项目业务逻辑服务模块，包括接口和实现，打包方式为jar，依赖于gseem-manage-mapper模块；

gseem-manage-web是项目的静态资源、jsp动态页面模块，包括接口和实现，打包方式为jar，依赖于gseem-manage-service模块；


# 简书
http://www.jianshu.com/u/441d207955f2
# Java技术日志 微信订阅号
![Java技术日志](http://upload.jianshu.io/collections/images/488450/javalog.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/240/h/240)

