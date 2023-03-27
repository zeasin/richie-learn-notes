# SpringBoot启动全流程
[参考](https://blog.csdn.net/weixin_43868685/article/details/119174084)
### 一、自动装配
[参考](https://blog.csdn.net/qq_27028647/article/details/129266436)
自动装配大致过程如下：

+ 获取到组件（例如spring-boot-starter-data-redis）META-INF文件夹下的spring.factories文件

+ spring.factories文件中列出需要注入IoC容器的类

+ 将实体类注入到IoC容器中进行使用
![img](https://img-blog.csdnimg.cn/img_convert/6df0a7dbafb988daec801e9700fcc71a.png)
**核心类**
+ AutoConfigurationImportSelector

### 二、SpringApplication.run()