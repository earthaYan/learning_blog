---
---

使用 go 开发 web 应用常用技术栈组合：go+gin+gorm

## 预期：

1. viper 读取配置文件
2. Gin 中间件
3. JWT
4. Bcrypt
5. Gin-Cors 和跨域
6. Go-redis,redis 以及缓存
7. Go 的基础知识

## Go 语言适合的场景

非 GUI 开发的主流选择

优点：
简洁性，高效的并发处理，较好的性能，丰富的标准库和第三方库，社区活跃，适合用于 web 后端开发，有很多好的 web 框架如：Gin,Beego,Fiber

## Gin

本质：使用 GO 语言开发的 web 框架，可以让开发者高效构建应用程序
特点：

- 高性能
- 中间件支持
- 路由分组

## Gorm

本质：ORM（对象关系映射）库,结构体与数据库中的表对应，将结构体的字段与数据库的列对应，从而可以通过结构体直接与数据库进行交互
优势：

- 简单易用
- 自动迁移
- 支持多种数据库

Gin 和 Gorm 经常会结合使用

## viper 读取配置文件