<<<<<<< HEAD
# 🛒 Retail Consumer Behavior Forecasting using Deep Learning

## 📌 Project Overview

This project focuses on forecasting retail revenue using Deep Learning models applied to time-series data from the Online Retail dataset.

The objective is to predict future sales behavior and compare the performance of several recurrent neural network architectures.

The project also includes an interactive Streamlit dashboard for data exploration, model comparison, and future revenue forecasting.

---

## 🎯 Objectives

* Analyze retail consumer purchasing behavior.
* Forecast future daily revenue.
* Compare different Deep Learning architectures.
* Reduce overfitting using advanced regularization techniques.
* Build an interactive AI-powered dashboard.

---

## 📊 Dataset

Dataset: Online Retail Dataset

The dataset contains transactional records including:

* Invoice Number
* Product Description
* Quantity
* Unit Price
* Customer ID
* Country
* Invoice Date

Revenue is computed as:

Revenue = Quantity × UnitPrice

Data cleaning steps:

* Remove missing values.
* Remove negative quantities.
* Remove invalid prices.
* Convert dates to datetime format.
* Aggregate transactions into daily revenue.

---

## 🧠 Deep Learning Models

The following architectures were implemented:

### 1. LSTM

Long Short-Term Memory network for sequential forecasting.

### 2. GRU

Gated Recurrent Unit network with fewer parameters and faster training.

### 3. Bi-LSTM

Bidirectional LSTM capable of learning temporal dependencies in both directions.

### 4. Bi-GRU

Bidirectional GRU architecture combining efficiency and bidirectional learning.

---

## 🛡️ Overfitting Prevention

Several techniques were used to improve generalization:

* Dropout (30%)
* Batch Normalization
* L2 Regularization
* Early Stopping
* Reduce Learning Rate on Plateau

---

## 📈 Evaluation Metrics

Models are evaluated using:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)

The best-performing model is automatically identified based on prediction performance.

---

## 📊 Dashboard Features

### 🏠 Dashboard

* Revenue KPIs
* Orders statistics
* Customer statistics
* Product statistics

### 📊 Sales Analysis

* Daily revenue evolution
* Revenue distribution
* Descriptive statistics

### 🌍 Top Countries

* Revenue by country

### 🛍️ Top Products

* Best-selling products

### 🤖 Model Comparison

* LSTM vs GRU vs Bi-LSTM vs Bi-GRU
* MAE, RMSE, MAPE comparison

### 📈 Learning Curves

* Training Loss
* Validation Loss
* Overfitting detection

### 🔮 Future Forecasting

* Revenue prediction up to 90 days
* Multi-model comparison

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Sarah-lechgar/Retail-Consumer-Behavior-Forecasting.git
cd Retail-Consumer-Behavior-Forecasting
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 🧰 Technologies Used

* Python
* TensorFlow / Keras
* Streamlit
* Pandas
* NumPy
* Scikit-Learn
* Plotly
* Matplotlib

## 🎥 Demo Video

[▶ Watch Demo Video](https://drive.google.com/file/d/1QEHm98fiFdSd81QceALa37SRzuN2L8Ft/view?usp=sharing)


## 👩‍💻 Authors

- Sarah Lechgar
- Nisrine El Machkouri

Artificial Intelligence & Computer Science Students

Interests:
- Deep Learning
- Data Science
- Predictive Analytics
=======
# Retail-Consumer-Behavior-Forecasting
Deep Learning project for retail revenue forecasting using LSTM, GRU, Bi-LSTM and Bi-GRU models.
>>>>>>> e57b32be72f33c5c3db998a7957538155571d406
