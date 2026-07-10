# Employee Attrition Prediction using Machine Learning

## 📌 Overview

This project predicts whether an employee is likely to leave the company based on different factors such as age, monthly income, job role, work-life balance, years at the company, and more.

The main goal of this project is to help organizations identify employees who may be at risk of leaving so that they can take steps to improve employee retention.

---

## 🎯 Objectives

- Understand the employee attrition dataset.
- Perform data cleaning and preprocessing.
- Explore the data to identify important patterns.
- Build multiple machine learning models.
- Compare model performance and select the best model.

---

## 📂 Dataset

The dataset contains employee information such as:

- Age
- Department
- Job Role
- Monthly Income
- Work-Life Balance
- Years at Company
- Education
- Business Travel
- Overtime
- Attrition (Target Variable)

---

## 🛠️ Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values.
- Removed unnecessary columns.
- Converted the target variable (Attrition) into numerical values.
- Applied One-Hot Encoding for categorical features.
- Standardized the data using StandardScaler.

---

## 📊 Exploratory Data Analysis (EDA)

The dataset was analyzed to understand employee attrition patterns.

Some key findings include:

- Sales department showed the highest attrition rate.
- Sales Representatives had the highest employee attrition.
- Employees with lower monthly income were more likely to leave.
- Poor work-life balance was associated with higher attrition.
- Employees who left generally had fewer years at the company.

---

## 🤖 Machine Learning Models

The following models were implemented:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📈 Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **88.09%** |
| Random Forest | 87.76% |
| Gradient Boosting | 87.07% |

Logistic Regression achieved the best overall performance for this dataset and was selected as the final model.

---

## 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Future Improvements

- Perform hyperparameter tuning to improve model performance.
- Handle class imbalance using techniques such as SMOTE.
- Try advanced machine learning algorithms like XGBoost or LightGBM.
- Deploy the model as a web application.

---

## 📌 Conclusion

This project demonstrates how machine learning can be used to predict employee attrition and provide useful insights for HR teams. By identifying employees who are likely to leave, organizations can take proactive measures to improve employee satisfaction and reduce turnover.
