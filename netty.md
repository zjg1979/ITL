# netty 用法

## 业务逻辑的类ChannelInboundHandlerAdapter    
- channelRead  
- channelActive  
- channelRigister  
## 解码类ByteToMessageDecoder 继承自 ChannelInboundHandlerAdapter  
- decode

## 自定义协议解析
- LengthFieldBasedFrameDecoder  [参考1](https://blog.csdn.net/u014801432/article/details/81909902)[参考2](https://www.cnblogs.com/lanqie/p/8268469.html)[参考3](https://www.jianshu.com/p/c90ec659397c)

## 记录日志
[参考](https://blog.csdn.net/arctan90/article/details/51280797)  
[日志分类](https://zhuanlan.zhihu.com/p/36185173)  
- 查询日志
- 慢查询日志
- 错误日志
- 二进制日志
