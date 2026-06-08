# 🔍 AI 模型价格雷达

一页看清所有AI模型价格，输入用量即算月费，选最划算的模型。

## ✨ 功能

- 📊 **模型价格总览** — 覆盖 OpenAI / Anthropic / Google / DeepSeek / 阿里 / Mistral / Meta 全部主流模型
- 💰 **月费计算器** — 输入每月用量，自动计算每个模型的月费，高亮最便宜TOP 6
- 🎯 **场景推荐** — 预设6种使用场景（对话/代码/文档/图片/批量/推理），一键填充用量
- ⭐ **收藏功能** — 收藏常用模型，本地保存不丢失
- 📱 **响应式设计** — 手机/平板/桌面都能用
- 🌙 **暗色主题** — GitHub Dark 风格，护眼舒适

## 🚀 使用

直接打开 [在线地址](https://watermelontip.github.io/ai-pricing-radar/) 即可使用，无需注册或配置。

或者本地运行：
```bash
# 方法1：直接用浏览器打开
start index.html

# 方法2：本地服务器
npx http-server -p 8080
```

## 📸 截图

> 暗色主题 · 响应式布局 · 一键计算

## 🛠️ 技术栈

- 纯 HTML / CSS / JavaScript，零依赖
- CSS 变量化主题系统
- localStorage 本地存储
- GitHub Pages 部署

## 📝 更新模型价格

打开 `index.html`，找到 `MODELS` 数组，修改对应模型的价格即可：

```javascript
{ id:"gpt-4o", name:"GPT-4o", provider:"OpenAI", inputPrice:2.5, outputPrice:10, ... }
```

价格单位：$/1M tokens

## 📄 License

MIT
