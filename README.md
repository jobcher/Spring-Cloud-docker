# Spring-Cloud-docker
Spring Cloud集成项目docker部署库

## 前置条件
### 安装docker和docker-compose
1. 安装docker
```sh
curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun
curl -sSL https://get.daocloud.io/docker | sh
```

2. 安装docker-compose
```sh
#下载安装
sudo curl -L "https://github.com/docker/compose/releases/download/v2.16.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
#可执行权限
sudo chmod +x /usr/local/bin/docker-compose
#创建软链：
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
#测试是否安装成功
docker-compose --version
```

