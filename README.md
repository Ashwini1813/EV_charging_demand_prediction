# EV_charging_demand_prediction
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red?style=for-the-badge&logo=streamlit)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)

# ⚡ EV Adoption Forecaster — Washington State

## 🌐 Live Demo
👉 [Launch App](https://ev-charging-demand-prediction-26.streamlit.app/)

---

## 📌 Overview
EV Adoption Forecaster is a Machine Learning-powered web application that predicts Electric Vehicle (EV) adoption trends across counties in Washington State.

Using historical EV population data and a Random Forest Regression model, the application forecasts EV growth for the next 36 months, helping users explore future adoption patterns and compare trends between counties.

---

## 🎯 Features
- ✅ Forecast EV adoption for the next 3 years (36 months)
- ✅ Compare forecasts across up to 3 counties
- ✅ Visualize cumulative EV growth trends
- ✅ Historical vs Forecast comparison charts
- ✅ Automatic EV growth percentage calculation
- ✅ Interactive and user-friendly Streamlit interface

---

## 🛠️ Tech Stack
| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Machine Learning | Random Forest Regressor |
| Data Processing | Pandas, NumPy |
| ML Framework | Scikit-learn |
| Visualization | Matplotlib |
| Model Serialization | Joblib |
| Deployment | Streamlit Cloud |

---

## 📊 Model Performance
| Metric | Score |
|--------|-------|
| MAE | 0.01 |
| RMSE | 0.06 |
| R² Score | 0.97 |

The model demonstrates excellent predictive performance on the prepared dataset.

---

## 🔧 Feature Engineering
To improve forecasting accuracy, the following engineered features were used:
- Lag Features (1, 2, and 3 months)
- Rolling Mean (3-month window)
- Monthly Percentage Change
- Quarterly Percentage Change
- Cumulative EV Growth Trend
- County Encoding
- Time-based Forecasting Features

**Total engineered features: 9**

---

## 📂 Dataset
- **Source:** Washington State EV Population Data
- **Target Variable:** Total Electric Vehicles per County per Month
- **Data Granularity:** County-wise monthly EV adoption statistics

---

## 📈 Forecasting Workflow
1. Data Collection & Cleaning
2. Feature Engineering
3. Model Training using Random Forest Regressor
4. Multi-step Forecast Generation
5. Interactive Visualization with Streamlit
6. Deployment on Streamlit Cloud

---

## 🚀 Run Locally
```bash
# Clone the repository
git clone https://github.com/Ashwini1813/EV_charging_demand_prediction.git

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

---

## 🎓 Learning Outcomes
Through this project, I gained hands-on experience in:
- Time Series Forecasting
- Feature Engineering
- Machine Learning Model Development
- Model Deployment
- Interactive Dashboard Creation
- End-to-End Data Science Workflow

---

## 👩‍💻 Developer
**Ashwini Parmar**
