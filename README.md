# SpringSession-Redis原理
SpringSession-Redis是为了解决分布式的session不共享问题，SpringSess ion的实现
是通过SessionRepositoryFilter拦截器来替换原来的request和response，使用SessionRepositoryRequestWrapper
和SessionRepositoryResponseWrapper将数据的保存和获取通过redis来实现


# Spring websocket
(这些都是通过订阅通道进行，这里结合了点对点聊天完成，前端使用vue，文件为demo.zip)
## 1.1 点对点
这里我们采用socketjs来实现全双工通信
## 1.2 广播
