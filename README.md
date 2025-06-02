基于fx的快速开发框架

```
// 创建一个模型
go run . gen model {name}
// 创建一个模块
go run . gen moudule {name}
// 创建一个服务&路由
go run . gen service {package_name}/{service_name} {model_name}
or
go run . gen service {service_name} {model_name}
```
前端生成有待完善
