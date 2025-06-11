# 📊 Customer Churn Prediction – Task 2 (Future Interns)

This project predicts customer churn using a real-world telecom dataset. It includes complete data preprocessing, feature engineering, visualization, class balancing using SMOTE, and evaluation of three powerful models: **Logistic Regression**, **Random Forest**, and **XGBoost**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedTaha-751/FUTURE_ML_2/blob/main/Churn_Prediction_Task2.ipynb)

---

## 🚀 Features
- Cleaned and prepared dataset from real-world telecom churn data  
- Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- Feature engineering (e.g., tenure grouping, total services count)  
- One-hot encoding & label encoding  
- Class imbalance handled using **SMOTE**  
- Trained and evaluated:
  - Logistic Regression  
  - Random Forest Classifier  
  - XGBoost Classifier  
- AUC-ROC curve comparison  
- XGBoost feature importance visualization  

---

## 🧰 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- imbalanced-learn (SMOTE)  
- Matplotlib & Seaborn  

---

## 📈 Model Evaluation
Each model was evaluated using:
- Classification report (Precision, Recall, F1-score)  
- ROC-AUC score  
- ROC Curve  

---

## 📎 How to Use

1. Open the notebook in Google Colab:  
   [Click here to run in Colab](https://colab.research.google.com/github/MohammedTaha-751/FUTURE_ML_2/blob/main/Churn_Prediction_Task2.ipynb)

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook cells step by step to:
   - Load and clean the dataset  
   - Explore and visualize key patterns  
   - Train models and evaluate performance  

---

## 📂 Dataset Source
The dataset used in this project is from the [Telco Customer Churn Dataset](https://github.com/MohElaghory/Telco-Customer-Churn), which contains customer demographics, account information, and service usage patterns.

---

## 🔍 Key Insights
- **Long-term contracts** significantly reduce churn likelihood.  
- Customers with more add-on services (like Tech Support, Online Backup) are **less likely** to churn.  
- **MonthlyCharges** and **tenure** have a strong correlation with churn behavior.

---

## 🎯 Internship Context
This project is part of **Task 2 – Churn Prediction System** in the **Future Interns Machine Learning Internship**. The internship emphasizes hands-on learning in machine learning through self-paced projects and real-world problem-solving.

---

## ✍️ Author
**Mohammed Taha Ahamed**  
B.E. Information Science & Engineering  
HKBK College of Engineering  
2022 Batch

---

## 📄 License
This project is open-source and free to use for academic and learning purposes.

---

## 🙌 Acknowledgements
Thanks to:
- Future Interns for the internship opportunity  
- The creators of the Telco dataset  
- All open-source contributors to the libraries used in this project
