# Sales Analytics Dashboard

A professional, interactive sales analytics dashboard built with React and Recharts. Designed to visualize revenue performance, product trends, customer segmentation, and profitability at a glance.

## Features

- **KPI Overview** — Total Revenue, Total Profit, Profit Margin, Orders, and Average Order Value, each with period-over-period trend indicators
- **Monthly Sales Trend** — Revenue vs. Profit over time (3M / 6M / 12M views)
- **Top Products** — Ranked bar chart of best-performing products by revenue
- **Customer Segmentation** — Revenue breakdown by customer segment (Enterprise, Mid-Market, SMB, Individual)
- **Profit Analysis** — Profit and margin comparison across product categories
- **Interactive Filters** — Cascading Region → Country → State/Province filters, plus Category and Segment filters, all live-updating every chart and KPI

## Tech Stack

- **React** — component architecture and state management
- **Recharts** — data visualization (area, bar, and pie charts)
- **Custom design system** — dark "financial ledger" theme with Fraunces, Inter, and IBM Plex Mono typography

## Data

Uses realistic sample transaction data spanning 12 months across 4 global regions, 24 countries, and 90+ states/provinces. Data structure is modular — swap in a real CSV or API source without changing the dashboard logic.

## Preview

*(Add a screenshot or screen recording of the dashboard here)*

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Run locally: `npm start`

## Author

Built by [Elamkavi](https://github.com/Elamkavi518) — final-year IT student exploring data analytics and career opportunities in motorsport strategy and performance analysis.
