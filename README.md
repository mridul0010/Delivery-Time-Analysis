# 🚚 Delivery Time Analysis

An end-to-end analytics project to understand what drives food delivery time and to present actionable insights through an interactive Streamlit dashboard.

## 🔗 Live Dashboard

👉 https://delivery-time-analysis.streamlit.app/

## 🎯 Project Objective

Identify the most important operational factors affecting delivery performance and support data-driven decisions for faster and more reliable deliveries.

## 📌 Key Features

- Interactive Streamlit dashboard with business-focused visual insights
- End-to-end preprocessing and feature engineering workflow
- Analysis across traffic, distance, time of day, weather, and rider factors
- Filterable data exploration with CSV download support

## 🧠 Key Insights

- **Traffic density** is the strongest contributor to delivery delays
- **Time of day** amplifies traffic impact, especially during evening hours
- **Multiple deliveries per rider** increase delivery time non-linearly
- **Rider rating and efficiency** matter more than raw speed alone

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- Statsmodels

## 📂 Repository Structure

```text
Delivery-Time-Analysis/
├── app.py
├── Data_Preprocessing.ipynb
├── EDA.ipynb
├── data/
├── requirements.txt
└── README.md
```

## ⚙️ Run Locally

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the dashboard:
   ```bash
   streamlit run app.py
   ```

## 👤 Author

**Mridul Lata**  
LinkedIn: https://www.linkedin.com/in/mridullata
