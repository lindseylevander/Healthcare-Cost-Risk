# Healthcare-Cost-Risk
# Healthcare Cost and Risk Prediction Analysis

## Project Overview

This project analyzes healthcare insurance data to identify the primary influencers of medical costs and to develop predictive models for healthcare risk assessment. Using statistical analysis and machine learning techniques, the project explores how demographic and health-related factors influence insurance charges and high-cost risk classification.

The goal of this project is to simulate a real-world healthcare analytics workflow by combining exploratory data analysis, predictive modeling, and business-focused interpretation to support data-driven decision-making in the healthcare and insurance space.

---

## Objectives

* Analyze factors contributing to healthcare insurance costs
* Identify patterns and trends within patient demographic and health information
* Build regression models to predict medical insurance charges
* Develop classification models to identify high-risk individuals
* Translate analytical findings into actionable healthcare insights

---

## Dataset

Dataset Used:
Medical Cost Personal Dataset (Insurance Charges)

The dataset includes:

* Age
* Sex
* BMI
* Number of children/dependents
* Smoking status
* Geographic region
* Medical insurance charges

---

## Languages and Tools

* Python
* pandas
* NumPy
* scikit-learn
* matplotlib
* seaborn
* Google Colab

---

## Project Workflow

### 1. Data Exploration and Cleaning

* Reviewed dataset structure and data types
* Checked for missing values and inconsistencies
* Explored feature distributions and variable relationships

### 2. EDA

Performed visual and statistical analysis to evaluate:

* Smoking status vs medical charges
* BMI and age impact on costs
* Regional charge differences
* Cost distribution patterns

### 3. Feature Engineering

* Encoded categorical variables
* Created a high-risk classification label using top quartile insurance charges
* Prepared datasets for regression and classification tasks

### 4. Predictive Modeling

#### Regression Models

Used machine learning models to predict insurance charges:

* Linear Regression
* Random Forest Regressor

Evaluation Metrics:

* RMSE
* MAE
* R² Score

#### Classification Models

Built models to identify high-risk individuals:

* Logistic Regression
* Random Forest Classifier

Evaluation Metrics:

* Accuracy
* Precision & Recall
* ROC-AUC

---

## Key Insights

* Smoking status was the strongest predictor of increased healthcare costs
* Higher BMI and older age were associated with elevated medical charges
* Random Forest models outperformed baseline linear models in predictive performance
* Feature importance analysis highlighted behavioral and demographic variables that contribute most to healthcare cost risk

---

## Business Impact

This project demonstrates how predictive analytics can support healthcare insurers and providers by:

* Identifying high-risk individuals earlier
* Improving healthcare cost forecasting
* Supporting targeted care management strategies
* Enabling more data-driven operational and financial decision-making

---

## Future Improvements

Potential next steps include:

* Hyperparameter tuning
* SHAP explainability analysis
* Advanced ensemble modeling
* Risk segmentation and clustering
* Deployment as an interactive dashboard or API

---

## Author

Lindsey LeVander

MS Data Science – AI Optimization & Machine Learning

GitHub: https://github.com/lindseylevander
LinkedIn: https://www.linkedin.com/in/lindsey-levander-1b9874234/
