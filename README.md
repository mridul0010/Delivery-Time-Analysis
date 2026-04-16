<div align="center">

# 📊 🚚 Delivery Time Analysis

**An end-to-end analytics project to understand what drives food delivery time and to present actionable insights through an interactive Streamlit dashboard.**

[![Streamlit App](https://img.shields.io/badge/Streamlit-Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://e-commerce-customer-churn-analysis-and-retention-strategy.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

</div>


## 📚 Table of Contents

- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Data Description](#-data-description)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

## 🔗 Live Dashboard

👉 https://delivery-time-analysis.streamlit.app/

## 📖 About the Project

This project analyzes delivery operations using exploratory data analysis and feature engineering, then presents findings in a Streamlit dashboard for business decision-making.

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

## 📁 Project Structure

```text
Delivery-Time-Analysis/
├── app.py
├── Data_Preprocessing.ipynb
├── EDA.ipynb
├── data/
├── requirements.txt
└── README.md
```

## 🚀 Getting Started

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the dashboard:
   ```bash
   streamlit run app.py
   ```

## 🗂️ Data Description

- `data/Delivery Dataset.csv`: Raw delivery dataset used in preprocessing.
- `data/Cleaned Delivery Dataset.csv`: Cleaned dataset consumed by the Streamlit app.

## 📸 Screenshots

Dashboard screenshots can be added here to showcase key tabs and insights.

## 🤝 Contributing

Contributions are welcome. Please open an issue first to discuss major changes before submitting a pull request.

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## 👤 Author

**Mridul Lata**  
LinkedIn: https://www.linkedin.com/in/mridullata
