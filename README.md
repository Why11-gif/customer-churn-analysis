## Customer Churn Analysis

# Overview

Customer churn is one of the most important business problems in the telecom industry. This project analyzes customer behavior and builds machine learning models to predict whether a customer is likely to leave the company.

The goal is to identify the factors that contribute to customer churn and help businesses improve customer retention strategies.



# Dataset

Dataset: Telco Customer Churn Dataset

Total Records: 7,032

Features: 21

Target Variable: Churn

---

# Project Workflow

### 1. Data Collection
- Loaded telecom customer churn dataset using Pandas.

### 2. Data Cleaning
- Identified missing values.
- Removed records with missing TotalCharges values.
- Converted TotalCharges to numeric format.

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer churn distribution.
- Studied contract type vs churn.
- Studied tenure vs churn.
- Studied monthly charges vs churn.
- Generated correlation heatmap.

### 4. Feature Engineering
- Encoded categorical variables using Label Encoding.
- Prepared data for machine learning models.

### 5. Model Building
Implemented:

- Logistic Regression
- Random Forest Classifier

### 6. Model Evaluation
Evaluated models using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

# Results

### Logistic Regression

Accuracy: 78.75%

Confusion Matrix:

[[921, 112],
 [187, 187]]

### Random Forest Classifier

Accuracy: 78.46%

Confusion Matrix:

[[934, 99],
 [204, 170]]

---

# Key Insights

- Customers with Month-to-Month contracts show significantly higher churn rates.
- Customers with shorter tenure are more likely to leave.
- Higher monthly charges are associated with increased churn.
- Longer contract periods improve customer retention.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- VS Code

---

## Project Structure

customer-churn-analysis/

├── data/

├── notebooks/

│ └── churn_analysis.ipynb

├── images/

├── README.md

---

## Future Improvements

- Hyperparameter Tuning
- Feature Selection
- XGBoost Implementation
- Deployment using Streamlit

---

# Author

Kalpana

Aspiring Data Scientist | Python | Machine Learning | Data Analytics