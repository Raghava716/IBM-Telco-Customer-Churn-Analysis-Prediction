# 📊 Customer Churn Prediction using XGBoost

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Acquiring new customers is significantly more expensive than retaining existing ones. This project aims to predict whether a customer is likely to leave the company and identify the key factors influencing churn.

Using the Telco Customer Churn dataset, an end-to-end machine learning pipeline was developed, including data preprocessing, exploratory data analysis, feature engineering, model building, and business recommendations.

---

## 🎯 Project Objectives

* Analyze customer behavior and identify factors contributing to churn.
* Build a machine learning model to predict customer churn.
* Generate actionable business insights to improve customer retention.
* Visualize important trends and patterns in customer data.

---

## 📂 Dataset Information

**Dataset:** Telco Customer Churn Dataset

**Source:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn

**Dataset Size:**

* Total Customers: 7,043
* Features: 20
* Target Variable: Churn (Yes/No)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook / Kaggle Notebook
* Power BI (Optional)

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Customer churn distribution
* Contract type vs churn
* Internet service vs churn
* Payment method vs churn
* Tenure distribution
* Monthly charges distribution
* Correlation analysis
* Feature importance analysis

---

## 🔍 Data Preprocessing

* Removed unnecessary columns (`customerID`)
* Encoded categorical variables
* Split dataset into training and testing sets
* Applied feature engineering and preprocessing techniques

---

## 🤖 Machine Learning Model

### Model Used

* XGBoost Classifier

### Model Performance

| Metric        | Score  |
| ------------- | ------ |
| Accuracy      | 79.77% |
| Precision     | 64.88% |
| Recall        | 51.87% |
| F1 Score      | 57.65% |
| ROC-AUC Score | 84.03% |

---

## ⭐ Top Features Influencing Churn

1. Contract
2. InternetService
3. OnlineSecurity
4. TechSupport
5. Tenure
6. StreamingMovies
7. MultipleLines
8. PaperlessBilling
9. TotalCharges
10. PhoneService

---

## 📈 Key Business Insights

* Customers with month-to-month contracts are more likely to churn.
* Customers without online security services have a higher churn rate.
* Customers without tech support are more likely to leave.
* Customers with lower tenure are at greater risk of churning.
* Internet service type significantly impacts customer retention.

---

## 💡 Business Recommendations

* Encourage customers to switch to long-term contracts through discounts and incentives.
* Offer free trials for online security and technical support services.
* Implement customer retention campaigns for new customers.
* Provide personalized offers to high-risk customers.
* Improve customer service and support quality.

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── feature_importance.png
│   └── dashboard.png
│
├── requirements.txt
├── README.md
└── churn_model.pkl
```

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the Jupyter notebook or Kaggle notebook and execute all cells.

---

## 📷 Project Screenshots

Add the following screenshots to enhance your repository:

* Churn Distribution
* Contract vs Churn
* Feature Importance Plot
* Tableau Dashboard

---

## 🎓 Learning Outcomes

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Classification using XGBoost
* Model Evaluation Metrics
* Business Insight Generation
* Data Visualization and Storytelling

---

## 👨‍💻 Author

**Venkat Raghava C G**

M.Sc. Data Science | Data Analyst | Machine Learning Enthusiast

* LinkedIn: https://www.linkedin.com/in/raghavavenkat49
* Portfolio: https://datascienceportfol.io/raghavavenkat49

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
