from datetime import date

# Create a basic README content for the GitHub project
content =  📊 Amazon Stock Price Analysis Dashboard (Google Sheets Project)

## 🔍 Project Overview

This is a **complete real-time data analysis project** on Amazon stock prices using **Google Sheets**. The project involves:
- Data cleaning and formatting
- Daily return and moving average calculations
- Trendline and forecast modeling
- Interactive dashboard creation
- Tools used: **Google Sheets, Excel-style formulas**

---

## 📁 Dataset

- Source: [Yahoo Finance](https://finance.yahoo.com/quote/AMZN/history)
- Data range: Historical stock data from **January 2020 to May 2025**
- Format: `.csv` file containing `Date, Open, High, Low, Close, Volume`

---

## 🧮 Data Analysis Steps

### 1. **Data Cleaning**
- Removed extra headers/rows
- Converted `Date` to proper format
- Applied number formatting (2 decimal places)

### 2. **Calculated Columns**
| Column | Formula |
|--------|---------|
| **Daily Return (%)** | `(Close - Open) / Open * 100` |
| **7-Day MA** | `=AVERAGE(Close[-6]:Close[0])` |
| **30-Day MA** | `=AVERAGE(Close[-29]:Close[0])` |

### 3. **Trendline & Forecasting**
- Used Google Sheets chart options to add a **Linear Trendline**
- Projected **30 future days** using `FORECAST.LINEAR` formula

---

## 📊 Dashboard (Google Sheets)

The Dashboard includes:
- 📌 Key Metrics: Latest Close, Avg Price, Max/Min Price
- 📈 Line Charts: Close Prices, 7 & 30 Day Moving Averages
- 🔮 Forecasting: Trendline + Forecasted stock values
- 🧮 Formulas: Dynamic ranges, INDEX, AVERAGE, FORECAST.LINEAR

---

## 📌 Tools Used
- **Google Sheets** for data manipulation and dashboard
- **Yahoo Finance** for real-time stock data

---

## 🗓️ Project Date
- Created: 03/06/2025
- Author: Mohamed asim

---

## 🧠 Key Learnings
- Learned how to clean and format raw financial data
- Built statistical models using built-in spreadsheet functions
- Developed forecasting logic and interpreted stock trends
- Created a visual dashboard for presentation or portfolio

--

