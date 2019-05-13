![](https://bboysoul-web.oss-cn-hangzhou.aliyuncs.com/20190513-2.gif)

### 简介

之前我写过[搭建一个google镜像站]([https://www.bboysoul.com/2017/09/01/%E6%90%AD%E5%BB%BA%E4%B8%80%E4%B8%AAgoogle%E9%95%9C%E5%83%8F%E7%AB%99/](https://www.bboysoul.com/2017/09/01/%E6%90%AD%E5%BB%BA%E4%B8%80%E4%B8%AAgoogle%E9%95%9C%E5%83%8F%E7%AB%99/)
)这篇文章，使用的是nginx的一个模块，但是使用比较麻烦，今天就简化了一下

### 准备

首先你要准备一台国外的服务器

之后你要搭建docker环境

`curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun`

安装docker-compose

`curl -L https://github.com/docker/compose/releases/download/1.24.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose`

`chmod +x /usr/local/bin/docker-compose`

### 启动谷歌镜像站

之后clone我这个项目，欢迎fork star follow我

`git clone https://github.com/bboysoulcn/docker-nginx-google.git`

之后直接启动

`cd docker-nginx-google/ && docker-compose up -d`

欢迎关注Bboysoul的博客[www.bboysoul.com](http://www.bboysoul.com/)
Have Fun