<div align="center">

# 📈 Loan Default Prediction Project: Paycast

<img align="center" src="https://github.com/MaSOouD69/Loan-prediction/blob/main/Paycast%20Logo.png" title="Paycast" alt="Paycast" width="400" height="400"> 

</div>

## 🎯 Project Overview

This project leverages machine learning to predict loan payment statuses accurately. By doing so, it offers lending institutions enhanced risk assessment, decision-making processes, and the potential to minimize financial losses.

## 📊 Dataset

The dataset comes from **LendingClub**, a prominent peer-to-peer lending platform in the United States. Each row represents a unique loan, and each column represents a different loan attribute, including:
- Loan amount
- Term
- Interest rate
- Grade, sub-grade
- Employment title, employment length
- Home ownership
- Annual income

## 🚀 Project Workflow

### 🧹 [Data Cleaning](https://github.com/MaSOouD69/Loan-prediction/blob/main/1.%20data_cleaning.ipynb)
We started by tidying up the dataset: removing irrelevant features, handling missing data, and eliminating any features not available at loan issuance time.

### 🕵️‍♂️ [Exploratory Data Analysis (EDA)](https://github.com/MaSOouD69/Loan-prediction/blob/main/2.%20EDA.ipynb)
EDA helped understand feature distributions and relationships with loan status, thus informing model choice and guiding feature engineering.

### 🧠 [Feature Engineering](https://github.com/MaSOouD69/Loan-prediction/blob/main/3.%20Feature%20Engineering.ipynb)
We transformed existing data through one-hot encoding, converting categorical variables into machine-learning-friendly formats.

### 📊 [Modeling](https://github.com/MaSOouD69/Loan-prediction/blob/main/4.%20modeling.ipynb)
We tested and evaluated various models, including:
- Logistic Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- XGBoost

The **Random Forest model** was chosen for its superior performance.

## 📝 Findings and Conclusions
The best-performing model boasts an accuracy of ~80% and correctly identifies 93% of loans paid off, enhancing risk assessment.

Potential improvements include:
1. **Addressing Class Imbalance:** The dataset had many more loans that were paid off than defaulted. Techniques such as random oversampling could be used to address this imbalance.
2. **Incorporating More Features:** Additional features not included in the current dataset could potentially enhance the predictive power of the model.
3. **Trying Different Models:** While the Random Forest model performed best in this project, other techniques such as neural networks, or ensemble methods could potentially yield better results.
4. **Balancing Power with Interpretability:** Depending on the needs of the end user, future work could focus on models that balance predictive power with interpretability.


This project demonstrates the practical application of data science techniques in predicting loan defaults and provides valuable insights for risk assessment in lending institutions. Future work will aim to further improve the model's performance and interpretability.
