2024 Java EE Homework 4 开发一个玩具微服务系统

应用场景：
假设我们要开发一个集成多个服务的微服务系统，如CRM服务、物流服务、自动仓储服务和支付服务。例如，如果客户下达一个将一批货物存储到仓库的服务订单，CRM服务将调用相应的物流服务、仓储服务和支付服务来完成服务交易。为了开发系统，我们需要添加服务发现、网关和oauth服务器等微服务基础设施，除了上述提到的服务。

开发要求：
1. 使用Spring Cloud基础设施开发一个玩具微服务系统。
2. 使用Eureka或Alibaba Nacos进行服务发现。
3. （可选）使用Resilience4j或Hystrix实现断路器。
4. （可选）集成Oauth2授权服务器。
5. （可选）通过网关向外部用户暴露API。
6. （可选）使用Spring Cloud配置服务器和Sleuth进行集中配置和跟踪。
