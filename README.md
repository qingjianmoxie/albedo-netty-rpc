# albedo-netty-rpc
spring springboot netty rpc zookeeper protostuff

项目是基于netty实现通信，zookeeper作为服务发现的高可用rpc远程调用框架

zookeeper 默认地址 localhost:2181,localhost:2182,localhost:2183

启动顺序：

    albedo-rpc-example-server
    albedo-rpc-example-client

启动方式: mvn spring-boot:run 

访问地址: http://localhost:8811/index
