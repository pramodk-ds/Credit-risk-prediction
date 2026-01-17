# 💳 Credit Risk Prediction – Bank GoodCredit

## 📌 Introduction
Financial institutions face risk in lending decisions.  
This project applies machine learning models to predict whether a client is a **good credit risk** or **bad credit risk**, helping banks minimize defaults.

---

## 📊 Dataset
- Features: Age, Job, Credit History, Loan Amount, Duration, Housing, Purpose, etc.  
- Target Variable: Credit Risk → Good / Bad

---

## 🚀 Approach
1. Data Preprocessing  
   - Missing value handling  
   - Encoding categorical features  
   - Feature scaling  

2. Exploratory Data Analysis (EDA)  
   - Distribution of credit risk across demographics  
   - Correlation heatmaps  

3. Model Building  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  

4. Model Evaluation  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix  

---

## 📈 Results
- XGBoost achieved the best predictive performance.  
- Important predictors: Credit history, duration, and loan amount.

---

## ✅ Conclusion
This model helps banks identify potential risky applicants, reducing default risk and improving lending strategies.

---

## ⚠️ Problems Faced
- Class imbalance between Good and Bad credit risks  
- Missing values in categorical features  
- Trade-off between recall and precision for loan approvals  

---

## ⚡ How to Run
```bash
pip install -r requirements.txt
jupyter notebook Credit_Risk_Prediction_GoodCredit.ipynb
```

---

## 👨‍💻 Author
**Pramod K**  
Data Science Enthusiast | Machine Learning | Deep Learning
