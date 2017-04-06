# micro-service
spring-cloud 微服务组件demo

说明：

**工程名**	**描述**	**端口**
eureka-server	服务发现与注册中心	7070
ribbon	负载均衡器	7071
config-server	配置管理中心	7072
zuul	动态路由器	7073
service-A	A服务，用来测试服务间调用与路由	7074
service-B	B服务	7075
service-B2	B2服务，与B服务serviceId相同，用来测试负载均衡和容错	7076
hystrix-ribbon	负载均衡器的容错测试	7077
feign	声明式、模板化的HTTP客户端，可用来做负载均衡，较轻量	7078
hystrix-feign	feign的容错测试	7079
hystrix-dashboard	hystrix可视化监控台	7080
turbine	集群下hystrix可视化监控台	7081

开发环境：JDK1.7 + maven 
说明：最好还是用1.8版本的JDK，后面高版本都是在1.8下面迭代的，注意修改pom文件中的Java.version
