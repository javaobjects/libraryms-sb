# 图书管理系统服务端

#### 项目说明

- 此项目为图书管理系统后台，使采用的是springboot+mybatis等技术实现数据持久化以及api服务调用，
前台使用vue.js,vue-resource,vue-router,iView2.0UI框架,vue-quill-editor等技术实现前台页面，前台地址是:[Vue-iView-Demo](https://github.com/yangyuscript/Vue-iView-demo.git)
- 由于前期没有上传后台项目springboot的application.porperties文件，故此次一并上传，大家就不必到issue中寻找了。
#### 配置环境
1. Jdk1.8.0 161
2. Mysql-5.5.27
3. Apache-maven-3.9.0
#### 开发工具
1. IntelliJ IDEA 2022.3.2
2. Navicat Premium 12
3. Git 2.24.1
#### 开发环境
Windows
#### 项目启动
- 1.数据库：mysql5.6执行以下脚本,前台项目下脚本文件--db_appapidemo.sql  （数据库脚本在前台项目下，请移步：[Vue-iView-Demo](https://github.com/yangyuscript/Vue-iView-demo.git)）
- 2.后台启动：导入项目，进入控制台，到项目所在路径，执行命令：mvn clean spring-boot:run
- 3.前台启动：导入项目，进入控制台，到项目所在路径，执行命令：npm run dev，访问地址：http://localhost:8075  进入到登录界面，打开数据库中t_reader表获取用户名和密码
#### 包的结构
```agsl
 +- libraryms-sb
    +- .mvn
        +- wrapper
    +- src
    |   +- main
    |   |    +- java
    |   |    |    +- com
    |   |    |    |    +- lin
    |   |    |    |    |    +- appapidemo
    |   |    |    |    |    |    +- controller -- 控制器类 负责接收和处理HTTP请求
    |   |    |    |    |    |    +- mapper -- MyBatis框架的数据访问层
    |   |    |    |    |    |    +- model -- 
    |   |    |    |    |    |    +- util -- 
    |   |    |    |    |    |    +- AppapidemoApplication.java -- 应用程序入口类
    |   |    |    |    |    |    +- CorsConfig.java -- 
    |   |    |    |    |    |    +- Swagger2.java -- 
    |   |    +- resources
    |   |        +- application.properties -- 应用程序的配置信息
    |   +- test -- 测试代码
    |  	|	+- java
    |  	|	    +- com
    |  	|	        +- lin
    |  	|	            +- appapidemo
    +- target -- Maven建项目时自动生成的目录
    +- .gitignore -- 指定需要 Git 忽略的文件或目录
    +- LICENSE -- 开源软件的授权协议
    +- mvnw
    +- mvnw.cmd
    +- README.md -- 项目的相关信息文档
```

#### 效果展示
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/1.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/2.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/3.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/4.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/5.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/6.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/7.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/8.png?raw=true)
![](https://github.com/yangyuscript/Vue-iView-demo/blob/master/static/9.png?raw=true)


#### tip
鉴于star该项目的同学越来越多，鄙人觉得应当补充以上信息供大家交流学习，如果大家有任何建议均可issue，一定尽一切办法解决各位的问题，希望大家一起进步，oh yeah!

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
