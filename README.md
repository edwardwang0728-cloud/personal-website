# 王骏翔个人求职网站

这是一个纯静态个人求职网站，可以免费或极低成本部署。无需后端、数据库或付费服务器。

## 本地打开

直接双击 `index.html`，或在浏览器中打开该文件。

## 免费部署方式

- GitHub Pages：把本文件夹内容推到一个 GitHub 仓库，Settings -> Pages 选择 `main` 分支即可。
- Cloudflare Pages：连接 GitHub 仓库，构建命令留空，输出目录选择仓库根目录。
- Netlify：把整个文件夹拖拽到 Netlify Drop，或连接 GitHub 仓库自动部署。
- Vercel：导入静态仓库，Framework Preset 选择 Other，构建命令留空。

## 文件结构

- `index.html`：页面结构与简历内容
- `styles.css`：视觉样式、响应式布局、动画状态
- `script.js`：粒子背景、鼠标互动、卡片倾斜、滚动显现
- `assets/avatar.jpg`：个人照片
- `assets/wang-junxiang-resume.docx`：可下载 Word 简历
