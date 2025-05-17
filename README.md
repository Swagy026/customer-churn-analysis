# 🔍 Customer Churn Analysis (Python)

## 📌 Overview
This project analyzes customer churn using a real-world telecom dataset. The goal is to identify which factors influence churn and to build a predictive model using logistic regression.

## 🧠 Problem Statement
Telecom companies lose revenue when customers leave (churn). By understanding patterns in customer behavior, we can predict churn and take proactive steps to retain high-risk customers.

## 🧰 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Train-Test Split, Evaluation)
- Jupyter Notebook
- Joblib (model saving)

## 📂 Project Structure
/customer-churn-analysis/
├── churn_analysis.ipynb
├── telco_customer_churn.csv
├── model/
│ └── churn_model.pkl


## 🚀 Steps Performed
1. Loaded and cleaned the dataset
2. Visualized churn patterns by category and contract
3. Engineered features with one-hot encoding
4. Trained a Logistic Regression model
5. Achieved churn prediction accuracy of ~**[your model's score]%**
6. Saved the final model for reuse

## 📈 Results
The model identifies churn-prone customers with reasonable precision. Visual EDA shows higher churn rates in short-term contract plans and customers with high monthly charges.

## 🛠️ How to Run
1. Clone this repo and open the Jupyter Notebook
2. Run all cells to replicate analysis
3. Use the trained model saved as `churn_model.pkl` for predictions

## 📊 Dataset Source
[Kaggle: Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
