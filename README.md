# AuroraKairos Blog

使用 Hexo + anzhiyu 主题构建的技术博客。

## 快速开始

### 本地开发

```bash
# 安装依赖
npm install

# 启动本地服务器
npm run server
```

### 部署

推送到 main 分支后，GitHub Actions 将自动构建并部署到 GitHub Pages。

## 目录结构

```
blog/
├── source/          # 博客文章源文件
├── themes/anzhiyu/  # 博客主题
├── .github/         # GitHub Actions 配置
└── _config.yml      # Hexo 配置
```

## 写作

在 `source/_posts/` 目录下创建 Markdown 文件即可。

---

Powered by [Hexo](https://hexo.io/) + [Anzhiyu Theme](https://github.com/anzhiyu-c/hexo-theme-anzhiyu)