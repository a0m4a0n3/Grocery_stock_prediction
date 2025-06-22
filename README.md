# 🛒 AI Driven Grocery Stock Prediction

A machine learning-based web app developed to **predict hourly grocery stock levels**, enhance inventory decisions, and reduce stock-related risks. This project uses **Python**, **Streamlit**, and **Random Forest** to provide real-time predictions based on historical sales and sensor data.

---

## 🚀 Features

- 📉 **Stock Prediction Model**: Forecasts hourly grocery stock levels using a Random Forest Regressor.
- 🧼 **Data Preprocessing**: Handles missing values, merges multiple data sources, and performs feature engineering.
- 📊 **Exploratory Data Analysis**: Identifies trends and patterns to support model training and decision-making.
- 🌐 **Streamlit Web Interface**: Interactive UI for entering product details and getting stock level predictions.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas, NumPy**
- **Scikit-learn**
- **Streamlit**
- **Matplotlib/Seaborn (EDA)**

---

## 📁 File Structure

```
AI-Grocery-Stock-Prediction/
│
├── LICENSE                         # License file
├── README.md                       # Project documentation
├── app.py                          # Streamlit application for stock prediction
├── merge.csv                       # Final merged dataset (if used for backup)
├── requirements.txt                # Python dependencies
├── sample_sales_data.csv           # Sales data sample
├── sensor_stock_levels.csv         # Hourly stock level sensor data
├── sensor_storage_temperature.csv  # Temperature readings from sensors
```

---

## 📦 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/AI-Grocery-Stock-Prediction.git
cd AI-Grocery-Stock-Prediction
```

### 2. Install the Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
streamlit run app.py
```

Then open your browser and go to:
```
http://localhost:8501
```

---

## 🔍 Model Overview

- Preprocessing involved handling nulls, merging sales and sensor data, and selecting important features.
- Tested multiple ML models (Linear Regression, Decision Tree, etc.).
- **Random Forest Regressor** was selected based on lower **Mean Absolute Error (MAE)** and better generalization.

