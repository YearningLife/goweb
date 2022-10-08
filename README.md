# goweb

### 1. 演示

- 启动

  ![启动](./picture/1-startup.gif)

- 界面

  ![界面演示](./picture/2-demo.gif)

### 2. 官网项目: [Go 语言之旅 (go-zh.org)](https://tour.go-zh.org/welcome/1)

### 3. 练习项目: [Go by Example 中文版 (gobyexample-cn.github.io)](https://gobyexample-cn.github.io/)

### 4. 参考博客: [李文周的博客 | 总结Go语言学习之路](https://www.liwenzhou.com/)

### 5. gin 官方文档: [文档 | Gin Web Framework (gin-gonic.com)](https://gin-gonic.com/zh-cn/docs/)

### 6. gorm 官方文档: [GORM 指南 | GORM - The fantastic ORM library for Golang, aims to be developer friendly.](https://gorm.io/zh_CN/docs/)

### 7. 参考视频: https://www.bilibili.com/video/BV1gJ411p7xC?p=27

### 8. 更新日志:

- goweb22 验证 `database/sql` 标准库 , 参考连接: [Go语言操作MySQL | 李文周的博客 (liwenzhou.com)](https://www.liwenzhou.com/posts/Go/go_mysql/)
- goweb23 验证 `sqlx` 使用, 参考连接: [sqlx库使用指南 | 李文周的博客 (liwenzhou.com)](https://www.liwenzhou.com/posts/Go/sqlx/)
- goweb24 验证 `redis`使用
- goweb25_zap 验证`zap`日志
- goweb26_gin_zap 验证`zap日志` 及 `gin框架中的日志`集成
- goweb27_viper 验证 `viper`环境变量
- goweb28_shutdownAndReboot 验证`优雅关机和重启`, 重启-windows无法实现, 须在unix machine 上才可以
- goweb29_app_framework 脚手架项目, 了解项目的基本构建方式
- goweb30_app_framework2 脚手架项目优化, 使用更加简介高效的配置方式,`mapstructure`映射
- goweb31_flags 使用`os.Args` 和 `flag` 参数化启动, 同时将 `goweb30_app_framework2`  的启动方式调整为配置加载方式
- goweb32_bells-of-ireland 开启新项目`bells-of-ireland`, 准备写一个技术博客, 项目寓意: 好运气
  - 运用`snowflake` [链接](https://cdmana.com/2022/123/202205031931453727.html), 生成用户唯一ID
  - `2022-10-01`更新
    - a. 实现用户注册,
    - b. main.go优化;   
    - c. 参考`validator`[库](https://github.com/go-playground/validator), 实现请求参数校验
    - d. 参考博客: [validator库博客](https://www.liwenzhou.com/posts/Go/validator_usages/)
    - e. 实现用户注册和登陆功能
    - f. 实现统一的响应体
    - g. 实现JWT鉴权
    - h. 实现有效期内登录: 还有两个功能未实现: 1).accessToken未过期时, 刷新token;2)实现同一时间内只能一台设备登录

