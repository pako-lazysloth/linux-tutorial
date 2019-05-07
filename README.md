# 操作系统指南

> 作为研发工程师，谁还没干过点运维的活？:joy:
>
> 搞运维，怎么着也得懂点操作系统相关。
>
> 本项目，就是本人在日常学习工作中，对于操作系统、运维部署等相关知识的整理。

## :memo: 知识点

### [Linux](docs/linux)

#### [Linux 命令](docs/linux/cli)

> 根据应用场景，将常见 Linux 命令分门别类的一一介绍。
>
> 如果想快速学习，推荐参考这篇文章：[命令行的艺术（转载）](docs/linux/cli/命令行的艺术.md)

1. [查看 Linux 命令帮助信息](docs/linux/cli/01.查看Linux命令帮助信息.md) - 关键词：`help`, `whatis`, `info`, `which`, `whereis`, `man`
2. [Linux 文件目录管理](docs/linux/cli/02.Linux文件目录管理.md) - 关键词：`cd`, `ls`, `pwd`, `mkdir`, `rmdir`, `tree`, `touch`, `ln`, `rename`, `stat`, `file`, `chmod`, `chown`, `locate`, `find`, `cp`, `mv`, `rm`
3. [Linux 文件内容查看命令](docs/linux/cli/03.Linux文件内容查看编辑.md) - 关键词：`cat`, `head`, `tail`, `more`, `less`, `sed`, `vi`, `grep`
4. [Linux 文件压缩和解压](docs/linux/cli/04.Linux文件压缩和解压.md) - 关键词：`tar`, `gzip`, `zip`, `unzip`
5. [Linux 用户管理](docs/linux/cli/05.Linux用户管理.md) - 关键词：`groupadd`, `groupdel`, `groupmod`, `useradd`, `userdel`, `usermod`, `passwd`, `su`, `sudo`
6. [Linux 系统管理](docs/linux/cli/06.Linux系统管理.md) - 关键词：`reboot`, `exit`, `shutdown`, `date`, `mount`, `umount`, `ps`, `kill`, `systemctl`, `service`, `crontab`
7. [Linux 网络管理](docs/linux/cli/07.Linux网络管理.md) - 关键词：关键词：`curl`, `wget`, `telnet`, `ip`, `hostname`, `ifconfig`, `route`, `ssh`, `ssh-keygen`, `firewalld`, `iptables`, `host`, `nslookup`, `nc`/`netcat`, `ping`, `traceroute`, `netstat`
8. [Linux 硬件管理](docs/linux/cli/08.Linux硬件管理.md) - 关键词：`df`, `du`, `top`, `free`, `iotop`
9. [Linux 软件管理](docs/linux/cli/09.Linux软件管理.md) - 关键词：`rpm`, `yum`, `apt-get`

#### [Linux 工具](docs/linux/tool)

- [Git](docs/linux/tool/git)
- [Vim](docs/linux/tool/vim.md)

#### [Linux 脚本编程](docs/linux/scripts)

- [一篇文章让你彻底掌握 shell 语言](docs/linux/scripts/shell.md)
- [Python](docs/linux/scripts/python.md)

#### [Linux 运维](docs/linux/ops)

#### Linux 服务器运维

- [Linux 典型运维应用](docs/linux/ops/linux典型运维应用.md)
- [samba 使用详解](docs/linux/ops/samba使用详解.md)

#### 应用、服务、工具运维和调优

> :bulb: **说明**
>
> 这里总结了一些常用开发软件的安装、配置、使用指南。
>
> 此外，提供了一键安装、配置脚本，:point_right: [**软件安装配置脚本**](https://github.com/dunwu/os-tutorial/tree/master/codes/linux/ops/soft)。
>
> [环境部署工具](https://github.com/dunwu/os-tutorial/tree/master/codes/deploy) ：适合开发、运维人员，在 [CentOS](https://www.centos.org/) 机器上安装常用命令工具或开发软件。

- 研发环境
  - [JDK](docs/linux/ops/soft/jdk.md)
  - [Maven、Nexus](https://github.com/dunwu/javastack/tree/master/docs/javatool/build/maven)
  - [Nginx](https://github.com/dunwu/nginx-tutorial)
  - [Nodejs](docs/linux/ops/soft/nodejs.md)
  - [Tomcat](docs/linux/ops/soft/tomcat.md)
  - [Zookeeper](docs/linux/ops/soft/zookeeper.md)
- 研发工具
  - [Jenkins](docs/linux/ops/soft/jenkins.md) - 持续集成和持续交付平台。
  - [Elastic](docs/linux/ops/soft/elastic) - 常被称为 `ELK` ，是 Java 世界最流行的分布式日志解决方案 。 `ELK` 是 Elastic 公司旗下三款产品 [ElasticSearch](https://www.elastic.co/products/elasticsearch) 、[Logstash](https://www.elastic.co/products/logstash) 、[Kibana](https://www.elastic.co/products/kibana) 的首字母组合。
- 版本控制
  - Gitlab - Git 代码管理平台
  - [Svn](docs/linux/ops/soft/svn.md) - Svn 是 Subversion 的简称，是一个开放源代码的版本控制系统，它采用了分支管理系统。
- 消息中间件
  - [Kafka](docs/linux/ops/soft/kafka.md) - 应该是 Java 世界最流行的消息中间件了吧。
  - [RocketMQ](docs/linux/ops/soft/rocketmq.md) - 阿里巴巴开源的消息中间件。
- 数据库
  - [Mysql](https://github.com/dunwu/database/blob/master/docs/mysql/install-mysql.md) - 关系型数据库
  - [PostgreSQL](https://github.com/dunwu/database/blob/master/docs/postgresql.md#安装) - 关系型数据库
  - [Mongodb](https://github.com/dunwu/database/blob/master/docs/mongodb/install-mongodb.md) - Nosql
  - [Redis](https://github.com/dunwu/database/blob/master/docs/redis/install-redis.md) - Nosql

### [Windows](docs/windows)

- [Windows 工具](docs/windows/Windows工具.md)

### [Docker](docs/docker)
