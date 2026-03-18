# Brent Oil Market Analysis Dashboard (Power BI)

## Project Overview

This project analyzes Brent Oil Futures daily market data for 2025 and presents insights through an interactive Power BI dashboard.

The goal of this project is to demonstrate **data cleaning, financial time-series analysis, KPI development, and dashboard design** using Power BI.

The dashboard allows users to explore oil price trends, volatility patterns, and trading activity through interactive visualizations.

---

## Business Problem

Energy traders and analysts need tools to monitor oil price movements and market volatility in order to support trading strategies and investment decisions.

This dashboard helps answer questions such as:

* How has the Brent oil price evolved over time?
* When did the market experience the highest volatility?
* Is there a relationship between trading volume and price movement?
* What trends can be observed using moving averages?

---

## Dataset

Dataset used: **Brent Oil Futures Historical Data (Daily 2025)**

Columns included:

| Column   | Description                   |
| -------- | ----------------------------- |
| Date     | Trading date                  |
| Price    | Closing price                 |
| Open     | Opening price                 |
| High     | Highest price of the day      |
| Low      | Lowest price of the day       |
| Volume   | Daily trading volume          |
| Change % | Daily price change percentage |

---

## Data Cleaning

Data preprocessing was performed in Power Query.

Steps included:

* Converting Date column to Date format
* Cleaning Volume column (removing K notation and converting to numeric values)
* Removing % symbol from Change column
* Converting Change % to decimal values
* Creating calculated fields for volatility analysis

---

## Key Metrics

The dashboard calculates several important financial indicators:

* Average Price
* Maximum Price
* Minimum Price
* Total Trading Volume
* Average Daily Change
* Market Volatility

Advanced analytics include:

* 7-Day Moving Average
* 30-Day Moving Average
* Daily Trading Range

---

## Dashboard Pages

### 1. Market Overview

Provides a high-level summary of the oil market.

Visuals include:

* KPI cards (Average Price, Max Price, Min Price, Volatility)
* Price trend line chart
* Moving average trend analysis

---

### 2. Volatility Analysis

Focuses on market instability and price fluctuations.

Visuals include:

* Daily price range chart
* Daily percentage change chart
* Volatility indicators

---

### 3. Trading Activity

Examines the relationship between market activity and price movement.

Visuals include:

* Price vs Volume combo chart
* Volume vs Price scatter plot

---

## Tools Used

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)

---

## Skills Demonstrated

* Data cleaning and transformation
* Time-series data analysis
* Financial market analysis
* Data visualization
* Interactive dashboard development
* Data storytelling

---

## Key Insights

Some insights derived from the dashboard include:

* Oil prices showed periodic fluctuations throughout 2025.
* Certain trading periods exhibited higher volatility with wider daily price ranges.
* Increased trading volumes often corresponded with larger price movements.

---

## Project Files

Repository structure:

Brent-Oil-PowerBI-Dashboard/
│
├── data/
│   └── brent_oil_daily_2025.csv
│
├── dashboard/
│   └── brent_oil_dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md

---

## How to Use

1. Download the `.pbix` file
2. Open it using Power BI Desktop
3. Explore the interactive dashboard

---

## Future Improvements

Possible enhancements include:

* Oil price forecasting
* Additional technical indicators (RSI, Bollinger Bands)
* Multi-year analysis
* Integration with live market data

---

## Author:

Ransford Djabang
Data Analytics Portfolio Project
