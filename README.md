# 书桌

运营岗位资质题库跨平台刷题网站，共收录 2957 道题。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个公开仓库。
2. 将本 ZIP 解压后的**全部文件**上传到仓库根目录，包括隐藏的 `.github` 文件夹。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment → Source** 中选择 **GitHub Actions**。
5. 打开仓库的 **Actions** 页面，等待 `Deploy 书桌 to GitHub Pages` 显示绿色对勾。
6. 回到 **Settings → Pages** 查看网站地址。

以后修改或替换文件并提交后，网站会自动重新发布。

## 使用说明

- 网站是纯静态 PWA，不需要服务器或数据库。
- 学习记录、主题和设置保存在浏览器本机。
- Windows、安卓可通过浏览器安装；iPhone 可使用 Safari 的“添加到主屏幕”。
- 如需保留学习记录，请不要清除该网站的浏览器数据。

## 本地预览

不要直接双击 `index.html`。可以在本目录运行任意静态文件服务器，例如：

```bash
python -m http.server 8080
```

然后访问 `http://localhost:8080`。
