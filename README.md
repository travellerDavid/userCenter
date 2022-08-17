# userCenter
## 项目地址(Repository)
https://github.com/travellerDavid/userCenter

## 概述(Overview)
本项目是以cas为基础的标准登录认证服务端程序，使用本项目可以快速创建企业内部的统一登录认证。
该服务端提供纯server端以及前后分离的模式，适用于各种不同的使用场景。

系统前端架构UI部分Layui为定制主题,系统后端架构主要是以Spring,shrio相关组件为基础搭建的。

本项目提供用户管理，用户权限管理，单点登录客户端信息管理，系统菜单管理等高级功能。

另外本项目采用国外最新的后端技术栈，也可以用作后端学习资料。

## 应用配置(Configuration)
依赖 redis,mysql

## 应用运行(Run)
本项目包含认证登录端(cas-server)和uc客户端(uc-servere)两个服务。
需要执行响应的初始化sql.
运行命令很简单就是mvn，自动进行maven clean install操作，并完成应用启动。
### 运行服务端(Run Cas Server)
```
cd cas-server

```

### 运行客户端(Run Uc Server)
```
cd uc-server
mvn
```

## 环境要求(Requirements)

- Java 8+
- Maven 3.0+
- Mysql 5.6+
- Redis 3+
- Tomcat 8+

## 主要依赖(Major dependencies)
- Spring Boot 2.3.6
- Swagger and Springfox
.
.
.

## 系统截图(Screenshots)


## 联系方式(Contact)
- Email: 981488858.com

