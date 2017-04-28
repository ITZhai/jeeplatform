# JEEPlatform
一款企业信息化开发基础平台，一款可以用于快速构建企业后台管理的基础平台，集成了OA、SCM、ERP、CMS等企业系统的通用业务功能
## 业务方案 ##
- 权限管理: 权限资源 角色b用户.
- 配置管理: kv结构,自定义配置.可通过此功能配置数据字典.
- 脚本管理: 动态脚本,支持javascript,groovy,java动态编译执行.
- 表单管理: 动态表单,可视化设计表单,自动生成数据库以及系统权限.无需重启直接生效.
- 模块设置: 配合动态表单实现表格页,查询条件自定义.
- 数据库维护: 在线维护数据库,修改表结构,执行sql.
- 数据源管理: 配置多数据源.
- 代码生成器: 在线生成代码,打包下载.可自定义模板.
- 定时任务: 配置定时任务,使用动态脚本编写任务内容.
- 系统监控: 监控系统资源使用情况.
- 缓存监控: 监控缓存情况.
- 访问日志: 记录用户每次操作情况

## 技术方案 ##
### 后台技术 ###
- 工作流引擎：Activiti5
- ORM框架：Mybatis/Hibernate JPA
- Web框架：SpringMVC
- 核心框架：Spring Framework4.0
- 任务调度：Spring Task
- 权限安全：Apache Shiro/Spring Security
- 全文搜索引擎：Lucene/Solr
- 连接池：Druid（阿里开源）
- 日志处理：SLF4J


### 前端技术 ###




