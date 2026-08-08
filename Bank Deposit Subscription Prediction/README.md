# 🏦 Bank Deposit Subscription Prediction

## 📌 Project Overview

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on their personal, financial, and marketing campaign information.

The project follows an end-to-end Machine Learning workflow, including data exploration, preprocessing, feature encoding, model training, evaluation, cross-validation, hyperparameter tuning, feature importance analysis, and final model comparison.

## 📂 Dataset

The dataset contains **11,162 customer records and 15 features**, including numerical and categorical variables.

### 📋 Features

| Feature | Description |
|---|---|
| `age` | Customer's age |
| `job` | Type of job |
| `marital` | Marital status |
| `education` | Education level |
| `default` | Credit default status |
| `balance` | Average yearly balance |
| `housing` | Housing loan status |
| `loan` | Personal loan status |
| `month` | Month of the last contact |
| `duration` | Duration of the last contact |
| `campaign` | Number of contacts during the campaign |
| `pdays` | Days since the previous contact |
| `previous` | Number of previous contacts |
| `poutcome` | Outcome of the previous marketing campaign |
| `deposit` | Target variable — term deposit subscription |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- YData Profiling

## 🔍 Project Workflow

1. Data Loading & Understanding
2. Exploratory Data Analysis (EDA)
3. Data Quality Checks
4. Data Profiling
5. Univariate & Bivariate Analysis
6. Train-Test Split
7. Feature Encoding
8. Decision Tree Classification
9. Bagging Classification
10. Random Forest Classification
11. Model Evaluation
12. Confusion Matrix & Classification Report
13. 10-Fold Cross-Validation
14. Random Forest Hyperparameter Tuning using GridSearchCV
15. Feature Importance Analysis
16. Final Model Comparison
17. Conclusion & Key Insights

## 🤖 Machine Learning Models

The following tree-based classification models were trained and compared:

- Decision Tree
- Bagging Classifier
- Random Forest Classifier

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- 10-Fold Cross-Validation

Random Forest was further optimized using **GridSearchCV** to find a suitable combination of hyperparameters.

## 💡 Key Highlights

- Performed exploratory data analysis to understand customer and campaign characteristics.
- Applied appropriate encoding techniques to categorical and binary features.
- Compared a single Decision Tree with ensemble-based models.
- Used 10-Fold Cross-Validation to assess model consistency.
- Applied GridSearchCV for Random Forest hyperparameter tuning.
- Analyzed Random Forest feature importance.
- Compared models using both overall and class-wise performance metrics.

## 🎯 Project Objective

The main objective is to develop a reliable classification model that can predict whether a customer is likely to subscribe to a term deposit and to understand the factors that contribute to these predictions.

## 👨‍💻 Author

**Fahad**

This project was developed as part of my Machine Learning learning journey and practical project work.
