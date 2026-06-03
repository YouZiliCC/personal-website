# 个人网站项目

这是一个现代化的个人网站项目，展示个人作品和信息。已部署到 GitHub Pages！

🌐 **在线访问**: [https://youzilicc.github.io/personal-website](https://youzilicc.github.io/personal-website)

## 📁 项目结构

```
personal-website/
├── index.html              # 主页面
├── styles/
│   └── main.css           # 主样式文件
├── scripts/
│   └── main.js            # 主JavaScript文件
├── assets/                 # 资源文件夹（图片、图标等）
├── package.json           # 项目配置
├── .gitignore            # Git忽略文件
└── README.md             # 项目文档
```

## ✨ 功能特性

- 📱 **响应式设计** - 完美适配各种设备（手机、平板、桌面）
- 🎨 **现代化风格** - 使用现代 CSS 和设计模式
- ⚡ **流畅动画** - 平滑的页面交互和过渡效果
- 🔍 **SEO 友好** - 搜索引擎优化
- 🌐 **跨浏览器兼容** - 支持主流浏览器
- 📄 **自动部署** - 与 GitHub Pages 集成

## 🚀 快速开始

### 本地开发

1. **克隆项目**
```bash
git clone https://github.com/YouZiliCC/personal-website.git
cd personal-website
```

2. **启动本地服务器**
```bash
# 使用 Python 3
python -m http.server 8000

# 或使用 Node.js (需要安装 http-server)
npx http-server

# 或使用 Live Server (VS Code 扩展)
```

3. **在浏览器中打开**
```
http://localhost:8000
```

## 📝 页面部分说明

### 🔝 导航栏
- 粘性导航栏，始终显示在顶部
- 包含主页、关于、项目、联系链接
- 平滑的导航动画

### 🎯 英雄部分 (Hero Section)
- 欢迎信息和个人简介
- 行动按钮（CTA）
- 渐变背景设计

### 👤 关于部分
- 个人简介信息
- 背景和经历说明

### 💼 项目部分
- 项目卡片网格展示
- 支持响应式 3 列/2 列/1 列布局
- 悬停动画效果

### 📧 联系部分
- 联系表单（邮箱和信息输入）
- 表单验证和提交处理

### 🔗 页脚
- 版权信息
- 可扩展的链接区域

## 🎯 自定义指南

### 修改内容
编辑 `index.html` 文件中的文本内容：
- 更改标题和描述
- 更新项目信息和链接
- 修改联系方式
- 添加个人社交媒体链接

### 修改样式
编辑 `styles/main.css` 文件：
```css
/* 修改主色调 */
--primary-color: #0066cc;  /* 改为您喜欢的颜色 */

/* 修改辅助色 */
--secondary-color: #f0f0f0;

/* 调整间距和大小 */
/* 自定义响应式断点 */
```

### 添加功能
编辑 `scripts/main.js` 文件：
- 增强交互功能
- 集成第三方 API
- 添加表单验证和邮件发送
- 集成分析工具（Google Analytics 等）

## 🛠️ 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和响应式设计
- **JavaScript (Vanilla)** - 交互和动态功能
- **Git & GitHub** - 版本控制和托管
- **GitHub Pages** - 自动部署

## 📦 可选扩展功能

- ✍️ 添加博客功能
- 💬 集成评论系统
- 🌙 添加暗黑模式
- 📊 集成分析工具
- 🔨 使用构建工具（Webpack、Vite）
- ✨ 添加动画库（AOS、GSAP）
- 🖼️ 添加图库/作品展示
- 🔐 添加联系表单后端处理

## 🌐 部署指南

### GitHub Pages 部署 ✅ (已完成)

1. **自动启用** - GitHub Pages 已自动启用
2. **访问地址** - `https://youzilicc.github.io/personal-website`
3. **自动更新** - 每次推送到 `main` 分支时自动部署

### 其他部署平台

- **Netlify** - 连接 GitHub 仓库，自动部署
- **Vercel** - 类似 Netlify，专为前端优化
- **Firebase Hosting** - Google 提供的静态托管
- **Cloudflare Pages** - 快速且全球加速
- **传统虚拟主机** - 上传文件到服务器

## 📋 部署检查清单

- [x] HTML 结构完成
- [x] CSS 样式完成
- [x] JavaScript 功能完成
- [x] 响应式设计测试
- [x] GitHub Pages 配置
- [x] 自动部署设置

## 🔄 更新网站

1. 克隆或拉取最新代码
2. 在本地修改文件
3. 提交更改到 GitHub
   ```bash
   git add .
   git commit -m "更新内容"
   git push origin main
   ```
4. GitHub Pages 将自动构建并部署

## 📱 浏览器兼容性

- ✅ Chrome (最新版本)
- ✅ Firefox (最新版本)
- ✅ Safari (最新版本)
- ✅ Edge (最新版本)
- ✅ 移动浏览器 (iOS Safari, Chrome Mobile)

## 🎨 配色方案

**主配色**: 蓝色系 (#0066cc - #0052a3)
**辅助色**: 浅灰 (#f0f0f0)
**文本色**: 深灰 (#333) / 中灰 (#666)

可在 `styles/main.css` 中的 `:root` 部分修改。

## 📄 许可证

**MIT License** - 自由使用和修改
详见 LICENSE 文件

## 👤 作者

**YouZiliCC**

- GitHub: [@YouZiliCC](https://github.com/YouZiliCC)
- Email: 可在联系表单中获取

## 🤝 贡献

欢迎提交问题和改进建议！

如果您有任何建议或发现问题，请：
1. 提交 Issue
2. Fork 项目并提交 Pull Request
3. 在讨论中分享想法

## 📚 学习资源

- [MDN Web Docs - HTML](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
- [MDN Web Docs - JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)
- [GitHub Pages 文档](https://docs.github.com/cn/pages)

## 🐛 常见问题

**Q: 网站无法访问？**
A: 请检查 GitHub Pages 是否已启用，设置中选择 `main` 分支。

**Q: 修改后网站没有更新？**
A: GitHub Pages 部署可能需要 1-2 分钟，请刷新浏览器或清除缓存。

**Q: 联系表单如何发送邮件？**
A: 目前仅有前端验证，可集成邮件服务如 Formspree、EmailJS 等。

**Q: 如何添加自定义域名？**
A: 在仓库设置中的 GitHub Pages 部分配置自定义域名。

---

**最后更新**: 2026 年 6 月 3 日

**版本**: 1.0.0

**状态**: ✅ 完成并已部署到 GitHub Pages
