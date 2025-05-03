# Custom Hooks for Fetching Stock Data

This section contains custom hooks designed for fetching stock data. These hooks utilize **React Query** for data fetching and caching, and they manage fetching both stock quotes and historical data.

## `useStockQuote` Hook

The `useStockQuote` hook is used to fetch the latest stock quote for a given symbol.

### Usage

```tsx
const { data, isLoading, error } = useStockQuote(symbol);
