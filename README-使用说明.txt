Dayform 2.1 使用说明

1. 本地预览：双击 index.html。此时可体验任务、课程、目标、日志，但 PWA 离线安装需要 HTTPS 或 localhost。
2. 发布：登录 github.com -> New repository -> 名称 dayform -> Public -> Create repository。
3. 选择 Add file -> Upload files，把本文件夹里的 index.html、manifest.webmanifest、sw.js 和 icons 文件夹内两张图片上传到仓库根目录，提交。
4. Settings -> Pages -> Source: Deploy from a branch -> Branch: main / (root) -> Save。
5. 访问 https://你的用户名.github.io/dayform/ （请替换为真实用户名）。发布可能需要几分钟。
6. 用该网址制作二维码；iPhone Safari 打开后使用分享菜单 -> 添加到主屏幕。Android Chrome 使用菜单 -> 安装应用/添加到主屏幕。

注意：数据存储在当前浏览器 localStorage 中，不跨设备同步，也不与旧版本不同来源的网址共享。升级或换网址前请自行保留重要记录。不要在公开 GitHub 仓库上传个人任务、课程表、密码等私人信息。
