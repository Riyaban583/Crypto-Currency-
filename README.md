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



## 🙏 Acknowledgments

Special thanks to:

- 🪙 **[CoinGecko](https://www.coingecko.com/)** - For providing the free cryptocurrency API
- 📊 **[Google Charts](https://developers.google.com/chart)** - For the charting library
- ⚛️ **[React Team](https://react.dev/)** - For the amazing framework
- ⚡ **[Vite Team](https://vitejs.dev/)** - For the blazing-fast build tool
- 🎨 **[Shields.io](https://shields.io/)** - For the awesome badges
- 💡 **Open Source Community** - For inspiration and resources

---


<div align="center">

### ⭐ Star this repository if you found it helpful!

**Made with ❤️ by [Riya Bansal](https://github.com/Riyaban583)**

[![GitHub followers](https://img.shields.io/github/followers/Riyaban583?style=social)](https://github.com/Riyaban583)
[![GitHub stars](https://img.shields.io/github/stars/Riyaban583/Crypto-Currency-?style=social)](https://github.com/Riyaban583/Crypto-Currency-)

---

**Happy Coding! 🚀**

</div>
