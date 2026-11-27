# hello-github

本机 GitHub 环境验证仓库，2026-11-27 创建。

## 本机实测记录

| 路径 | 结果 |
|---|---|
| git clone 直连 https | 300 秒超时，不可用 |
| git clone 走 ghfast 镜像 | 5.9 秒成功 |
| git clone 走 SSH | 21.5 秒成功，约 0.02 MB/s |
| SSH 认证 | 通过（Hi shaonian7919） |
| GitHub release 走清华镜像 | 7.5 MB/s |

## 使用约定

- 拉取公开仓库：`git ghclone owner/repo`
- 推送自己的仓库：走 SSH（`git@github.com:...`）
