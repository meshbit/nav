# Telegram 导航 🧭

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Online-brightgreen)](https://meshbit.github.io/TelegramNavigation/)
[![Hugo](https://img.shields.io/badge/Hugo-v0.163.2-ff4088)](https://gohugo.io/)
[![Theme](https://img.shields.io/badge/Theme-WebStack--Hugo-blue)](https://github.com/shenweiyan/WebStack-Hugo)

> 精心整理的 Telegram 群组、频道、机器人导航站，15 个分类，1400+ 条目，帮你快速发现优质 Telegram 资源。

## 在线访问

🔗 **[https://meshbit.github.io/TelegramNavigation/](https://meshbit.github.io/TelegramNavigation/)**

## 分类

| 分类 | 图标 | 说明 |
|------|------|------|
| 📦 资源频道 | `fa-box` | 各类资源分享频道 |
| 💬 中文社区 | `fa-comments` | 中文讨论群组 |
| 🤖 趣味工具 | `fa-robot` | 实用机器人和工具 |
| 🎮 娱乐休闲 | `fa-gamepad` | 游戏、影视、娱乐 |
| 🛡️ 群组管理 | `fa-shield-alt` | 群管机器人和工具 |
| 📰 新闻资讯 | `fa-newspaper` | 新闻频道和媒体 |
| 🔍 搜索机器人 | `fa-search` | 各种搜索 bot |
| 💻 技术开发 | `fa-code` | 编程和技术讨论 |
| 🔗 科学上网 | `fa-globe` | 网络工具和代理 |
| ₿ 加密货币 | `fa-bitcoin` | 币圈和 Web3 |
| 📡 播客与媒体 | `fa-podcast` | 播客和自媒体 |
| 🎁 抽奖机器人 | `fa-gift` | 抽奖和活动 bot |
| 🛒 购物优惠 | `fa-shopping-cart` | 购物和优惠信息 |
| 🌍 地区群组 | `fa-map-marker-alt` | 各地区本地群组 |
| 📚 学习教育 | `fa-book` | 学习和教育资源 |

## 数据来源

数据整理自 [AZeC4/TelegramGroup](https://github.com/AZeC4/TelegramGroup)，感谢原作者。

## 技术栈

- **静态生成**: [Hugo](https://gohugo.io/) Extended v0.163.2
- **主题**: [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo)
- **部署**: [GitHub Pages](https://pages.github.com/)
- **图标**: Font Awesome 5.15.4

## 本地开发

```bash
# 克隆仓库
git clone https://github.com/meshbit/TelegramNavigation.git
cd TelegramNavigation

# 安装 Hugo Extended
# Windows: choco install hugo-extended
# macOS: brew install hugo
# Linux: snap install hugo --channel=extended

# 初始化主题子模块
cd nav-hugo
git submodule update --init --recursive

# 启动开发服务器
hugo server -D

# 构建
hugo --gc --minify
```

## 贡献

欢迎提交 PR 添加新的群组、频道或机器人，或改进站点功能。

数据文件位于 `nav-hugo/data/webstack.yml`，格式如下：

```yaml
- taxonomy: 📦 资源频道
  icon: fas fa-box
  links:
  - title: 频道名称
    url: https://t.me/username
    description: 简短描述
    logo: https://example.com/icon.png  # 可选
```

## 免责声明

- 内容采集自网络，仅供学习参考
- 所有频道群组真实性未知，侵权请联系删除
- 存在广告内容，请自行辨别

## License

MIT © [meshbit](https://github.com/meshbit)
