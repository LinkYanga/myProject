# 小米商城电商系统
> 基于 Go 语言开发的轻量级电商系统，实现商品展示、用户管理、权限控制、验证码服务等核心电商功能

## 项目地址
- GitHub 仓库：https://github.com/LinkYanga/myProject
- 仓库克隆地址（SSH）：git@github.com:LinkYanga/myProject.git

## 项目简介
myProject 是一套基于 Go 语言构建的前后端分离电商系统，聚焦小米商城核心业务场景，涵盖用户端交互、服务端业务逻辑、权限管控、验证码等基础能力，是 Golang 后端开发者学习电商系统开发的实践项目。

## 技术栈
- 核心语言：Go
- Web 框架：Gin
- 微服务框架：Go-Micro
- 数据库：MySQL（基于 GORM 操作）
- 数据序列化：Protobuf
- 容器化：Docker
- 缓存：Redis

## 项目结构
- myProject/
- ├── xiaomishop/
-  │   ├── server/              # 服务端模块
-  │    │   ├── rbac/            # 权限管理服务
-  │    │   └── captcha/         # 验证码服务
-  │    └── client/              # 客户端模块
-  │        ├── ginshop/         # 商城前端(基于Gin框架)
-  │        ├── captcha-client/  # 验证码客户端
-  │        └── ginWebApi/       # Web API服务

## 核心功能
- RBAC 权限管理：基于角色的访问控制，支持角色创建、权限分配、接口级鉴权
- 验证码服务：生成图形 / 短信验证码，提供验证接口，防范恶意请求
- 商品管理：商品分类、列表展示、详情查询、库存管理等核心电商功能
- 用户系统：用户注册、登录、信息修改
