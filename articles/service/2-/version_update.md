# 产品发布历史

## v0.1-20180313 专属云

# 1.版本号：V3.5、发版时间：2018年3月13日 #

# 2.新增特性： #
 - 支持服务注册和服务发现、支持服务注册中心集群部署，保证高可用性
 
 - 支持服务注册后心跳检查，服务检查token验证
 
 - 注册中心支持调用者服务和被调用者服务的注册，注册信息包括租户ID,APPID。注册中心可以查看实例的所属应用和状态，当前应用的服务列表
 
 - 提供基本RPC调用框架，支持组件加载机制和插件机制,支持指定IP调用
 
 - 支持服务注册的zone元数据设置，调用时可按照会话信息调用指定zone的服务
 
 - 支持网络多跃点智能检测，运行时按照最短路径进行调用
 
 - 支持服务限流，可以从线程数和QPS两个维度进行限流
 
 - 给服务提供者提供直观的服务依赖关系图和微服务看板，同时支持无痕埋点，埋点对应用无侵入，无性能影响
 
 - 通过分布式链路追踪功能，查看调用耗时，提供快速定位性能问题的能力
 
 - 支持对注册到微服务注册中心的服务进行检索、支持服务和方法级别查询
 
 - 支持调用统计，统计区间范围内的细化到方法级别的用户访问量 
 
 - 监控客户端和服务端调用数据，统计调用成功率
 
 - 配置中心，支持应用配置文件的统一管理，当配置发生变化时实时更新，保证线上线下的配置文件的一致性
 
 - 支持服务注册和运行时的应用的多套环境的区分，环境隔离访问和统计监控
 
 - 支持不同环境之间的权限控制，token机制的调用验证
 
 - 支持服务和方法级别的授权控制，服务调用时权限验证
 
 - 支持类隔离机制的加载，提供隔离组件包，不影响业务工程的三方组件的版本依赖
 
 - 支持对开源开发组件的适配，包含spring不同版本、dubbo服务
 
 - 提供秘钥管理功能，不同角色分配不同的秘钥，保证调用过程环境的隔离验证
 
 - 提供元数据管控后台，根据元数据统计和控制接口和方法信息，提供文档支持
 


 



