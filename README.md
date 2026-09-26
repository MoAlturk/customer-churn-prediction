# Customer Churn Prediction 📊🤖

An End-to-End Machine Learning project to predict customer churn for a telecommunications company using a Logistic Regression model.

## 🚀 Project Overview
Customer churn is a critical business metric. This project builds a predictive model to identify customers who are likely to leave the service, allowing the company to take proactive retention measures.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:** Pandas, NumPy, Scikit-Learn

## 📈 Pipeline Steps
1. **Data Cleaning:** Handled missing values in `TotalCharges` and dropped irrelevant identifiers (`customerID`).
2. **Feature Engineering:** Applied One-Hot Encoding (`pd.get_dummies`) and handled multicollinearity (`drop_first=True`).
3. **Data Splitting:** Split dataset into 80% training and 20% testing sets.
4. **Feature Scaling:** Standardized features using `StandardScaler` to prevent data leakage.
5. **Model Training:** Trained a **Logistic Regression** classifier.
6. **Evaluation:** Evaluated model performance using Accuracy, Precision, Recall, and F1-Score (achieving ~79% accuracy).

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/customer-churn-prediction.git](https://github.com/YOUR-USERNAME/customer-churn-prediction.git)
