# VisionFocus Hours · 专注时光愿景板

![License](https://img.shields.io/badge/license-Non--Commercial-red.svg)
![Web3 Ready](https://img.shields.io/badge/Web3-Hackathon_Project-purple.svg)
![Version](https://img.shields.io/badge/version-1.0.0-orange.svg)

> ✨ 用专注时光，显化你的愿景 ✨  
> 一个结合冥想引导、愿景可视化与时间投资的Web3 DApp

## 🌟 项目简介

**VisionFocus Hours** 是一个沉浸式的愿景实现工具，帮助用户：
- 通过专业冥想引导设定年度愿景
- 创建个性化的视觉愿景板
- 记录并可视化专注时间投入
- 体验愿望逐渐显化的成就感
- 生成年度NFT纪念时光投资

### 核心哲学
> "时间是每个人最公平的资源，如何投资时间，决定未来的模样"

## 🚀 立即体验

- 🌐 **在线演示**: [visionfocushours.app](https://visionfocushours.app)
- 📱 **桌面版优先**: 最佳体验在桌面/平板浏览器
- 🔗 **测试网**: Sepolia测试网NFT铸造

## ✨ 核心功能

### 🧘 沉浸式冥想引导
- 温暖的女声引导 + 温馨背景音乐
- 呼吸动画 + 打字机效果文字
- 专业心理咨询师般的问题设计

### 🎨 手绘风格愿景板编辑器
- 上传图片关联每个愿望
- 多种相框、贴纸、布局选择
- 温暖治愈的UI/UX设计

### ⏳ 专注时光记录（核心创新）
- **存入专注时光**：1小时专注 = 1个"时光币"
- **视觉显化系统**：
  - 10小时：星星点点效果
  - 30小时：微光荧光效果  
  - 60小时：金色流光效果
  - 100小时：钻石七彩流光效果
- **多巴胺反馈**：投币动画 + 风铃音效

### 🔮 年度NFT纪念
- 年终自动生成愿景板NFT
- Sepolia测试网铸造
- 记录一年专注时光的成就

## 🛠 技术栈
前端： HTML5 · CSS3 · JavaScript (ES6+)
动画： Lottie · CSS Animations
Web3： Ethers.js · MetaMask集成
存储： LocalStorage (v1) · 计划迁移IPFS
设计： 手绘风格 · 响应式布局 · 暖色调
音频： Web Audio API · 背景音乐系统


## 📁 项目结构
vision-focus-hours/
├── src/
│ ├── pages/ # 5个主要页面
│ │ ├── meditation/ # 冥想引导页
│ │ ├── wishes-input/ # 愿望输入页
│ │ ├── editor/ # 愿景板编辑页
│ │ ├── fullscreen/ # 全屏查看页
│ │ └── nft/ # NFT生成页
│ ├── components/ # 可复用组件
│ │ ├── WalletConnect/ # 钱包连接
│ │ ├── PomodoroTimer/ # 番茄钟
│ │ ├── CoinEffect/ # 投币动画
│ │ └── VisionItem/ # 愿景碎片组件
│ ├── assets/ # 静态资源
│ │ ├── audio/ # 音效和音乐
│ │ ├── images/ # 图片和贴纸
│ │ └── animations/ # Lottie动画
│ ├── styles/ # 全局样式
│ └── utils/ # 工具函数
├── docs/ # 项目文档
├── contracts/ # 智能合约 (可选)
└── tests/ # 测试文件


## 🎯 路线图

### P0 (核心功能 - 黑客松版本)
- ✅ 钱包连接 (MetaMask)
- ✅ 冥想引导流程
- ✅ 愿望碎片输入系统
- ✅ 愿景板基础编辑器
- ✅ 投币交互与显化效果
- ✅ 本地存储与状态管理
- ✅ Sepolia测试网NFT铸造

### P1 (增强体验)
- 🔄 番茄钟专注计时器
- 🔄 更多贴纸和相框素材
- 🔄 导出/导入愿景配置
- 🔄 调试模式和演示功能

### P2 (未来规划)
- 📅 季度回顾和统计数据
- 📅 社交分享功能
- 📅 移动端适配优化
- 📅 IPFS去中心化存储
- 📅 多链支持 (Polygon, Arbitrum)

## 📄 许可证

本项目采用**非商业许可证**，详情请参阅 [LICENSE](LICENSE) 文件。

### 许可证要点
- ✅ **允许**：个人使用、学习、教育用途、开源贡献
- ❌ **禁止**：商业使用、闭源分发、商标商业使用
- 📧 **商业许可**：如需商业使用，请联系项目维护者获取商业许可

**重要提示**：使用本软件即表示您同意遵守许可证条款。违反许可证的行为可能导致法律后果。

## 🏗 开发指南

### 环境要求
- Node.js 16+
- MetaMask钱包
- 现代浏览器 (Chrome/Firefox/Edge)

### 快速开始
```bash
# 克隆项目
git clone https://github.com/yourusername/vision-focus-hours.git
cd vision-focus-hours

# 安装依赖 (如果有构建步骤)
npm install

# 启动开发服务器
npm run dev

# 打开浏览器访问
# http://localhost:3000


用每一小时专注，绘制未来的自己
Every hour focused, paints a clearer future.



