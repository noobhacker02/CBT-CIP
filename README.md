# CBT-CIP

# 🧠 CipherByte Internship Projects – Talha Shaikh

Welcome to the collection of web-based machine learning & data analysis applications developed during my internship at **CipherByte Technologies**. Each task integrates practical ML concepts with user-friendly interfaces using **Gradio**.

---

# 🌸 Task 1: Iris Flower Classification - Gradio Web App

This project uses a simple ML model to classify iris flower species based on sepal and petal measurements from a user-uploaded Excel sheet.

## 🚀 Features
- 📁 **File Upload**: Accepts `Iris Flower.xlsx` with flower measurements.
- 🧠 **Model**: K-Nearest Neighbors (KNN) with `k=3`.
- 📊 **Output**:
  - ✅ Accuracy percentage
  - 📋 DataFrame showing actual vs. predicted labels

## 🛠️ Tech Stack
- `Python`
- `Gradio`
- `Pandas`
- `Scikit-learn`
- `Openpyxl`

## 🎯 Purpose
To demonstrate the integration of supervised ML with an interactive interface, enabling predictions without needing code.

---

# 📊 Task 2: Unemployment Analysis - Gradio Web App

An interactive data visualization tool to analyze India’s unemployment trends using real-world data.

## 🚀 Features
- 📁 Accepts two Excel files:
  - `Unemployment_Rate_upto_11_2020.xlsx`
  - `Unemployment in India.xlsx`
- 🔍 **Preprocessing**: Cleans and merges time-series data
- 📊 **Visualizations**:
  - 📉 Urban vs. Rural time series
  - 📦 Boxplot of state-wise unemployment
  - 🔥 Correlation heatmap
- 🧾 **Insights**:
  - Summary stats
  - Top 5 states with highest COVID-era unemployment

## 🛠️ Tech Stack
- `Python`
- `Gradio`
- `Pandas`
- `Seaborn` & `Matplotlib`
- `Pillow`
- `Openpyxl`

## 🎯 Purpose
Showcasing interactive data analytics with insightful visual reports for real-world decision-making.

---

# ⏳ Task 3: Time Series Forecasting - Gradio Web App

Built a forecasting app that predicts the next 12 months of travel and alcohol sales using SARIMAX models.

## 🔧 Features
- 📂 Accepts:
  - `Miles_Traveled.csv`
  - `Alcohol_Sales.csv`
- 🧠 Trains SARIMAX model per metric
- 📈 Forecasts for 12 future months
- 📊 Plots actual vs. predicted values
- 🧮 Evaluation:
  - **RMSE**
  - **MAE**

## 💡 How It Works
1. Parses time-series data with monthly frequency.
2. Splits train/test (last 12 months as test).
3. Forecasts and evaluates trends per series.

## 🛠️ Tech Stack
- `Python`
- `Pandas`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`
- `Statsmodels` (SARIMAX)
- `Gradio`

## 🎯 Purpose
Demonstrates time-series modeling and deployment in an accessible format.

---

# 📧 Task 4: Spam Email Detection - Gradio Web App

A machine learning app that detects whether an email is spam or ham based on textual input using Naive Bayes.

## 💡 Overview
Applies binary classification to email messages using natural language processing techniques.

## 🧠 Model Details
- 📘 **Dataset**: `Spam Email Detection.xlsx`
- 🧹 Preprocessing: Lowercase, remove URLs, punctuation, numbers
- 🧪 Vectorization: TF-IDF (bigrams + stopwords)
- 📊 Model: `Multinomial Naive Bayes` (`alpha=0.1`)

## 📈 Metrics
- 🔍 Accuracy: `~97%`
- 📑 Precision, Recall, F1-score
- 🧱 Confusion Matrix

## 🚀 Web Interface
- 🔤 Input: Free text email
- 📮 Output: “Spam” or “Ham”
- 🌐 Built with Gradio

## 🧪 Example

```plaintext
Input: "Congratulations! You've won a $1000 gift card. Click here to claim."
Output: Spam

Input: "Hi John, let’s reschedule our meeting for tomorrow."
Output: Ham
```

---

# 👨‍💻 Developed By
**Talha Shaikh**  
🔗 [LinkedIn](https://www.linkedin.com/in/talha-s-145729339/)  
📌 Internship Project Series – **#CipherByteTech**

---

> “Bringing machine learning to life with code, data, and interaction.”
```


