# Predictive-Analytics-Lab-Exam-2.-


## 📌 Overview

This project demonstrates a complete **classification workflow** using **Logistic Regression** on a binary classification dataset.
It covers all required tasks: **EDA, model building, decision boundary visualization, and evaluation**.

---

## 📂 Dataset

* File: `Lab_Exam_binary_classification_dataset.csv`
* Features:

  * `Feature1`
  * `Feature2`
* Target:

  * `Target` (Yes / No → converted to binary)

---

## ⚙️ Workflow

### 1. Data Loading & Cleaning

* Removed missing values
* Handled outliers (`Feature1 < 100`)
* Converted categorical target into binary (Yes → 1, No → 0)

---

### 2. Exploratory Data Analysis (EDA)

* Scatter plot to visualize class distribution
* Correlation heatmap to understand feature relationships

---

### 3. Model Building

* Used **Logistic Regression**
* Applied **StandardScaler** using Pipeline
* Used **stratified train-test split** for balanced training

---

### 4. Decision Boundary

* Generated mesh grid
* Plotted decision regions
* Visualized classification separation

---

### 5. Model Evaluation

* Accuracy score
* Classification report (Precision, Recall, F1-score)
* Confusion matrix visualization

---

## 📈 Results

* Model performs well on binary classification
* Clear separation observed in decision boundary
* Balanced performance across classes

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

```bash
python your_script_name.py
```

---

## 📌 Key Concepts

* Logistic Regression
* Decision Boundary
* Feature Scaling
* Classification Metrics
* Pipeline in ML



---

## ⭐ Notes

This project is designed for **academic purposes (Lab Exam)** and demonstrates a **complete end-to-end classification pipeline**.
