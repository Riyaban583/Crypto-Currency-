# 💰 Crypto Currency Tracker

<div align="center">

![Crypto Tracker Banner](https://img.shields.io/badge/Crypto-Tracker-gold?style=for-the-badge&logo=bitcoin&logoColor=white)

A modern, responsive cryptocurrency tracking web application built with **React** that provides real-time crypto prices, market data, and interactive charts powered by the CoinGecko API.

[![Live Demo](https://img.shields.io/badge/demo-live-success?style=for-the-badge)](https://your-demo-link.com)
[![GitHub](https://img.shields.io/badge/github-repo-blue?style=for-the-badge&logo=github)](https://github.com/Riyaban583/Crypto-Currency-)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)

[Features](#-features) • [Demo](#-demo) • [Installation](#%EF%B8%8F-installation--setup) • [Usage](#-usage) • [Tech Stack](#%EF%B8%8F-tech-stack) • [Contributing](#-contributing)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Screenshots](#-screenshots)
- [Tech Stack](#%EF%B8%8F-tech-stack)
- [Installation & Setup](#%EF%B8%8F-installation--setup)
- [Project Structure](#-project-structure)
- [Usage](#-usage)
- [API Reference](#-api-reference)
- [Learnings](#-learnings)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [Author](#%EF%B8%8F-author)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 🌟 Overview

Crypto Currency Tracker is a sleek and intuitive web application designed for crypto enthusiasts to monitor real-time cryptocurrency prices and market trends. Built with modern React practices and powered by the CoinGecko API, it delivers a seamless experience for tracking your favorite digital assets.

**Why this project?**
- Practice modern React development patterns
- Learn API integration and data fetching
- Implement global state management with Context API
- Create responsive, user-friendly interfaces
- Work with real-time financial data

---

## ✨ Features

### Core Functionality
- 📊 **Real-time Market Data** - Live cryptocurrency prices updated from CoinGecko API
- 🔍 **Smart Search** - Quickly find cryptocurrencies by name or symbol
- 📈 **Interactive Charts** - Visualize price trends over the last 10 days using Google Charts
- 💱 **Multi-Currency Support** - View prices in USD, INR, EUR, and more
- 🟢🔴 **Price Change Indicators** - Track 24-hour price movements with color-coded indicators
- 🪙 **Detailed Coin Pages** - Comprehensive information including market cap, volume, and supply

### User Experience
- ⏳ **Loading States** - Elegant loading spinners for better UX
- 📱 **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- 🎨 **Modern UI** - Clean and intuitive interface
- ⚡ **Fast Performance** - Optimized with Vite for lightning-fast load times

---

## 🎬 Demo

### 🔗 Live Demo
🚀 **[View Live Application](https://your-demo-link.com)** _(Coming Soon)_

> **Note:** Add your deployed app link here (Netlify, Vercel, GitHub Pages, etc.)

### 🎥 Video Walkthrough
_Add a GIF or video demonstration here_

---

## 📸 Screenshots

<details>
<summary>Click to view screenshots</summary>

### Home Page - Crypto List
![Home Page](./screenshots/home.png)
> Browse through the top cryptocurrencies with real-time prices and market data

### Coin Detail Page
![Coin Detail](./screenshots/coin.png)
> Detailed view with interactive charts and comprehensive market information

### Search Functionality
![Search Feature](./screenshots/search.png)
> Quickly find your favorite cryptocurrencies

### Responsive Design
![Mobile View](./screenshots/mobile.png)
> Fully responsive across all devices

</details>

> **To add screenshots:** Create a `screenshots` folder in your repository and add images with the names shown above.

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### Libraries & Tools
- **React Router DOM** - Client-side routing
- **Context API** - Global state management
- **Google Charts** - Data visualization
- **CoinGecko API** - Cryptocurrency data
- **Git** - Version control
- **npm** - Package management

---

## ⚙️ Installation & Setup

### Prerequisites
Before you begin, ensure you have the following installed:
- **Node.js** (v14 or higher) - [Download here](https://nodejs.org/)
- **npm** or **yarn** - Comes with Node.js
- **Git** - [Download here](https://git-scm.com/)

### 🚀 Quick Start

#### 1️⃣ Clone the repository
```bash
git clone https://github.com/Riyaban583/Crypto-Currency-.git
```

#### 2️⃣ Navigate to the project directory
```bash
cd Crypto-Currency-
```

#### 3️⃣ Install dependencies
```bash
npm install
```

#### 4️⃣ Start the development server
```bash
npm run dev
```

#### 5️⃣ Open your browser
The application will be running at:
```
http://localhost:5173
```

### 🏗️ Build for Production

To create an optimized production build:
```bash
npm run build
```

To preview the production build locally:
```bash
npm run preview
```

---

## 📂 Project Structure

```
Crypto-Currency-/
│
├── public/                      # Static assets
│   └── favicon.ico
│
├── src/                         # Source files
│   ├── assets/                  # Images, icons, etc.
│   │   └── logo.png
│   │
│   ├── components/              # Reusable components
│   │   ├── LineChart/
│   │   │   ├── LineChart.jsx
│   │   │   └── LineChart.css
│   │   ├── Navbar/
│   │   │   ├── Navbar.jsx
│   │   │   └── Navbar.css
│   │   └── Footer/
│   │       ├── Footer.jsx
│   │       └── Footer.css
│   │
│   ├── context/                 # Context API
│   │   └── CoinContext.jsx      # Global state management
│   │
│   ├── pages/                   # Page components
│   │   ├── Home/
│   │   │   ├── Home.jsx
│   │   │   └── Home.css
│   │   └── Coin/
│   │       ├── Coin.jsx
│   │       └── Coin.css
│   │
│   ├── App.jsx                  # Main App component
│   ├── App.css                  # Global styles
│   ├── main.jsx                 # Entry point
│   └── index.css                # Base styles
│
├── .gitignore                   # Git ignore file
├── index.html                   # HTML template
├── package.json                 # Dependencies and scripts
├── vite.config.js               # Vite configuration
└── README.md                    # Project documentation
```

---

## 💡 Usage

### Browsing Cryptocurrencies
1. Open the application in your browser
2. The home page displays a list of top cryptocurrencies
3. Scroll through the list to see prices, market cap, and 24h changes

### Searching for a Coin
1. Use the search bar at the top of the page
2. Type the name or symbol of the cryptocurrency
3. The list will filter in real-time

### Viewing Coin Details
1. Click on any cryptocurrency from the list
2. View detailed information including:
   - Current price and market cap
   - 24-hour trading volume
   - Price change percentage
   - 10-day price chart
   - Circulating supply

### Changing Currency
1. Use the currency selector in the navbar
2. Choose your preferred currency (USD, INR, EUR)
3. All prices will update automatically

---

## 🔌 API Reference

This project uses the **CoinGecko API** - a free, comprehensive cryptocurrency data API.

### Endpoints Used

#### Get Market Data
```
GET https://api.coingecko.com/api/v3/coins/markets
```
**Parameters:**
- `vs_currency`: The target currency (usd, inr, eur)
- `order`: Sort order (market_cap_desc)
- `per_page`: Number of results per page
- `page`: Page number

#### Get Coin Details
```
GET https://api.coingecko.com/api/v3/coins/{id}
```
**Parameters:**
- `id`: Coin ID (bitcoin, ethereum, etc.)

#### Get Historical Chart Data
```
GET https://api.coingecko.com/api/v3/coins/{id}/market_chart
```
**Parameters:**
- `id`: Coin ID
- `vs_currency`: Target currency
- `days`: Number of days (10)

### Rate Limits
- CoinGecko free tier: 10-50 calls/minute
- No API key required for basic usage

**Documentation:** [CoinGecko API Docs](https://www.coingecko.com/en/api/documentation)

---

## 🧠 Learnings

### Technical Skills Gained
- ✅ **API Integration** - Fetching and handling real-time data from external APIs
- ✅ **State Management** - Using React Context API for global state
- ✅ **Async Operations** - Managing async/await and handling loading states
- ✅ **React Hooks** - Practical use of useState, useEffect, useContext
- ✅ **React Router** - Implementing client-side routing and navigation
- ✅ **Data Visualization** - Creating interactive charts with Google Charts
- ✅ **Responsive Design** - Building mobile-first, responsive layouts
- ✅ **Error Handling** - Gracefully handling API errors and edge cases
- ✅ **Git Workflow** - Version control and GitHub collaboration

### Best Practices Implemented
- Component-based architecture
- Separation of concerns
- Clean code principles
- Proper file organization
- Meaningful commit messages

---

## 🚀 Future Enhancements

### Planned Features
- [ ] 🌙 Dark/Light theme toggle
- [ ] ⭐ Favorites/Watchlist functionality
- [ ] 📊 More chart types (candlestick, area charts)
- [ ] 🔔 Price alerts and notifications
- [ ] 📈 Portfolio tracking
- [ ] 🔄 Auto-refresh prices
- [ ] 📱 PWA (Progressive Web App) support
- [ ] 🌍 More currency options
- [ ] 📰 Crypto news integration
- [ ] 📊 Advanced filtering and sorting
- [ ] 💾 Local storage for user preferences

### Technical Improvements
- [ ] TypeScript migration
- [ ] Unit and integration tests
- [ ] Performance optimization
- [ ] Better error boundaries
- [ ] Accessibility improvements (WCAG compliance)

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**!

### How to Contribute

1. **Fork the Project**
   ```bash
   # Click the 'Fork' button at the top right of this page
   ```

2. **Clone your Fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Crypto-Currency-.git
   ```

3. **Create a Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

4. **Make your Changes**
   - Write clean, readable code
   - Follow the existing code style
   - Test your changes thoroughly

5. **Commit your Changes**
   ```bash
   git add .
   git commit -m "Add some AmazingFeature"
   ```

6. **Push to your Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

7. **Open a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Describe your changes

### Contribution Guidelines
- Write clear, descriptive commit messages
- Update documentation for any new features
- Ensure your code follows the project's coding standards
- Test your changes before submitting a PR
- Be respectful and constructive in discussions

---

## 👩‍💻 Author

<div align="center">

### **Riya Bansal**

[![GitHub](https://img.shields.io/badge/GitHub-Riyaban583-black?style=for-the-badge&logo=github)](https://github.com/Riyaban583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/your-profile)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-orange?style=for-the-badge&logo=google-chrome)](https://your-portfolio.com)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:your.email@example.com)

**Passionate about building modern web applications and learning new technologies!**

</div>

> 💡 **Note:** Update the LinkedIn, Portfolio, and Email links with your actual profiles

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use

---

## 🙏 Acknowledgments

Special thanks to:

- 🪙 **[CoinGecko](https://www.coingecko.com/)** - For providing the free cryptocurrency API
- 📊 **[Google Charts](https://developers.google.com/chart)** - For the charting library
- ⚛️ **[React Team](https://react.dev/)** - For the amazing framework
- ⚡ **[Vite Team](https://vitejs.dev/)** - For the blazing-fast build tool
- 🎨 **[Shields.io](https://shields.io/)** - For the awesome badges
- 💡 **Open Source Community** - For inspiration and resources

---

## 📞 Support

If you have any questions, issues, or suggestions:

- 🐛 **Report bugs:** [Open an issue](https://github.com/Riyaban583/Crypto-Currency-/issues)
- 💬 **Discussions:** [Join discussions](https://github.com/Riyaban583/Crypto-Currency-/discussions)
- ⭐ **Star this repo** if you find it helpful!

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

**Made with ❤️ by [Riya Bansal](https://github.com/Riyaban583)**

[![GitHub followers](https://img.shields.io/github/followers/Riyaban583?style=social)](https://github.com/Riyaban583)
[![GitHub stars](https://img.shields.io/github/stars/Riyaban583/Crypto-Currency-?style=social)](https://github.com/Riyaban583/Crypto-Currency-)

---

**Happy Coding! 🚀**

</div>
