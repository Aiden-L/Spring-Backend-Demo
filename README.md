# Spring-Backend-Demo

#### 介绍
SpringBoot适用于API后端开发的demo，数据库支持使用MyBatis，项目管理采用Maven

项目包括基本配置，拿到即可使用的项目结构，包括GET，POST两种接口常见请求方式demo

#### 软件架构
* SpringBoot
* MyBatis
* FastJSON

#### Dependencies
* jdk~=1.8
* maven~=3.6
* MySQL

#### 安装教程

1. 进入`pop.xml`安装需要的包
2. [进入`application.yaml`配置文件修改mysql配置](src/main/resources/application.yaml)
```yaml
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/yespaper  # 远程连接地址和库名，如本地连接，只需修改“yespaper”为想连接库名即可
    username: root  # 你连接数据库用的用户名
    password: root  # 你连接数据库用的密码
```
3. 运行`WebApplication.java`

