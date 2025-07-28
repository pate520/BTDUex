# BTDUex - 数字资产交易平台

🚀 **现代化的加密货币交易平台网站**

## ✨ 特性

### 🎨 视觉效果
- **3D品牌动画** - CSS3实现的炫酷品牌名动画效果
- **币种动画区域** - 包含BTC、ETH、BNB、SOL、ADA等主流币种的3D浮动效果
- **几何形状动画** - 立方体、球体、三角形等几何元素的动态展示
- **粒子效果系统** - 增强视觉层次感
- **响应式设计** - 完美适配桌面端和移动端

### 📊 功能特性
- **实时市场数据** - 集成CoinGecko API获取真实加密货币价格
- **多语言支持** - 中文/英文双语切换
- **深色/浅色主题** - 用户可自由切换主题模式
- **最新资讯** - 2025年7月最新的数字货币新闻动态
- **平台优势展示** - 安全保障、低手续费、高流动性、24/7客服

### 🛠 技术栈
- **纯HTML/CSS/JavaScript** - 无框架依赖，轻量高效
- **CSS3动画** - 流畅的3D变换和动画效果
- **Fetch API** - 异步获取实时市场数据
- **LocalStorage** - 保存用户偏好设置
- **Service Worker** - 离线缓存支持

## 🌐 在线演示

访问：[https://pate520.github.io/BTDUex/](https://pate520.github.io/BTDUex/)

## 🚀 快速开始

### 本地运行
```bash
# 克隆仓库
git clone https://github.com/pate520/BTDUex.git

# 进入项目目录
cd BTDUex

# 启动本地服务器（Python）
python3 -m http.server 8000

# 或使用Node.js
npx serve .

# 访问 http://localhost:8000
```

### GitHub Pages部署
1. Fork此仓库
2. 在仓库设置中启用GitHub Pages
3. 选择main分支作为源
4. 访问 `https://yourusername.github.io/BTDUex/`

## 📱 响应式设计

- **桌面端** (1200px+) - 完整功能展示
- **平板端** (768px-1199px) - 优化布局
- **移动端** (<768px) - 简化界面，保持核心功能

## 🎯 核心亮点

### 1. 3D品牌动画
- 每个字母独立的3D动画效果
- 渐变色彩和发光效果
- 鼠标悬停交互动画

### 2. 实时数据集成
- 自动获取8种主流加密货币价格
- 实时涨跌幅显示
- 市值和24小时交易量数据

### 3. 现代化UI设计
- 深色主题为主，支持浅色切换
- 毛玻璃效果和阴影设计
- 流畅的过渡动画

## 📊 支持的加密货币

| 币种 | 代码 | 特色 |
|------|------|------|
| Bitcoin | BTC | 数字黄金，市值第一 |
| Ethereum | ETH | 智能合约平台 |
| BNB | BNB | 币安生态代币 |
| XRP | XRP | 跨境支付解决方案 |
| Cardano | ADA | 学术研究驱动 |
| Solana | SOL | 高性能区块链 |
| Dogecoin | DOGE | 社区驱动的模因币 |
| Tether | USDT | 稳定币 |

## 🔧 自定义配置

### 修改支持的币种
编辑 `index.html` 中的 `supportedCoins` 数组：

```javascript
const supportedCoins = [
    'bitcoin', 'ethereum', 'binancecoin', 'ripple',
    'cardano', 'solana', 'dogecoin', 'tether'
];
```

### 添加新的语言
在 `translations` 对象中添加新语言：

```javascript
const translations = {
    'zh': { /* 中文翻译 */ },
    'en': { /* 英文翻译 */ },
    'ja': { /* 日文翻译 */ }  // 新增
};
```

## 📈 性能优化

- **图片懒加载** - 提升页面加载速度
- **CSS动画优化** - 使用transform和opacity避免重排
- **API缓存** - 减少不必要的网络请求
- **代码压缩** - 生产环境建议压缩CSS/JS

## 🤝 贡献指南

1. Fork 项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系方式

- **项目链接**: [https://github.com/pate520/BTDUex](https://github.com/pate520/BTDUex)
- **在线演示**: [https://pate520.github.io/BTDUex/](https://pate520.github.io/BTDUex/)

---

⭐ 如果这个项目对您有帮助，请给个Star支持一下！
