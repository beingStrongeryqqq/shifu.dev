---
title: 生产安装部署
sidebar_position: 0
---

# 生产安装部署

在生产环境部署 ***Shifu*** 前您需要先[安装 Kubernetes](https://kubernetes.io/releases/download/)。

***Shifu*** 提供了一键安装的方式，您可以使用如下命令将 ***Shifu*** 安装到您的集群中：

```bash
kubectl apply -f https://raw.githubusercontent.com/Edgenesis/shifu/v0.2.1/pkg/k8s/crd/install/shifu_install.yml
```