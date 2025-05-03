# Stock Data API Utilities

This module provides functions to fetch stock quote and historical data using the **Alpha Vantage API**, along with mock data for development and demo purposes.

---

## 🔐 Environment Setup

> **Note**: The `API_KEY` is hardcoded as `"demo"` for testing. In production, store your Alpha Vantage API key in an environment variable.

---

## 📘 Types

### `StockQuote`

Represents a single stock's current quote.

```ts
interface StockQuote {
  symbol: string;
  companyName?: string;
  price: number;
  change: number;
  changePercent: number;
  previousClose: number;
  high: number;
  low: number;
  volume: number;
  lastUpdated: string;
}
