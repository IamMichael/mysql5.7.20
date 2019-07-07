```
基于CentOS7.5 Minimal 安装测试

Docker版本：18.6.0
MySQL版本：5.7.20

关于docker二进制文件
# wget   https://download.docker.com/linux/static/stable/x86_64/docker-18.06.0-ce.tgz
# tar -zxf docker-18.06.0-ce.tgz
# cp  docker/docker*  roles/docker/files/docker

关于 MySQL 5.7.20 镜像包 mysql_5.7.20.tar
# docker pull mysql:5.7.20
# docker save -o mysql_5.7.20.tar  mysql:5.7.20
# cp mysql_5.7.20.tar roles/mysql/files/
```
