Odoo-yfc 说明
----

## 基于Odoo17的二次开发
- 实现前后端完全分离
- 使用`NextJS`作为前端开发框架
- 基于`json-rpc`的数据访问
- 一个产品信息管理系统（PIM）————应用于汽车配件商业领域企业
- 基于`PIM`重构`Odoo`的前端应用，重新集成`ERP`

## 注意事项
- `odoorc`为`odoo-server`的配置文件（开发者之间不共享）
- 项目中引入了`poetry`，主要用于虚拟环境管理，不作为`python`依赖管理的工具。
- `aiofc_addons` 放置二次开发的模块
- `local_addons` 放置测试类模块，仅在开发环境下使用，不在生产环境部署
## 其他
- 前端项目地址：
  - https://github.com/7wanaio/auto-parts-sys.git
  - git@github.com:7wanaio/auto-parts-sys.git
