
# Jeexo

## 简介

Jeexo是从[JeeSite](http://git.oschina.net/thinkgem/jeesite)扩展出来的一个快速开发平台,

是一个提供了通用模块的快速开发脚手架,省去通用功能重复开发而设计的。

## 帮助文档

1.下载代码： Git clone  https://github.com/jwangkun/jeexo

2.导入/db/jeexo.sql文件至您的数据库

3.导入Maven项目到Idea/Eclipse

4设置数据库连接，配置文件位于site-core/src/main/resources/jeesite.properties，Druid配置了加密，所以密码用的是密文 java -cp druid-1.0.16.jar com.alibaba.druid.filter.config.ConfigTools you_password 用上面这种方式把密码生成之后，把jdbc.password和jdbc.publickey都拷贝到配置文件里面

5.在根目录下编译项目 mvn clean install package

6.启动项目 进入site-core目录，执行mvn jetty:run即可

#系统截图

![](http://ww1.sinaimg.cn/large/8bb65895ly1fdljmc5ul4j212l0hxn09)


![](http://ww1.sinaimg.cn/large/8bb65895ly1fdljmc2z1mj212d0hm0tp)


![](http://ww1.sinaimg.cn/large/8bb65895ly1fdljmc6j5rj211c0hzmy8)