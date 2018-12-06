# netty 用法

## 业务逻辑的类ChannelInboundHandlerAdapter    
- channelRead  
- channelActive  
- channelRigister  
## 解码类ByteToMessageDecoder 继承自 ChannelInboundHandlerAdapter  
- decode

## 自定义协议解析
- LengthFieldBasedFrameDecoder  
[参考1](https://blog.csdn.net/u014801432/article/details/81909902)    
[参考2](https://www.cnblogs.com/lanqie/p/8268469.html)  
[参考3](https://www.jianshu.com/p/c90ec659397c)  
[参考3](https://www.jianshu.com/p/337d1d152413)  
[参考3](https://www.jianshu.com/p/ed4c61d0d6f2)  
[参考3](https://www.jianshu.com/p/c90ec659397c)  
[参考3](https://blog.csdn.net/z69183787/article/details/52980699)  
- lengthFieldOffset: 长度字段的偏差
- lengthFieldLength: 长度字段占的字节数
- lengthAdjustment: 添加到长度字段的补偿值
- initialBytesToStrip: 从解码帧中第一次去除的字节数

## 记录日志
[参考](https://blog.csdn.net/arctan90/article/details/51280797)  
[日志分类](https://zhuanlan.zhihu.com/p/36185173)  
- 查询日志
- 慢查询日志
- 错误日志
- 二进制日志
----
- sl4j + logback  
```
 <dependency>  
    <groupId>org.slf4j</groupId>  
    <artifactId>slf4j-api</artifactId>  
    <version>${slf4j.api.version}</version>  
  </dependency>  
  
  <dependency>  
    <groupId>ch.qos.logback</groupId>  
    <artifactId>logback-classic</artifactId>  
    <version>${logback.version}</version>  
  </dependency>  
  <dependency>  
    <groupId>ch.qos.logback</groupId>  
    <artifactId>logback-core</artifactId>  
    <version>${logback.version}</version>  
  </dependency>  
```  
[maven 资源文件夹](https://jingyan.baidu.com/album/77b8dc7fb733356174eab6ed.html?picindex=1)  
[backup.xml无效问题](https://blog.csdn.net/cnwyt/article/details/80462896)
[log4j重复输出问题](https://blog.csdn.net/chxkyy/article/details/1718487)


## netty源码
[netty权威指南](https://github.com/wuyinxian124/nettybook2)
[源码接卸](https://www.jianshu.com/u/dbcfb30ec5e4)
