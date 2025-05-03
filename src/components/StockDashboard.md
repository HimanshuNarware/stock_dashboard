# StockDashboard Component

The `StockDashboard` component is a central part of a stock market dashboard application. It displays a list of stock quotes and their details, provides a search functionality, and shows a stock chart with historical data. The component utilizes lazy loading for the chart and includes error handling and loading states to ensure a smooth user experience.

## Features

- **Stock List**: Displays a list of stocks with detailed information such as stock symbol, company name, price, and change in price.
- **Search Functionality**: Allows users to search for stocks by symbol or company name.
- **Lazy Loading for Chart**: The chart for the selected stock is lazily loaded to optimize performance.
- **Error Boundary**: Ensures that if an error occurs within the stock list or chart, it will be gracefully handled and displayed.
- **Loading Skeletons**: Displays loading skeletons while stock data or the chart is being fetched.
- **Chart for Selected Stock**: Displays a line chart for the selected stock's historical data.

## Installation

Make sure you have the necessary dependencies installed for this component:

```bash
npm install react-skeleton-loader
