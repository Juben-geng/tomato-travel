# 番茄旅行AI助手

🍅 企业级AI驱动旅游定制师平台 — 智能匹配供应商，一键生成行程方案

## 🚀 在线演示

**Vercel 部署地址**: [https://tomato-travel.vercel.app](https://tomato-travel.vercel.app)

## ✨ 核心功能

### 🏨 实时酒店比价
- 多平台价格对比（途牛 + 飞猪 + 携程 + Booking + Agoda）
- 支持城市查询 + 酒店名搜索
- 实时价格、评分、取消政策
- 一键预订链接

### 🤖 AI智能助手
- 自然语言查询酒店价格
- 智能匹配供应商
- 行程方案生成

### 💬 真实聊天系统
- 用户和供应商真实沟通
- 消息通知 + 附件上传
- 收藏保存 + 自动回复

## 📦 部署说明

### Vercel 一键部署

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Juben-geng/tomato-travel)

### 环境变量

| 变量名 | 说明 |
|--------|------|
| FLYAI_API_URL | 飞猪API地址（可选） |

## 🛠️ 技术栈

- 前端: HTML + CSS + JavaScript
- 后端: Vercel Serverless Functions
- 数据: localStorage + 飞猪/途牛 API

## 📄 文件说明

| 文件 | 功能 |
|------|------|
| index.html | 🏠 首页 |
| hotel-price-comparison.html | 🏨 酒店比价 |
| index-full.html | 🤖 AI助手 |
| admin-panel.html | 🔐 管理后台 |
| api/hotel/search.js | 📡 酒店API |

---

🍅 番茄旅行AI — 让旅游定制更智能