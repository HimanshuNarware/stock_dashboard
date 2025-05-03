# StockChart Component

The `StockChart` component visualizes historical stock data in a line chart format. It provides an interactive chart to view the price history of a specific stock symbol over time. Built with React, it uses the Recharts library for rendering the chart.

## Features

- **Price History**: Displays a line chart showing the stock's closing prices over time.
- **Custom Tooltip**: Shows detailed stock information (open, close, high, low prices) for each data point when hovered over.
- **Responsive**: The chart automatically adjusts to the available width and height.
- **Loading State**: Displays a loading message while data is being fetched.
- **Dynamic Y-Axis**: The Y-axis adjusts dynamically based on the minimum and maximum stock prices with a 10% padding for better visibility.
- **Change Indicator**: Highlights the overall change in the stock price between the first and last data points.

## Installation

Make sure you have the necessary dependencies installed for this component:

```bash
npm install recharts
