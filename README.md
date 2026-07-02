# Customer_Churn_Prediction_using_ML
codewithsani/Customer_Churn_Prediction_using_ML
# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. Losing existing customers is often more expensive than acquiring new ones. This project uses machine learning to predict whether a customer is likely to churn based on demographic information, account details, and service usage.

The goal is to help businesses identify high-risk customers and take proactive retention measures.

---

## Business Problem

A telecommunications company wants to reduce customer churn by identifying customers who are most likely to leave. By accurately predicting churn, the company can target retention campaigns and improve customer satisfaction.

---

## Dataset

The dataset contains customer information including:

- Customer demographics
- Account information
- Services subscribed
- Monthly charges
- Total charges
- Contract type
- Payment method
- Customer tenure
- Churn status (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SMOTE (Imbalanced-learn)
- Joblib

---

## Project Workflow

1. Import libraries
2. Load and understand the dataset
3. Data cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Data Preprocessing
7. Handle class imbalance using SMOTE
8. Train multiple Machine Learning models
9. Model evaluation
10. Save the best-performing model
11. Build a prediction system

---

## Exploratory Data Analysis

The notebook includes:

- Distribution of numerical features
- Box plots for outlier detection
- Correlation heatmap
- Analysis of categorical variables
- Customer churn distribution

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns (Customer ID)
- Checked for missing values
- Label encoded categorical features
- Train-Test Split
- Applied SMOTE to balance the target classes

---

## Machine Learning Models

The following classification models were trained and compared:

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

Random Forest achieved the best performance among the default models.

---

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```
Customer_Churn_Prediction_using_ML/
│
├── Customer_Churn_Prediction_using_ML.ipynb
├── README.md
├── data/
│   └── customer_churn.csv
├── models/
│   └── churn_model.pkl
├── images/
└── requirements.txt
```

---

## Business Insights

This project enables organizations to:

- Identify customers with a high probability of churning
- Improve customer retention strategies
- Reduce revenue loss
- Support data-driven decision making

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature selection
- Downsampling comparison
- ROC-AUC analysis
- Precision-Recall analysis
- Deployment using Streamlit or Flask

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/codewithsani/Customer_Churn_Prediction_using_ML.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook Customer_Churn_Prediction_using_ML.ipynb
```

---

## Author

**Sani**

GitHub: https://github.com/codewithsani

---

## License

This project is intended for educational and portfolio purposes.
