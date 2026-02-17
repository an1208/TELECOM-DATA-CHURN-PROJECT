# 📌 Project Title
**Customer Churn Prediction using Machine Learning**

---

## 📊 Problem Statement
Customer churn is a critical challenge in the telecom industry. This project aims to predict which customers are likely to leave based on their demographic information and service usage patterns. By identifying high-risk customers, the company can deploy proactive retention strategies to minimize revenue loss.

---

## 📂 Dataset
**Telco Customer Churn Dataset**  
- **Source:** [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)  
- **Description:** Contains 7,043 rows and 21 features including tenure, contract type, payment method, and monthly charges.

---

## 🛠️ Technologies Used
- **Python** – Core Analysis  
- **Pandas & NumPy** – Data Manipulation  
- **Scikit-learn** – Machine Learning & Hyperparameter Tuning  
- **Matplotlib & Seaborn** – Data Visualization  
- **Imbalanced-learn (SMOTE)** – Handling Class Imbalance  

---

## ⚙️ Methodology

### 1. Data Cleaning
- Handled hidden missing values in `TotalCharges`.  
- Dropped irrelevant features like `customerID`.

### 2. Preprocessing
- Applied One-Hot Encoding to categorical variables.  
- Performed feature scaling for numerical variables.

### 3. Handling Imbalance
- Used **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the churn vs. non-churn classes in the training data.

### 4. Model Training
- Compared **Logistic Regression** and **Random Forest Classifier**.

### 5. Optimization
- Performed **GridSearchCV** on the Random Forest model to optimize for the **Entropy** criterion and **tree depth**.

---

## 📈 Final Model Comparison (Class 1 - Churners)

| Model                  | Precision | Recall | F1-score | ROC-AUC |
|------------------------|-----------|--------|----------|---------|
| Logistic Regression    | 0.49      | 0.79   | 0.61     | 0.8351  |
| Random Forest (Optimized) | 0.56   | 0.68   | 0.62     | 0.8293  |

---

## 💡 Key Findings & Business Insights

- **The Best "Safety Net":**  
  Logistic Regression achieved the highest **Recall (79%)**, making it ideal to identify every possible at-risk customer.

- **The Best "Precision Tool":**  
  Random Forest improved **Precision to 56%**, reducing "false alarms" and ensuring marketing resources target customers truly likely to leave.

- **Top Churn Drivers:**  
  Customers with **month-to-month contracts** and **low tenure (<6 months)** showed the highest probability of churn.

- **Strategy Recommendation:**  
  Focus on **incentive programs** to convert month-to-month users into annual contracts to significantly improve retention.

---

## 🌐 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anushka-sharma-1208ans)  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anushka.sh0812@gmail.com)  
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/an12ushka)

