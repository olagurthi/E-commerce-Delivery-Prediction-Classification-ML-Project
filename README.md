# 📦 E-Commerce Delivery Prediction

A complete end-to-end machine learning project for predicting delivery outcomes in an e-commerce environment.  
The project combines **data analysis, feature engineering, and multiple classification models** to deliver reliable predictions and business insights.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange)
![pandas](https://img.shields.io/badge/pandas-1.3+-blue)
![NumPy](https://img.shields.io/badge/numpy-1.21+-lightgrey)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.5+-green)

---

## 📚 Table of Contents

- 📊 Dataset  
- 🧱 Project Structure  
- ⚙️ Installation  
- 🔄 Pipeline Overview  
- 🤖 Models Used  
- 📈 Results  
- 📊 Visual Outputs  
- 📐 Evaluation Metrics  
- 📂 Outputs  

---

## 📊 Dataset

The dataset contains **~50,000 e-commerce orders** with operational and customer-related features.

### 🎯 Target Variable
- `Delivery_Status`  
  - Delivered  
  - Delayed  
  - Returned  

### 📌 Key Features
- Shipping Cost 💸  
- Delivery Days ⏱️  
- Shipping Mode 🚚  
- Customer Region 🌍  
- Product Category 🛍️  
- Order / Ship / Delivery Dates 📅  

---

## 🧱 Project Structure

```
project/
│
├── data/
│   └── dataset.csv
│
├── figures/
│   └── (16 generated visualizations)
│
├── outputs/
│   ├── X_train.csv
│   ├── X_test.csv
│   ├── y_train.csv
│   ├── y_test.csv
│   ├── predictions.csv
│   └── model_comparison.csv
│
├── main.py
└── README.md
```

---

## ⚙️ Installation

Install dependencies:

```
pip install pandas numpy matplotlib scikit-learn
```

Run the project:

```
python main.py
```

---

## 🔄 Pipeline Overview

This project follows a full machine learning workflow:

### 1️⃣ Data Exploration (EDA)
- Target distribution 📊  
- Shipping mode analysis 🚚  
- Regional & category insights 🌍  
- Delivery time and cost distributions ⏱️💸  
- Temporal trends 📅  
- Correlation analysis 🔗  
- Outlier detection ⚠️  

---

### 2️⃣ Feature Engineering
- Processing time (Order → Shipment) ⏳  
- Time-based features (month, weekday, quarter) 📅  
- Shipping mode indicators 🚚  
- Cost efficiency (cost per day) 💰  
- Categorical encoding 🔢  

---

### 3️⃣ Model Training

The following models are implemented:

- Logistic Regression  
- Decision Tree 🌳  
- Random Forest 🌲  
- Support Vector Machine  
- Gradient Boosting ⚡  

---

### 4️⃣ Evaluation

Models are compared using:

- Accuracy  
- Precision (macro)  
- Recall (macro)  
- F1 Score (macro)  

---

## 🤖 Models Used

Each model is trained and evaluated under the same conditions to ensure fair comparison.

The best model is selected based on **F1 Score**, which balances performance across all classes.

---

## 📈 Results

- Multiple models are trained and benchmarked  
- The best-performing model is automatically selected  
- Results are exported and visualized  

---

## 📊 Visual Outputs

The project generates **16 high-quality figures** stored in the `figures/` folder:

### 📌 Data Analysis
- Target distribution  
- Shipping mode vs delivery outcome  
- Regional performance  
- Product category impact  

### 📌 Feature Insights
- Delivery time distributions  
- Shipping cost analysis  
- Cost efficiency (cost/day)  
- Temporal trends  

### 📌 Advanced Analysis
- Scatter plots (feature relationships)  
- Outlier detection  
- Correlation heatmap  

### 📌 Model Evaluation
- Model comparison chart  
- Radar chart  
- Confusion matrices  
- Feature importance  
- Per-class metrics  
- Final dashboard summary  

👉 These visuals help understand both **data behavior** and **model performance**

---

## 📐 Evaluation Metrics

The main evaluation metric:

### ⭐ F1 Score (Macro Average)

Why?
- Handles class imbalance  
- Balances precision & recall  
- Ensures fair performance across all delivery outcomes  

---

## 📂 Outputs

### 📁 Data Splits
- X_train.csv  
- X_test.csv  
- y_train.csv  
- y_test.csv  

### 📁 Model Outputs
- model_comparison.csv  
- predictions.csv  

### 📁 Visualizations
- figures/ (16 plots)

---

## 🧠 Conclusion

This project demonstrates a **complete machine learning pipeline** applied to a real-world logistics problem.

Key takeaways:
- Feature engineering significantly improves performance  
- Data visualization is critical for understanding patterns  
- Model comparison ensures optimal selection  
- F1 Score provides reliable evaluation for multi-class problems  

---

## 👩‍💻 Authors

**Ola Gurthi**  
**Viola Makishti**  

Machine Learning Project — UNYT
