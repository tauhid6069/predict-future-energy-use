# Household Energy Forecasting – Machine Learning & Time Series

This repository contains two projects focused on **predicting household energy consumption** using both **traditional machine learning** and **time series forecasting** techniques. The goal is to explore different approaches for understanding and predicting how energy usage evolves over time.

---

## 📌 Projects Included

### 1️⃣ Predict Future Energy Use in a Household
Applies **regression models** to predict household energy consumption based on household characteristics and historical features.

**Highlights:**
- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Machine learning models (Linear Regression, Decision Tree, Random Forest, Gradient Boosting, Neural Networks)  
- Evaluation using MAE, MSE, RMSE, and R² Score  

Notebook: `notebooks/predict-future-energy-use-in-a-household.ipynb`

---

### 2️⃣ Time Series Forecasting of Energy Use
Applies **time series forecasting** to predict household energy consumption over time using both statistical and deep learning approaches.

**Highlights:**
- Time-series decomposition into trend/seasonality/residuals  
- Stationarity testing and differencing  
- Forecasting with ARIMA/SARIMA and Exponential Smoothing  
- Deep learning models (LSTMs with TensorFlow/Keras)  
- Evaluation using MAE, RMSE, and MAPE  

Notebook: `notebooks/time_series_forecasting.ipynb`

---

## 📂 Repository Structure
```
.
├── notebooks/
│   ├── predict-future-energy-use-in-a-household.ipynb
│   ├── time_series_forecasting.ipynb
├── requirements.txt                   # Dependencies for regression notebook
├── requirements_time_series.txt       # Dependencies for time series notebook
├── README.md                          # Documentation
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/tauhid6069/predict-future-energy-use.git
cd predict-future-energy-use
```

### 2️⃣ Install dependencies
For regression-based energy prediction:
```bash
pip install -r requirements.txt
```

For time series forecasting:
```bash
pip install -r requirements_time_series.txt
```

### 3️⃣ Run the notebooks
```bash
jupyter notebook notebooks/
```

---

## 📊 Models Covered
- **Machine Learning Models**: Linear Regression, Decision Tree, Random Forest, Gradient Boosting  
- **Statistical Models**: ARIMA, SARIMA, Exponential Smoothing  
- **Deep Learning Models**: LSTMs (TensorFlow/Keras)  

---

## 📈 Evaluation Metrics
- **Regression Models**: MAE, MSE, RMSE, R²  
- **Time Series Models**: MAE, RMSE, MAPE  

---

## 📝 Author
- **Md Tauhidul Islam**  
  [LinkedIn](www.linkedin.com/in/tauhidul-islam) 

