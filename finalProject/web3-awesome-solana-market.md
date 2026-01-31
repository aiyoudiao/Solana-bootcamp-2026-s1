# 项目名称

> PolyScore (Web3 Awesome Solana Market)

## 💻 项目 Repo

https://github.com/aiyoudiao/web3-awesome-solana-market

## 📌 项目简介

**PolyScore** 是一个基于 Solana 构建的沉浸式体育/电竞预测市场平台。它打破了传统预测市场的枯燥表格形式，通过 Web3 技术与 3D 可视化交互的结合，为用户提供像“看比赛、切视角”一样直观、有趣的链上竞猜体验。

本项目旨在参加 Solana 黑客松，探索 Consumer Crypto 应用的新形态：[👉 点击查看参赛推文](https://x.com/Aiom09/status/2016464207295009053?s=20)。

在线演示说明：仓库 Website 配置的地址 prediction-market-dapp.netlify.app 仅为部分纯前端 UI 演示，尚未完成与智能合约、后端服务的线上联调。若要体验完整交互（前后端 + 合约测试的完整版本），请参考仓库的“快速开始”在本地运行。

## 🛠️ 技术栈

- 智能合约：Rust + Anchor（合约目录：`contract/`，Program：`soldora`）
- 前端：Next.js 16（App Router）+ React 19 + TypeScript
- UI/动画：Tailwind CSS + Framer Motion
- 3D：React Three Fiber + Drei + Three.js
- 状态/数据：Zustand + TanStack Query
- Web3：Solana（Devnet/Mainnet）+ `@solana/web3.js` + Solana Wallet Adapter（Phantom / Solflare / Backpack 等）
- 后端：Supabase（PostgreSQL）+ Next.js API Routes

## 🎬 Demo 演示

### 演示链接

- 🎥 视频演示（仓库内）：./video/4ba995fdf31165b0409552e043d2d151_raw.mp4
- 🌐 在线 Demo（部分 UI）：https://prediction-market-dapp.netlify.app

### 功能截图

| 3D 沉浸式大厅 | 2D 极简列表 |
| :-: | :-: |
| ![3D Lobby](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/3d-home-list.png) | ![2D List](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/home-list.png) |

| 市场详情与交易 | 链上支付交互 |
| :-: | :-: |
| ![Detail](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/item-detail.png) | ![Pay](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/contact-pay.png) |

| 创建预测事件 | 个人中心 |
| :-: | :-: |
| ![Create](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/create-event.png) | ![Profile](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/profile.png) |

| 管理员后台 | 社交分享卡片 |
| :-: | :-: |
| ![Admin](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/admin.png) | ![Card](https://raw.githubusercontent.com/aiyoudiao/web3-awesome-solana-market/main/images/card.png) |

## 💡 核心功能

1. 沉浸式 3D 大厅与市场详情页（Cyberpunk 风格），提升链上交易的可玩性
2. 2D/3D 双模式一键切换（效率交易 / 视觉沉浸）
3. Solana 链上快速结算与交互（下单、结算等）
4. 社交化挑战：生成挑战卡片，一键分享至社交平台
5. 实时动态：赔率变化与“弹幕式”交易流/评论氛围

## ✍️ 项目创作者：

1. Btrain（GitHub：https://github.com/bcy97）
2. Jade（GitHub：https://github.com/JadeTwinkle）
3. Livian（GitHub：https://github.com/TLwen114514）
4. peihao（GitHub：https://github.com/aiyoudiao）

创作者联系方式：见各自 GitHub 主页（README 未提供其他联系方式）

创作者 Solana USDC 钱包地址：
- peihao：BVYLTa8Hm1WJJ265CNBLinQ75NdA6gMt6hfSTxJL4cGx

