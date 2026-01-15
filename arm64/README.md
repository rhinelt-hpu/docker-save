# ARM64 镜像构建

此文件夹用于触发 ARM64 架构的 Docker 镜像构建和打包。

## 使用方法

1. 在此文件夹中添加或修改任何文件
2. 推送到 main 分支
3. GitHub Actions 会自动检测到 arm64 文件夹的变更，并构建 ARM64 架构的镜像

## 打包说明

- 构建的镜像将会被打包为 `backup-arm64-YYYYMMDDHHmm.tar.gz`
- 镜像平台：linux/arm64
- 上传路径：与配置中的 RCLONE_UPLOAD_PATH 保持一致
