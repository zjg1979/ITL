# Maven使用说明
>依赖管理和生命周期管理
[eclipse maven 搭建环境](https://blog.csdn.net/rock4you/article/details/72628146)

## 镜像更改
修改apache-maven-3.5.0\conf下的setting.xml文件
```
  <mirrors>

    <mirror>

      <id>alimaven</id>

      <name>aliyun maven</name>

      <url>http://maven.aliyun.com/nexus/content/groups/public/</url>

      <mirrorOf>central</mirrorOf>   

    </mirror>

  </mirrors>
```
## 步骤
> 选择maven-archetype-quickstart
> groupid 对应java的包结构；ArtifactID为项目的为标志  
  例如公司mycomm,项目myapp  
  groupid   com.mycom.myapp
  artifactid  myapp-util myapp-domain  myapp-web
> 增加maven依赖，https://mvnrepository.com/


## 打包
Maven Build  Goals：
 clean  清除编译，compile  编译，test  编译并测试，install 打包并发送到本地仓库，package 只是打成jar包，并不会发送到本地仓库
