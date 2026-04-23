# Apple Inc. Financial Performance Analysis (2020–2025)
ACC102 Accounting Project

## 1. Project Overview
This project analyzes Apple Inc.’s financial performance from 2020 to 2025 using Python and WRDS Compustat data. It focuses on revenue trends, profitability ratios, and year-over-year growth to evaluate operational efficiency and shareholder return.

## 2. Data Source
- Database: WRDS Compustat (funda)
- Company: Apple Inc. (Ticker: AAPL)
- Period: 2020 – 2025
- Cleaned Data File: cleaned_data.csv
- Variables: date, revenue, net_income, cogs, equity

## 3. Python Methods Used
- pandas: Data loading, cleaning, calculation
- numpy: Numerical operations
- matplotlib: Visualization
- wrds: WRDS data extraction

## 4. Analysis Framework
1. Revenue & Net Income Trend Analysis
2. Profitability Ratios:
   - Gross Profit Margin
   - Net Profit Margin
   - Return on Equity (ROE)
3. Year-over-Year (YoY) Growth Rate Calculation

## 5. Key Findings
- Revenue grew rapidly from 2020 to 2022, stabilized in 2023–2024, and rebounded in 2025.
- Gross margin consistently improved over the period, showing strong cost efficiency.
- ROE remained at a high level, reflecting strong capital efficiency.
- Net income growth followed revenue trends with high stability.

## 6. Results & Visualizations
- Revenue and Net Income Trend (2020–2025)
- Gross Margin, Net Margin, ROE Trend
- Year-over-Year Growth Comparison

## 7. How to Run
1. Clone this repository
2. Install required packages:
   pip install pandas numpy matplotlib wrds
3. Open wrds_financial_data.ipynb
4. Run all cells to reproduce analysis and charts

## 8. Limitations & Future Improvements
1.Limitations
The analysis is based solely on annual financial data, which fails to capture short-term quarterly fluctuations, seasonal business cycles, and timely market responses.
The calculation of financial ratios (e.g., ROE) uses simplified total equity without adjusting for average equity, which may reduce the accuracy of profitability evaluation.
The study focuses only on Apple Inc. without comparing it with industry peers, lacking a benchmark to evaluate relative performance.
2.Future Improvements
Incorporate quarterly financial data to track finer-grained trends and short-term operational changes.
Refine ratio calculations with more precise accounting metrics (e.g., average equity for ROE) to improve analytical accuracy.
Add peer company comparison (e.g., Samsung, Microsoft) to provide industry-relative insights into competitive advantages.
Integrate macroeconomic indicators (interest rates, inflation) to explore external factors influencing financial performance.

## 8. Links
- GitHub Repository: This page
- Demo Video: To be added[wrds.financial.data.1.ipynb](https://github.com/user-attachments/files/26884949/wrds.financial.data.1.ipynb)

