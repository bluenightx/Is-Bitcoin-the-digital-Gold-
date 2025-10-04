# ₿ Is Bitcoin the digital gold? — README Summary

> This README documents the full pipeline used to analyze bitcoin, gold and sp500.  All code, logic, and visualizations were crafted for clarity, reproducibility, and usability.

---

## 📊 Project Pipeline

1. **Data Collection**
   - Collected data using the yfinance and pytrends libraries, as well as the News API.
   - Downloaded CSV files from official sources for additional datasets.

2. **Data Cleaning**
   - Standardized, filtered, and converted data to monthly frequency using Python.
   - Create new variables and merge multiple datasets into a single dataset.
   

3. **Exploratory Data Analysis (EDA)**
   - Cumulative Returns
   - Volatility Analysis
   - Asset Correlation
   - Performance During Market Shocks
   - Trading Volume

4. **Dashboard Development (Tableau)**
   - Created an interactive dashboard to explore:
     - Compounded returns by asset and by year
     - Compounded asset returns against GDP and against the CFNAI
     - Linear correlations between Bitcoin & S&P 500, and Gold & S&P 500
     - 12 month rolling volatility


---

## 🛠️ Tools & Technologies

- **Python** – Data cleaning, analysis (Pandas, NumPy)
- **yfinance** – Data collection
- **pytrends** – Data collection
- **News API** – Data collection
- **Tableau** – Dashboard creation and data visualization
---


## 📂 Project Structure

├── data/
│   ├──GDP.csv
│   └──US_ECO.csv
├── notebooks/
│   ├──data wrangling
│   ├──EDA_multivariate.ipynb
│   ├─EDA_univariate.ipynb
│   └──google trends and news
├── outputs/
│   ├──analysis.csv
│   └──returns_long_format
├── visualization/
│   └──tableau
└── README.md

---

## 🔗 Sources & References

- [GDP US data](https://fred.stlouisfed.org/series/GDP )
- [US Economic Indicators data](https://www.chicagofed.org/research/data/cfnai/current-data)
- [Gold data](https://www.gold.org/)
- [📊 Final Presentation ](https://www.canva.com/design/DAGzysq-lm4/KefSm9MJj-55x8RIL7Qu9Q/edit?utm_content=DAGzysq-lm4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton): Overall project and key findings.

---
## 👨‍💻 Author

**Anaísa Sena**  
*Data Analytics Final Project*  
GitHub: [AnaisaSena](https://github.com/bluenightx)

---

## 📜 License

This project is intended for educational and demonstration purposes. You are free to use and adapt it with credit.