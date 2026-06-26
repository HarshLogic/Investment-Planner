# Investment Planner 📈

A premium, interactive portfolio allocation dashboard designed to help users structure their wealth elegantly. Input your salary, set your ideal allocation targets across diverse asset classes, and instantly visualize your monthly capital distribution.

Live Demo: [investment-planner-portfolio.vercel.app](https://investment-planner-portfolio.vercel.app/)

---

## ✨ Features

- **Interactive Multi-Step Flow:** Seamless UI transition from income input to asset allocation and final breakdown.
- **Dynamic Math Engine:** Real-time updates ensure that currency distribution dynamically scales to match input parameters.
- **Strict Validation:** Prevents form submission unless asset allocation totals exactly 100%.
- **Comprehensive Asset Support:** Built-in slots for ETFs, Stocks, Gold, Crypto, Government Bonds, Time Deposits, REITs, and Commodities.
- **Premium UI/UX:** Dark mode aesthetic with high-contrast indicator tracks and glassmorphic card layouts.

## 🛠️ Tech Stack

- **Frontend:** React.js / Next.js (Tailwind CSS)
- **Deployment:** Vercel

---

## 🚀 Future Roadmap & Vision

We are actively expanding this calculator into a full-scale, intelligent personal finance assistant. Here is what is on the horizon:

### 🔹 Phase 1: Core Persistence & Real-World Data
* **User Accounts & DB:** Integration of Clerk/NextAuth and MongoDB to let users save and manage multiple financial profiles.
* **Live Asset API Sync:** Connecting live market data feeds (Yahoo Finance, CoinGecko) to translate cash amounts into actual asset volumes based on current market rates.

### 🔹 Phase 2: AI Orchestration & Visualizations
* **Interactive Growth Forecasts:** Integration of `recharts` to render compound interest lines, showing the 5, 10, and 20-year future value of the user's monthly investment.
* **AI Financial Health Check:** An embedded LLM layer (via Vercel AI SDK) that reads the active portfolio split and provides immediate, objective risk analysis and optimization critiques.

### 🔹 Phase 3: Smart SaaS Tools
* **Goal-Oriented Mode:** Reverse-engineers asset allocations backward from a set target savings amount and timeline.
* **Drift & Rebalancing Alerts:** Calculates exactly how much of an asset needs to be bought or sold over time to keep the portfolio locked onto the original target percentages.

---

## 💻 Getting Started

### Prerequisites
- Node.js (v18.x or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/investment-planner.git](https://github.com/your-username/investment-planner.git)
   cd investment-planner
