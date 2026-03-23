# 🏦 Bank Fraud Detection using Machine Learning

## 📌 Project Description

This Bachelor's Thesis (TFG) focuses on developing a fraud detection system for banking transactions using Machine Learning techniques.

The problem is approached as a highly imbalanced binary classification task, applying advanced preprocessing, modeling, and interpretability techniques.

---

## 🎯 Objectives

* Analyze and understand fraudulent transaction behavior.
* Perform a complete Exploratory Data Analysis (EDA).
* Handle class imbalance using techniques such as SMOTE.
* Build robust predictive models.
* Implement a **stacking model** to improve performance.
* Apply **clustering techniques** to uncover hidden patterns.
* Interpret models using tools like LIME.

---

## 🧰 Libraries Used

### 📊 Data Analysis & Manipulation

* **pandas** → Data manipulation and preprocessing.
* **numpy** → Numerical operations.

### 📈 Visualization

* **matplotlib** → Basic plotting.
* **seaborn** → Advanced statistical visualization.
* **missingno** → Missing data visualization.

### 🔍 Exploratory Data Analysis (EDA)

* **ydata-profiling** → Automated data reports.
* **scipy** → Advanced statistics.

### 🤖 Machine Learning

* **scikit-learn** → Models, metrics, and pipelines.
* **xgboost** → High-performance boosting model.
* **lightgbm** → Efficient for large-scale data.
* **catboost** → Handles categorical features effectively.

### ⚖️ Imbalanced Data Handling

* **imbalanced-learn** → SMOTE and other resampling techniques.

### 🔍 Clustering

* **scikit-learn** → KMeans, DBSCAN, etc.
* **yellowbrick** → Visualization tools for clustering.

### 🧠 Model Interpretability

* **lime** → Local explanations for model predictions.

### 🛠️ Utilities

* **joblib** → Model saving/loading.
* **tqdm** → Progress bars.
* **scikit-plot** → Visual evaluation metrics.

---

## ⚙️ Methodology

1. **Data loading and cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Preprocessing**

   * Scaling
   * Encoding
4. **Handling imbalance (SMOTE)**
5. **Training base models**
6. **Stacking model construction**
7. **Clustering for additional insights**
8. **Model evaluation**
9. **Interpretability with LIME**

---

## 📊 Evaluation Metrics

Due to class imbalance, focus is placed on:

* Precision
* Recall
* F1-score
* ROC-AUC

---

## ⚠️ Project Challenges

* Severe class imbalance.
* Risk of overfitting.
* Interpretability of complex models.
* Proper metric selection.

---

## 🚀 Expected Outcomes

* A robust fraud detection model with high predictive performance.
* Discovery of meaningful transaction patterns.
* Explainable AI insights into model decisions.

---

## 📁 Project Structure

```
├── data/
├── src/
├── models/
├── reports/
├── requirements.txt
├── README_en.md
└── README.md
```

---

## 👨‍💻 Author

Developed as part of a Bachelor's Thesis in Data Science.

