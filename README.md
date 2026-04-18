# 🚚 E-Commerce Delivery Prediction System  
### 📊 End-to-End Machine Learning Project

---

> 💡 A complete machine learning pipeline that analyzes and predicts delivery outcomes in e-commerce logistics using real-world data.

---

## 🌟 Overview

This project builds a full **data science and machine learning workflow** to predict delivery outcomes for e-commerce orders.

The system classifies each order into:

- ✅ Delivered  
- ⏳ Delayed  
- 🔄 Returned  

The pipeline includes everything from **data exploration → feature engineering → modeling → evaluation → insights**, making it a complete real-world ML project.

---

## 🎯 Problem Statement

In e-commerce, delivery performance directly affects:

- Customer satisfaction  
- Operational efficiency  
- Return rates  
- Business profitability  

This project aims to **predict delivery issues before they happen**, helping businesses optimize logistics and decision-making.

---

## 🧠 Objectives

- Understand patterns in delivery performance  
- Identify key factors behind delays and returns  
- Engineer new predictive features  
- Train and compare multiple ML models  
- Select the best model using **F1-score**  
- Generate insights from data  

---

## 🛠️ Tech Stack

- 🐍 Python  
- 📊 Pandas  
- 🔢 NumPy  
- 📈 Matplotlib  
- 🤖 Scikit-learn  

---

## 📂 Project Structure

```
E-commerce-Delivery-Prediction/
│
├── data/                # Dataset
├── figures/             # All generated visualizations
├── outputs/             # Processed data and results
│
├── main.py              # Full ML pipeline
└── README.md
```

---

## 📊 Dataset

- 📦 ~50,000 orders  
- 🧾 Multiple features (shipping, cost, region, category, dates)  
- 🎯 Target: `Delivery_Status`  

Classes:
- Delivered  
- Delayed  
- Returned  

---

## 🔍 Exploratory Data Analysis (EDA)

The project performs deep analysis to understand the data:

- 📊 Distribution of delivery outcomes  
- 🚚 Impact of shipping mode  
- 🌍 Differences across regions  
- 📦 Product category trends  
- ⏱️ Delivery time patterns  
- 💰 Shipping cost distribution  
- 📅 Time trends across months  
- 🔥 Feature correlations  
- 📉 Outlier detection  

---

## ⚙️ Feature Engineering

New features were created to improve prediction:

- ⏳ `processing_time` → time between order and shipment  
- 📅 `order_month`, `order_dayofweek`, `quarter`  
- 🚀 shipping indicators (`is_express`, `is_same_day`)  
- 💸 `cost_per_day` → efficiency metric  
- 🌐 one-hot encoded categorical features  

---

## 🤖 Machine Learning Models

The following models were trained:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Gradient Boosting  

---

## 📈 Model Evaluation

Models are evaluated using:

- Accuracy  
- Precision  
- Recall  
- ⭐ F1 Score (main metric)  

✔️ Best model is automatically selected.

---

## 📊 Visualizations (VERY IMPORTANT)

This project generates **16 professional figures** stored in the `figures/` folder.

### 📌 What each figure represents:

**Figure 01 — Target Distribution**  
Shows how many orders are Delivered, Delayed, or Returned.

**Figure 02 — Shipping Mode Analysis**  
Compares shipping types (Standard, Express, Same Day) and their delivery success rates.

**Figure 03 — Regional Analysis**  
Shows how delivery performance varies across customer regions.

**Figure 04 — Product Category Analysis**  
Analyzes which product types have more delays or returns.

**Figure 05 — Delivery Days Analysis**  
Shows distribution and average delivery times per status.

**Figure 06 — Shipping Cost Analysis**  
Examines how cost relates to delivery outcome.

**Figure 07 — Temporal Trends**  
Shows how deliveries change over time (monthly trends).

**Figure 08 — Scatter + Outliers**  
Visualizes relationship between cost and delivery days + detects anomalies.

**Figure 09 — Correlation Matrix**  
Shows relationships between numerical features.

**Figure 10 — Engineered Features**  
Visualizes new features like processing time and cost efficiency.

**Figure 11 — Model Comparison**  
Compares all ML models across metrics.

**Figure 12 — Radar Chart**  
Shows model performance in a multi-metric visual way.

**Figure 13 — Confusion Matrices**  
Displays prediction accuracy for each model.

**Figure 14 — Feature Importance**  
Shows which features influence predictions the most.

**Figure 15 — Per-Class Metrics**  
Shows precision/recall/F1 for each class.

**Figure 16 — Final Dashboard**  
A summary combining key results and insights.

---

## 🧾 Outputs

### 📁 outputs/

- X_train.csv, X_test.csv  
- y_train.csv, y_test.csv  
- model_comparison.csv  
- predictions.csv  
- feature_importance.csv  

### 📁 figures/

- 16 generated PNG visualizations  

---

## 💡 Key Insights

- 🚚 Shipping mode strongly impacts delivery success  
- 🌍 Some regions experience more delays  
- 💰 Higher cost does not guarantee faster delivery  
- ⏱️ Processing time is a key predictor  
- 📦 Product category affects return probability  

---

## 🚀 How to Run

Install dependencies:

```
pip install pandas numpy matplotlib scikit-learn
```

Run the project:

```
python main.py
```

---

## 🏁 Final Result

✔️ Full ML pipeline implemented  
✔️ Multiple models compared  
✔️ Best model selected  
✔️ Professional visual analysis generated  

---

## 👩‍💻 Authors

Ola Gurthi & Viola Makishti  
🎓 UNYT — Machine Learning Project  

---

## ⭐ Final Note

This project demonstrates a complete real-world ML workflow:

📊 Data → ⚙️ Features → 🤖 Models → 📈 Insights  

---

⭐ If you like it:
- Star the repo  
- Add it to your portfolio  
- Improve and expand it 🚀
