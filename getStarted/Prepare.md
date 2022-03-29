# Prepare

## 你需要准备什么

 - 一台 Linux 服务器，推荐拥有较多的 CPU 核心数量(8C)和较大的内存(8G)，若仅供测试体验，则推荐使用 2C4G 即以上配置，否则可能会导致服务器崩溃
 - 在 Linux 服务器上安装尽可能较新版本的 Git
 - 在 Linux 服务器上安装尽可能较新版本的 Docker & docker-compse
 - 一个良好的网络环境，特别是对 GitHub 和 dockerHub 的连接稳定
 - 一个愿意花费约 10 分钟来完成整个部署的人

### 我没有 Docker & docker-compse 怎么办

请前往 [此处](https://docs.docker.com/engine/install/) 获取相关帮助

当然，你也可以选择使用一行命令来快速安装 docker

```shell
curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh
```

通常，你还需要安装 docker-compse

你可以在 [这里](https://docs.docker.com/compose/install/) 获取相关帮助
