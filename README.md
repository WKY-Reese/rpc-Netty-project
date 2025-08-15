# rpc-Netty-project
  这是一个基于Netty和ZooKeeper实现的轻量级RPC框架，主要解决了分布式系统中服务之间的远程调用问题。框架的核心功能包括服务注册与发现、远程方法调用、负载均衡和动态扩缩容。在技术选型上，我使用Netty作为网络通信框架，ZooKeeper作为注册中心，CGLIB实现动态代理，JSON进行序列化。
