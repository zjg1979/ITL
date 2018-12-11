# linux基本操作
[参考](http://www.runoob.com/linux/linux-tutorial.html)
[yum](https://www.cnblogs.com/liaocheng/p/4243589.html)

# 查看版本
cat /etc/redhat-release


## 文件操作
mkdir  
rmdir
rm  

chmod 777 file

mount/umount 挂载设备

## 安装
yum
安装  install  
更新和升级   update  
查找和显示   info list  
删除程序  remove  

rpm 
安装
更新和升级
查找和显示
删除程序
## web操作

## 服务  
service start stop restart
chkconfig --list 
chkconfig service on/off  

# 源码安装
wget 
tar zxvf file
./configure
make & make install

#网络命令
netstat
ifconfig
iptables

## 开关机
shutdown  
poweroff  
init  
reboot  
halt  

## 配置java  
### 查询 rpm -qa | grep java jdk gcj
### 卸载 rpm -qa | grep java | xargs rpm -e --nodeps
### 安装 yum list java-1.8*  ,yum install java-1.8.0-openjdk* -y 
### 检测 java -version



