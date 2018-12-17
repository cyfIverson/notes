#### Linux工作日常积累
##### **注意：针对centos系统**
###### 查看Linux版本命令
- 查看Linux系统版本
  
```
[root@localhost etc]# cat /etc/redhat-release

CentOS release 6.5 (Final)
```
- 列出所有版本信息
```
[root@localhostetc]# lsb_release -a
LSB Version:    :base-4.0-amd64:base-4.0-noarch:core-4.0-amd64:core-4.0-noarch:graphics-4.0-amd64:graphics-4.0-noarch:printing-4.0-amd64:printing-4.0-noarch
Distributor ID:CentOS
Description:    CentOS release 6.5 (Final)
Release:        6.5
Codename:       Final
```

###### 查看Linux系统版本目的
了解具体系统版本，可以针对性的对其进行操作。Linux系统版本有很多，不同版本的系统里软件的安装过程和命令都有可能不一样，所以知道Linux系统版本后会提高你操作的效率。
在网上搜索解决问题的方案时最好带上Linux系统的版本，这样会更准确的找到你需要的方案