# SpringBoot启动全流程

### 一、自动装配
自动装配大致过程如下：

+ 获取到组件（例如spring-boot-starter-data-redis）META-INF文件夹下的spring.factories文件

+ spring.factories文件中列出需要注入IoC容器的类

+ 将实体类注入到IoC容器中进行使用

**核心类**
+ AutoConfigurationImportSelector

### 二、SpringApplication.run()