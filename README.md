# AAPL Stock Analysis & S&P 500 Comparison

This project analyzes historical stock data for Apple Inc. (AAPL) and compares it with the S&P 500 index. It fetches data from Yahoo Finance, computes key metrics, visualizes trends interactively, and outputs CSVs ready for dashboards or further analysis.

---

## **Project Features**
- Fetch historical stock prices and compute **daily returns**.
- Fetch **company information** (Sector, Market Cap, PE Ratio) safely.
- Calculate **moving averages (MA)** and **volatility** for trend analysis.
- Compute **cumulative returns** to track growth over time.
- Compare stock performance against **S&P 500**.
- Generate **interactive visualizations** using Plotly.
- Export CSV files ready for dashboards:
  - `dashboard_ready_stock_data.csv`
  - `AAPL_vs_SP500_analysis.csv`

---

## **Tools & Libraries**
- **Python 3.x**
- pandas, numpy
- yfinance
- matplotlib, seaborn
- plotly

---

## **Usage Instructions**
1. Open `Stock_Analysis.ipynb` in **Google Colab** or locally.
2. Run the notebook step by step.
3. Enter **stock tickers** when prompted (default: AAPL).
4. Notebook will generate **metrics, visualizations, and CSV files** automatically.
5. Optional: CSVs can later be used to create a **Streamlit dashboard**.

---

## **CSV Output Notes**
- The notebook generates CSV files automatically.
- Users can run the notebook to regenerate updated CSVs anytime.
- These files can be used for building dashboards or further analysis.

---

## **Project Usage**
- Ideal for **stock analysis, data science learning, or finance projects**.
- Can be extended to multiple tickers or other indices.
- Streamlit dashboard integration can be added later for **interactive web visualization**.

---

## **Repository Contents**
