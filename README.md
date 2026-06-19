<h1 align="center">
  <img src="https://meshbit.github.io/TelegramNavigation/assets/images/logo.svg" height="40" alt="Telegram 导航">
</h1>
<p align="center"><strong>精心整理的 Telegram 群组、频道、机器人导航站</strong></p>
<p align="center">
  <a href="https://meshbit.github.io/TelegramNavigation/"><img src="https://img.shields.io/badge/在线访问-2AABEE?style=for-the-badge"></a>
  <a href="https://github.com/meshbit/TelegramNavigation/tree/source"><img src="https://img.shields.io/badge/源码-source--branch-orange?style=for-the-badge"></a>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/分类-15-2AABEE">
  <img src="https://img.shields.io/badge/条目-1436+-2AABEE">
  <img src="https://img.shields.io/badge/Hugo-v0.126.1-ff4088">
  <img src="https://img.shields.io/badge/主题-WebStack_Hugo-blue">
  <img src="https://img.shields.io/badge/部署-GitHub_Pages-brightgreen">
</p>

---

## 简介

本导航站收集了大量优质 Telegram 资源，涵盖**群组**、**频道**、**机器人**三大类型，分 **15 个分类**，共收录 **1,436+ 条目**。

基于 [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) 主题构建，响应式设计，支持暗色模式，适配 PC 和移动端。

## 数据概览

| 分类 | 数量 |
|------|:----:|
| 资源频道 | 904 |
| 中文社区 | 112 |
| 趣味工具 | 89 |
| 娱乐休闲 | 66 |
| 群组管理 | 64 |
| 新闻资讯 | 50 |
| 搜索机器人 | 40 |
| 技术开发 | 37 |
| 科学上网 | 31 |
| 播客与媒体 | 15 |
| 加密货币 | 12 |
| 抽奖机器人 | 8 |
| 购物优惠 | 5 |
| 地区群组 | 2 |
| 学习教育 | 1 |
| **合计** | **1,436** |

## 技术栈

- **[Hugo](https://gohugo.io/)** — 静态网站生成器 (v0.126.1 Extended)
- **[WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo)** — 导航站主题
- **GitHub Pages** — 托管与自动部署

## 本地开发

```bash
# 克隆源码
git clone -b source https://github.com/meshbit/TelegramNavigation.git
cd TelegramNavigation

# 拉取主题子模块
git submodule update --init

# 安装 Hugo Extended
# macOS:  brew install hugo
# Windows: choco install hugo-extended

# 启动开发服务器
hugo server

# 构建
hugo --baseURL https://meshbit.github.io/TelegramNavigation/ --minify
```

## 项目结构

```
.
├── config.toml              # Hugo 配置
├── data/
│   └── webstack.yml         # 导航数据 (1,436 条)
├── layouts/                  # 自定义模板
├── static/                   # 静态资源、logo、图标
├── themes/
│   └── WebStack-Hugo/       # 主题 (子模块)
└── archetypes/               # 内容模板
```

> **分支说明**：`main` 分支存放构建后的静态站点 (GitHub Pages 部署)，`source` 分支存放 Hugo 工程源码。

## 数据来源

数据整理自 [AZeC4/TelegramGroup](https://github.com/AZeC4/TelegramGroup)，通过脚本解析 README 后生成 Hugo 数据文件。

## 贡献指南

欢迎提交新的 Telegram 群组、频道或机器人！

1. Fork 本仓库
2. 在 `data/webstack.yml` 中添加条目
3. 提交 PR 到 `source` 分支

## License

MIT © [meshbit](https://github.com/meshbit)
