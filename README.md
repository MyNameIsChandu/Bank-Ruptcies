# Bank-Ruptcies
# 🏦 Predicting Company Bankruptcies

## 📌 Overview
This project aims to predict whether a company will go bankrupt based on financial data using machine learning techniques. The model helps identify high-risk companies and supports better financial decision-making.

---

## 🎯 Problem Statement
Bankruptcy prediction is important in financial risk management. The goal is to build a classification model that can accurately identify companies likely to go bankrupt, while handling class imbalance in the dataset.

---

## 📊 Dataset
- Financial dataset containing company-related features  
- Target Variable:
  - 1 → Bankrupt  
  - 0 → Non-Bankrupt  

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Checked for missing values  
- Split data into training and testing sets  
- Applied feature scaling using StandardScaler  

### 2. Handling Imbalanced Data
- Used SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset  

### 3. Model Building
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

### 4. Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Cross-validation  

---

## 🚀 Results
- Random Forest performed best among the models  
- Improved performance after applying SMOTE  
- Achieved good recall for bankrupt class  

---

## 📈 Key Insights
- Class imbalance significantly affects model performance  
- SMOTE improves detection of minority class  
- Tree-based models perform better than linear models  

---

## 💡 Business Recommendations
- Use the model as an early warning system  
- Focus on recall to avoid missing risky companies  
- Continuously update the model with new data  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Matplotlib, Seaborn  

---
