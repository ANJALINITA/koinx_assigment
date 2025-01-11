

# KoinX - Frontend Intern Assignment

This project is a solution for the KoinX Frontend Intern Assignment. It demonstrates the implementation of a responsive web application using **React.js** that mimics the provided Figma design and integrates with APIs from **Coingecko** and **TradingView**.

---

## 🚀 Live Demo

Check out the live version of the project hosted on [Vercel](https://koinx-assigment-opal.vercel.app/).

---

## 📂 Features

### 1. **Bitcoin Price Display**
- Fetches the price of Bitcoin in **INR** and **USD** using Coingecko's `/simple/price` API.
- Displays the **24-hour price change** for Bitcoin in USD.

### 2. **Trending Coins (24h)**
- Fetches the top 3 trending coins using Coingecko's `/search/trending` API.
- Displays coin name, symbol, and other details in the “Trending Coins” section.

### 3. **Price Chart**
- Embeds a **TradingView Advanced Chart Widget** to display Bitcoin's price chart.
- Customizes the widget to match the Figma design as closely as possible.

### 4. **You May Also Like**
- Shows the top 3 trending coins in a **horizontally scrollable carousel**.
- Displays coin logo, symbol, price, 24-hour price change, and a sparkline graph.

### 5. **Responsive Design**
- Ensures the UI is fully responsive and matches the Figma design on all screen sizes.

### 6. **Optional Task**
- Implements dynamic token routing. For example:
  - `/bitcoin` shows Bitcoin's data and chart.
  - `/ethereum` shows Ethereum's data and chart.
- Fetches the relevant coin's details using Coingecko's `/coins/{id}` API.

---

## 🛠️ Technologies Used

- **React.js**: Frontend framework.
- **Coingecko API**: Fetch cryptocurrency data.
- **TradingView Widget**: Display price charts.
- **CSS/SCSS**: Styling the application (optional use of Tailwind CSS).
- **Netlify/Vercel**: Deployment platform.

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/ANJALINITA/koinx_assigment.git
cd koinx_assigment
