# Store-Sales-Time-Series-Forecasting
Time series forecasting of weekly retail store sales using Python and Holt-Winters Exponential Smoothing. Includes EDA, decomposition, and a 4-week forecast with business recommendations.
# 🛒 Store Sales Time Series Forecasting

**Tools:** Python · Pandas · Matplotlib · Statsmodels  
**Dataset:** [Kaggle — Store Sales Time Series Forecasting](https://www.kaggle.com/c/store-sales-time-series-forecasting)

---

## 📌 Business Problem

A retail chain needs to predict weekly sales for the next 4 weeks to optimize inventory ordering and staffing decisions. Inaccurate forecasts lead to either overstocking (wasted cost) or stockouts (lost revenue).

---

## 📊 Approach

| Step | Method |
|------|--------|
| Exploratory Data Analysis | Line plots, year-over-year comparison, monthly averages |
| Time Series Decomposition | Additive model — trend, seasonality, residual |
| Forecasting | Holt-Winters Exponential Smoothing |
| Evaluation | MAE, RMSE, MAPE |

---

## 🔑 Key Findings

- **Strong upward trend** — sales grew ~60% from 2020 to 2023
- **Yearly seasonality** — peak in weeks 48–52 (holiday season), dip in Q1
- **Model accuracy: MAPE ≈ 5%** — reliable enough for operational use

---

## 💼 Business Recommendations

- Start holiday inventory stocking **6 weeks before December**
- Run Q1 promotions to counter the seasonal sales dip
- Use forecast output to automate weekly purchase orders

---

## 📁 Files

| File | Description |
|------|-------------|
| `store_sales_forecasting.ipynb` | Full analysis notebook |
| `sales_eda.png` | EDA visualizations |
| `decomposition.png` | Trend/seasonality decomposition |
| `forecast.png` | 4-week forecast chart |

---

## 🚀 How to Run

```bash
git clone https://github.com/kamala-garayeva/store-sales-forecasting
cd store-sales-forecasting
pip install pandas numpy matplotlib statsmodels scikit-learn
jupyter notebook store_sales_forecasting.ipynb
```

---

*Part of my data analytics portfolio — [github.com/kamala-garayeva](https://github.com/kamala-garayeva)*
