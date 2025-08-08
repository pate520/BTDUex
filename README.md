# BTDUex - Digital Asset Trading Platform

🚀 **Modern Cryptocurrency Trading Platform Website**

## ✨ Features

### 🎨 Visual Effects
- **3D Brand Animation** - Cool brand animation effects implemented with CSS3
- **Coin Animation Area** - 3D floating effects for mainstream cryptocurrencies including BTC, ETH, BNB, SOL, ADA
- **Geometric Shape Animation** - Dynamic display of geometric elements like cubes, spheres, triangles
- **Particle Effect System** - Enhanced visual layering
- **Responsive Design** - Perfect adaptation for desktop and mobile devices

### 📊 Functional Features
- **Real-time Market Data** - Integrated CoinGecko API for real cryptocurrency prices
- **Multi-language Support** - Chinese/English bilingual switching
- **Dark/Light Theme** - Users can freely switch theme modes
- **Latest News** - Latest digital currency news updates from July 2025
- **Platform Advantages** - Security guarantee, low fees, high liquidity, 24/7 customer service

### 🛠 Tech Stack
- **Pure HTML/CSS/JavaScript** - No framework dependencies, lightweight and efficient
- **CSS3 Animation** - Smooth 3D transforms and animation effects
- **Fetch API** - Asynchronous real-time market data retrieval
- **LocalStorage** - Save user preferences
- **Service Worker** - Offline caching support

## 🌐 Live Demo

Visit: [https://pate520.github.io/BTDUex/](https://pate520.github.io/BTDUex/)

## 🚀 Quick Start

### Local Development
```bash
# Clone repository
git clone https://github.com/pate520/BTDUex.git

# Enter project directory
cd BTDUex

# Start local server (Python)
python3 -m http.server 8000

# Or use Node.js
npx serve .

# Visit http://localhost:8000
```

### GitHub Pages Deployment
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Select main branch as source
4. Visit `https://yourusername.github.io/BTDUex/`

## 📱 Responsive Design

- **Desktop** (1200px+) - Full feature display
- **Tablet** (768px-1199px) - Optimized layout
- **Mobile** (<768px) - Simplified interface, maintaining core functionality

## 🎯 Core Highlights

### 1. 3D Brand Animation
- Independent 3D animation effects for each letter
- Gradient colors and glow effects
- Mouse hover interaction animations

### 2. Real-time Data Integration
- Automatic retrieval of 8 mainstream cryptocurrency prices
- Real-time price change display
- Market cap and 24-hour trading volume data

### 3. Modern UI Design
- Dark theme as primary with light theme switching support
- Frosted glass effects and shadow design
- Smooth transition animations

## 📊 Supported Cryptocurrencies

| Currency | Code | Features |
|----------|------|----------|
| Bitcoin | BTC | Digital gold, market cap leader |
| Ethereum | ETH | Smart contract platform |
| BNB | BNB | Binance ecosystem token |
| XRP | XRP | Cross-border payment solution |
| Cardano | ADA | Academic research driven |
| Solana | SOL | High-performance blockchain |
| Dogecoin | DOGE | Community-driven meme coin |
| Tether | USDT | Stablecoin |

## 🔧 Custom Configuration

### Modify Supported Cryptocurrencies
Edit the `supportedCoins` array in `index.html`:

```javascript
const supportedCoins = [
    'bitcoin', 'ethereum', 'binancecoin', 'ripple',
    'cardano', 'solana', 'dogecoin', 'tether'
];
```

### Add New Languages
Add new languages to the `translations` object:

```javascript
const translations = {
    'zh-TW': { /* Chinese translations */ },
    'en': { /* English translations */ },
    'ja': { /* Japanese translations */ }  // New addition
};
```

## 📈 Performance Optimization

- **Image Lazy Loading** - Improve page loading speed
- **CSS Animation Optimization** - Use transform and opacity to avoid reflow
- **API Caching** - Reduce unnecessary network requests
- **Code Compression** - Recommended for production environment

## 🤝 Contributing Guidelines

1. Fork the project
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## 📞 Contact

- **Project Link**: [https://github.com/pate520/BTDUex](https://github.com/pate520/BTDUex)
- **Live Demo**: [https://pate520.github.io/BTDUex/](https://pate520.github.io/BTDUex/)

---

⭐ If this project is helpful to you, please give it a Star for support!