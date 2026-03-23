# 🏠 Housing Price Classification using Machine Learning (Task-4)

## 📌 Project Overview

This project focuses on solving a **classification problem** using machine learning techniques on the California Housing Dataset.

Instead of predicting exact house prices, the goal is to classify houses into:

- **Low Price (0)**
- **High Price (1)**

This project demonstrates core classification concepts such as Logistic Regression, Decision Tree, and evaluation metrics.

---

## 📊 Dataset

Dataset Used: **California Housing Dataset**

Features include:

- MedInc (Median Income)
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

### 🎯 Target Variable

A new column was created:
```
Price_Category = (Housing_Value > median).astype(int)
```


- 0 → Low Price  
- 1 → High Price  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🧠 Machine Learning Workflow

1. Data Loading  
2. Data Preprocessing  
3. Target Conversion (Classification)  
4. Train-Test Split  
5. Feature Scaling  
6. Model Training  
7. Model Evaluation  
8. Model Comparison  

---

## 📊 Class Distribution

The dataset is balanced:

- Class 0: ~10323 samples  
- Class 1: ~10317 samples  

No imbalance handling was required.

---

## 🤖 Models Implemented

### Logistic Regression
- Used as baseline model  
- Works well for linear relationships  

### Decision Tree Classifier
- Captures non-linear patterns  
- Tuned using max_depth  

---

## 📈 Model Performance

| Model | Accuracy |
|------|---------|
| Logistic Regression | ~80% |
| Decision Tree (depth=5) | 79% |
| **Decision Tree (depth=10)** | **86%** |

### Best Model: Decision Tree (max_depth=10)

- Precision: 0.86  
- Recall: 0.85–0.86  
- F1-score: 0.86  

---

## 📊 Evaluation Metrics

- **Accuracy** → Overall correctness  
- **Precision** → Correct positive predictions  
- **Recall** → Ability to detect positives  
- **F1-score** → Balance of precision & recall  

---

## 📉 Visualizations

- Confusion Matrix  
- ROC Curve  
- Classification Report  

---

## 🚀 Key Learnings

- Difference between regression and classification  
- Importance of precision, recall, and F1-score  
- Handling balanced datasets  
- Model tuning improves performance  
- Decision Tree captures complex patterns better than Logistic Regression  

---

## 📂 Project Structure
```
Task-4/
│
├── notebook.ipynb
├── README.md
├── California_housing.csv
```
