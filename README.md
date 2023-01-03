![](https://bboysoul-web.oss-cn-hangzhou.aliyuncs.com/20190513-2.gif)

### 简介
通过docker安装Google镜像站

### 准备

首先你要准备一台国外的服务器

之后你要搭建docker环境

`curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun`

安装docker-compose

`curl -L https://github.com/docker/compose/releases/download/1.24.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose`

`chmod +x /usr/local/bin/docker-compose`

### 启动谷歌镜像站

之后clone我这个项目，欢迎fork star follow我

`git clone https://github.com/fourgongzuoshi/docker-nginx-google.git`

之后直接启动

`cd docker-nginx-google/ && docker-compose up -d`

欢迎关注我的镜像站发布页[foursearch.cf](https://foursearch.cf)
Have Fun
