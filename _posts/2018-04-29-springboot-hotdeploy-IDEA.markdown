---
layout: post
title: springboot-hotdeploy-IDEA
date: 2018-04-30 12:21:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: i-rest.jpg # Add image post (optional)
tags: [Holidays, lonema]
---
资料链接：
[Intellij IDEA 4种配置热部署的方法](https://www.cnblogs.com/jcook/p/6910238.html)

[springboot 在idea中实现热部署](https://blog.csdn.net/xusheng_Mr/article/details/78771746) 

[基于Maven的SpringBoot项目实现热部署的两种方式](https://blog.csdn.net/tengxing007/article/details/72675168)

[Spring Boot 系列（六）web开发-Spring Boot 热部署](https://www.cnblogs.com/magicalSam/p/7196355.html)

[SpringBoot开发常用技术整合...](https://www.imooc.com/video/16717)

配置文件（application.properties/application.yml）文件中配置参数（properties文件为例）：

```
关闭缓存，页面即时刷新
freemarker模板引擎：
spring.freemarker.cache=false
thymeleaf模板引擎：
spring.thymeleaf.cache=true
application.properties文件配置热启动参数热启动生效
spring.devtools.livereload.enabled=true
设置重启的目录，添加哪个目录的文件需要restart
spring.devtools.restart.additional-paths=src/main/java
排除哪个目录下的文件不需要restart
spring.devtools.restart.exclude=static/** ,public/**
classpath目录下的WEB-INF文件夹内容修改不重启
spring.devtools.restart.exclude=WEB-INF/**
```

