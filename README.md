# tkeasz
`tkeasz`是在`TKE`（腾讯云的[容器服务](https://console.cloud.tencent.com/tke)）环境下，利用`ansible-playbook`自动化配置、部署`kubernetes`集群内各类组件的工具。既提供一键安装脚本，也可以分步执行安装各个组件。

项目基于`Centos7`，需要了解基础`kubernetes` `docker` `linux`知识，关于`ansible`建议阅读 [ansible超快入门](http://weiweidefeng.blog.51cto.com/1957995/1895261) 。

## 安装步骤
- 00、规划集群和安装概览

- 01、设置节点`HOSTNAME`

- 02、安装`NFS`存储架构

- 03、安装镜像仓库`Harbor`

- 04、配置`docker`

> 注：本项目只专注于在`TKE`下的各类拓展工具的自动化部署，想要了解`kubernetes`集群更底层的安装部署可以关注[GitHub - gjmzj/kubeasz](https://github.com/gjmzj/kubeasz)。  