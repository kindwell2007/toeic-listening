# TOEIC 听力学习 PWA

此目录包含可安装网页应用文件：
- `index.html`：学习入口及当前已整理的 Lesson 1
- `manifest.webmanifest`：应用名称、图标和独立窗口配置
- `sw.js`：离线缓存
- `icon-192.png`、`icon-512.png`：应用图标

## 发布后安装
必须通过 HTTPS 网站访问（不能使用 `content://` 本地文件地址）。
将本目录全部文件上传到一个静态网站托管服务（例如 GitHub Pages），然后用 Android Chrome 打开 HTTPS 地址。
在 Chrome 菜单中选择“安装应用”或“添加到主屏幕”；也可以使用页面顶部出现的“安装”按钮。
