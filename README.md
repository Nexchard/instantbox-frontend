# instantbox 前端

[![Docker](https://badgen.net/badge/icon/instantbox-frontend?icon=docker&label)](https://hub.docker.com/r/instantbox/instantbox-frontend)
[![MIT](https://badgen.net/badge/license/MIT/3da639)](LICENSE)


## 简介

本仓库是 [instantbox](https://github.com/nexchard/instantbox) 项目的前端组件。

这是原始 [instantbox/instantbox-frontend](https://github.com/instantbox/instantbox-frontend) 仓库的改进版本，包含以下增强功能：
- 更新了 Dockerfile 以提供更准确的基础构建镜像
- 添加了 GitHub Actions 工作流以实现 Docker 镜像的自动构建和发布

## Docker 镜像

预构建的 Docker 镜像可在 Docker Hub 上获取：
```bash
# 拉取最新镜像
docker pull nexsre/instantbox-frontend:latest
```

每当对 main 分支进行更改或创建新版本时，GitHub Actions 会自动构建并推送镜像到 Docker Hub。

## 许可证

[MIT](LICENSE)