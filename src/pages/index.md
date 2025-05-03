# 📈 Stock Market Dashboard

A modern, responsive **Stock Market Dashboard** built with React, Tailwind CSS, and Alpha Vantage API. This project displays real-time and historical stock data for selected companies, with support for searching, filtering, and interactive UI components. It provides a clean layout with a hero section, a lazily-loaded stock dashboard, error handling, and a footer.

## 🚀 Features

- 🔍 **Live Stock Quotes** using Alpha Vantage API
- 📊 **Historical Data Visualization**
- 🔁 **Mock Data Support** to avoid API rate limits
- 🧠 **Debounced Search** for performance
- 🧩 **React Query** for caching and auto-refresh
- ⚡ **Lazy Loading** for better initial performance
- 🛡️ **Error Boundaries** for resilience
- 💅 **Tailwind CSS** for sleek UI styling
- 🧪 **Skeleton Loaders** during data fetch

## 📂 Project Structure

src/
├── components/
│ ├── Hero.tsx
│ ├── StockDashboard.tsx (lazy-loaded)
│ ├── ErrorBoundary.tsx
│ └── ui/
│ ├── skeleton.tsx
│ └── use-toast.ts
├── hooks/
│ ├── useStockData.ts
│ └── useDebouncedCallback.ts
├── lib/
│ └── api.ts
├── pages/
│ └── index.tsx
├── utils/
│ └── cn.ts

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript
- **Styling:** Tailwind CSS
- **Data Fetching:** React Query
- **API:** Alpha Vantage (`demo` key used for development)
- **Tooling:** Vite or Next.js (depending on your setup)

## 🌐 API Integration

- fetchStockQuote(symbol): Gets current stock price & stats

- fetchStockHistory(symbol, interval): Gets historical data (mocked)

## 🧩 Key Components

**Hero.tsx**-Intro section of the landing page.

**StockDashboard.tsx**- Core dashboard displaying quote cards, charts, and search functionality.

**ErrorBoundary.tsx**Wraps around lazy components to catch runtime errors.

**NotFound.tsx**Simple 404 page using React Router’s useLocation().
Logs errors to console when unknown paths are accessed.

## 📦 Installation

```bash
git clone https://github.com/Himanshu Narware/stock-dashboard.git
cd stock-dashboard
npm install
