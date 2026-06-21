# 我的小工具 PWA

这是可以上传到 GitHub Pages 的 iOS PWA 包。

## 上传方式

1. 新建或打开一个 GitHub 仓库。
2. 把这个文件夹里的所有文件上传到仓库根目录。
3. 进入仓库 `Settings` -> `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. `Branch` 选择 `main` 和 `/root`，保存。
6. 等 GitHub Pages 部署完成后，用 iPhone Safari 打开 Pages 链接。
7. 点 Safari 分享按钮，选择“添加到主屏幕”。

## 文件说明

- `index.html`: 应用入口。
- `manifest.json`: PWA 安装信息。
- `sw.js`: 离线缓存。
- `icon-180.png`, `icon-192.png`, `icon-512.png`: iOS 和 PWA 图标。
- `.nojekyll`: 让 GitHub Pages 原样发布静态文件。

## 注意

iOS 上建议通过 `https://...github.io/...` 打开后添加到主屏幕。直接打开本地 `file://` 文件通常不能完整启用离线缓存。
