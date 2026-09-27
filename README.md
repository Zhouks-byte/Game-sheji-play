# 余烬前线

一款无需安装、无需构建工具的简体中文像素横版射击游戏。打开 `index.html` 即可游玩，也可以直接部署到 GitHub Pages。

## 玩法

- `A` / `D`：向左 / 向右移动
- `W`：跳跃躲避
- `S`：下蹲避弹
- 鼠标左键：瞄准并射击；按住可连续射击
- 弹匣耗尽后自动装填。绿色补给可以恢复生命。
- 击破 30 个感染者即可守住阵地；生命耗尽则任务失败。

## 部署到 GitHub Pages

1. 将仓库改动合并到 `main` 分支。
2. 在 GitHub 仓库的 **Settings → Pages → Build and deployment** 中，将 **Source** 设为 **GitHub Actions**。
3. `main` 分支有新提交后，`.github/workflows/pages.yml` 会自动发布；也可以在 **Actions** 页面手动运行“部署到 GitHub Pages”工作流。
4. 部署成功后，在 **Settings → Pages** 查看网站地址。

游戏是独立的静态 HTML 文件，不依赖外部 CDN、安装步骤或构建过程。
