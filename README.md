## 思维导航

* [前言](https://github.com)
* [项目介绍](https://github.com)
* [适用范围](https://github.com)
* [后端技术](https://github.com)
* [前端技术](https://github.com)
* [功能特点](https://github.com)
* [项目源代码](https://github.com)
* [项目运行效果](https://github.com)
* [项目源码地址](https://github.com)
* [优秀项目和框架精选](https://github.com)

## 前言


今天大姚给大家分享一套基于.NET 8\.0 \+ LayUI的快速开发框架，项目完全开源、免费（MIT License）且开箱即用：WaterCloud。



> 可完全实现二次开发让开发更多关注业务逻辑。既能快速提高开发效率，帮助公司节省人力成本，同时又不失灵活性。


:[westworld加速](https://tianchuang88.com)## 项目介绍


WaterCloud是一套基于ASP.NET 8\.0 MVC \+ API \+ SqlSugar \+ LayUI的快速开发框架，源代码完全开源、免费（MIT License），可以帮助你解决C\#.NET项目的重复工作（内置代码生成器），采用主流架构思想，容易上手，简单易学，学习成本低。


## 适用范围


WaterCloud适用于开发各类管理软件，如OA、ERP、BPM、CRM、WMS、TMS、MIS、BI、电商平台后台、物流管理系统、快递管理系统、教务管理系统等。


## 后端技术


* 核心框架：ASP.NET 8\.0、WEB API
* 定时任务：QuartZ，实现web控制
* 持久层框架：SqlSugar（支持多种数据库，复杂查询操作、多租户等）、Chloe(支持多种数据库，复杂查询操作，比较稳定)
* 安全支持：过滤器、Sql注入、请求伪造
* 服务端验证：实体模型验证
* 缓存框架：Redis/Memory（单点登录控制）
* 日志管理：Log、登录日志、操作日志
* 工具类：NPOI、Newtonsoft.Json、验证码、丰富公共类
* 其他：AutoFac、Swagger


## 前端技术


* js框架：jquery\-3\.4\.1、LayUI、LayUI mini（开源）
* 图标：Font Awesome 4\.7\.0及LayUI自带
* 客户端验证：LayUI verify
* 富文本编辑器：开源wangEditor、LayUI editor
* 上传文件：LayUI upload
* 动态页签：LayUI mini miniTab
* 数据表格：LayUI table、LayUI 开源 soul\-table组件
* 下拉选择框：LayUI select、xmselect
* 树结构控件：LayUI 开源 dtree
* 树状表格：LayUI 开源 treetable\-lay
* 穿梭框：LayUI transfer
* 页面布局：LayUI、LayUI mini
* 图表插件：echarts
* 日期控件：LayUI laydate
* 图标选择：LayUI 开源 IconPicker
* 省市区选择：LayUI 开源 layarea


## 功能特点


* 权限控制：基于RBAC的权限控制，支持到导航菜单、功能按钮、行级、列表级、表单字段级。
* 数据权限：精细化数据权限控制，实现不同人看不同数据。
* 代码生成：简单前后端代码生成，提高开发效率。
* 表单设计器：提供多种方式设计表单，包括动态表单拖拉式设计及自定义表单。
* 流程设计器：动态设计流程，节点及连线条件设计。
* 内容管理：已配置好wangEditor编辑器，易于使用。
* 文件管理：提供文件上传及下载功能。
* 常用类封装：包括日志、缓存、验证、字典、文件、邮件、Excel等。
* 响应式设计：支持电脑、平板、智能手机等设备，微信浏览器以及各种常见浏览器。
* 多租户：基于Database的多租户功能（SqlSugar支持）。
* 定时任务：基于quartz的定时任务功能（可以集群）。


## 项目源代码


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205730534-2064609502.png)


## 项目运行效果


设置`WaterCloud.Web`为启动项目，运行查看效果：


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205743190-1306267835.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205747349-1618930627.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205752980-84443766.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205758357-4978293.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205803880-1406272896.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205809123-1073420774.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205816569-1152363894.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205821283-272811807.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205826978-373471914.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205832330-568474282.png)


![](https://img2024.cnblogs.com/blog/1336199/202409/1336199-20240926205838188-20052109.png)


## 项目源码地址


更多项目实用功能和特性欢迎前往项目开源地址查看👀，别忘了给项目一个Star支持💖。


* 开源地址：[https://gitee.com/qian\_wei\_hong/WaterCloud](https://github.com)
* 在线文档：[https://gitee.com/qian\_wei\_hong/WaterCloud/wikis/pages](https://github.com)


## 优秀项目和框架精选


该项目已收录到C\#/.NET/.NET Core优秀项目和框架精选中，关注优秀项目和框架精选能让你及时了解C\#、.NET和.NET Core领域的最新动态和最佳实践，提高开发工作效率和质量。坑已挖，欢迎大家踊跃提交PR推荐或自荐（让优秀的项目和框架不被埋没🤞）。


* GitHub开源地址：[https://github.com/YSGStudyHards/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)
* Gitee开源地址：[https://gitee.com/ysgdaydayup/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)


