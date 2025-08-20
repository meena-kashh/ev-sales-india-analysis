# ev-sales-india-analysis
Analysis &amp; forecasting of Electric Vehicle (EV) sales by Indian states using Python (Pandas, NumPy, Matplotlib, scikit-learn).
# Electric Vehicle Sales by State in India ⚡🇮🇳

This repository analyzes and visualizes **EV sales across Indian states**.  
It covers data cleaning, EDA, trend analysis, forecasting baselines, and state-wise insights.

## 📦 Dataset (columns)
- `Year` — sales year (e.g., 2021)
- `Month_Name` — full month name (e.g., January)
- `Date` — transaction/reporting date (YYYY-MM-DD)
- `State` — Indian state/UT
- `Category` *(optional)* — 2W/3W/4W/Bus/LCV/other
- `Units` — number of EVs sold/registered
- `Source` *(optional)* — data provenance note

> Update this section if your schema differs.

## 🔍 Objectives
- Clean & standardize state names and dates
- Monthly/annual growth, CAGR, and seasonality
- Top/bottom states by adoption
- Per-capita/normalised metrics *(if population data added)*
- Baseline forecasting (naive, moving average, simple ML)

## 🗂 Repo Structure
