# 🐳 虎鲸云直播

# 👏 项目立项
- Orca 是为了在 私域下，历史的均是社群模式，当前直播火爆场景下，而为了在私域下引入直播方案而立项。 简单概述：虎鲸云是 企业私域直播的开源解决方案

<pre>
  本人是在非全职下开发维护该项目，所以有一些产品功能与规划有欠缺、请见谅、也欢迎大佬们推荐新的功能，或者提交新的 PR
  小弟有一些以下的想法的:
  - 商品更多裂变玩法
  - 支付的多渠道
  - 数据服务支撑
</pre>


## 项目包含多端

- 直播运营管理端: 直播管理、订单管理、直播统计、渠道管理、渠道数据、商品管理、视频管理、系统设置等
- 直播助理端: 直播过程中的 场控管理（氛围、剧本、订单等）、观众管理（禁言、回复、拉黑、自嗨等）、消息审核（通过、不通过）、订单管理（促单等）、商品管理(上下架、推荐、售罄等)、礼物管理、直播数据、大屏数据等、
- 直播主播端: 课件管理、消息管理、视频管理、屏幕分享、白板管理、推流管理等
- 直播观看端: 线路切换、商品、礼物、白板、课件等

# 🏠 项目组件


## 前端项目组件 （商业支持联系V: pink-hello）
> orca-admin       运营管理端（Web模式）

> assis-client     直播助播端（Web模式）

> anchor-client    直播主播端（Web模式开播）

> audience-client  观看端（H5模式）

## 后端项目组件 （商业支持联系V: pink-hello）

> living             [主项目]直播 
  ``` 
  doc/sql                   SQL与MARKDOWN文档
  
  living-common             
  living-beans
  
  living-web-adapater       Web端适配层
  living-web-org-adapter    企业端Web适配层
  living-logging-adapter    日志适配层
  living-dubbo-adapter      Dubbo 配置适配层
  
  living-seq-api            序列 Dubbo Api包
  living-core-api           核心 Dubbo Api包
  living-core-provider      核心 Dubbo Provider 服务
  living-seq-provider       序列 Dubbo Provider 服务

  living-core-dao           核心 Dao 层
  
  living-boss               开通管理端API服务
  living-admin              运营管理端API服务
  living-console            助播端、主播端API服务
  living-sharing            观看端API服务
  living-short              短域名服务
  living-task               分布式任务服务调度服务

  ```     

> grab-push        【闭源】[基础服务]伪直播服务（商业支持联系V: pink-hello）

> fire-sio         【闭源】[基础服务]IM服务（商业支持联系V: pink-hello）

> draw-sio         【闭源】[基础服务]白板服务（商业支持联系V: pink-hello）



# 项目技术栈

> Vue、React、TypeScript、Electorn

> Java、Python、SpringBoot、Dubbo、Netty、

> Redis、MongoDB、MySQL、Pulsar、Nacos、Zookeeper

> K8S、Docker、Docker-Compose、Rancher

> AliyunCloud、AWS、TencentCloud

> ...


