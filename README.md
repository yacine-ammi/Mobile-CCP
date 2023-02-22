## Project Overview

### Objective

The objective of this project is to analyze a public dataset of customers from a telecom company and predict whether a customer will switch to another company, thereby increasing profitability. 

### Dataset Description

- This project utilizes a public dataset of 66,469 customers from an anonymous telecommunications company.
- The goal of the project is to predict customer churn and increase profitability for the company.
- Data preprocessing and cleaning techniques were used on 66 features before moving to the modelling phase.

### Methodology

This project utilized both univariate and multivariate analysis to extract critical insights based on visualizations and correlation matrices. A data preprocessing stage was then required before the modeling phase could begin, where various techniques were used to prepare for the modeling stage. Various classification models were then applied to determine which one performed the best in identifying customers who may churn. The XGBoost model was chosen, evaluated, and interpreted using the SHAP package.

### Modelling

- Univariate and multivariate analysis were used to extract insights from the dataset.
- Several classification models were tested, including ensemble learning methods like XGBoost.
- The XGBoost model outperformed the other models with an accuracy of 90%.
- Hyperparameter optimization was used to improve recall and meet business needs.

### Results

- The XGBClassifier model is capable of effectively handling both churners and non-churners.
- User spendings was found to be the most relevant feature in predicting customer churn.
- SHAP values were used to interpret the model and examine feature influence.

### Project Structure

- `data`: contains the raw dataset, cleaned dataset, and partitioned datasets.
- `notebooks`: contains Jupyter notebooks for data preprocessing, EDA, and modelling.
- `data dictionaey`: table in pdf.
- `presentation`: in ppx.

### Conclusion

This study concluded that ensemble learning algorithms, such as XGBoost, performed the best in predicting customer churn with an accuracy of 90%. The XGBClassifier model is capable of handling both classes effectively in identifying churners and non-churners. The most relevant feature in predicting customer churn is `user_spendings`. SHAP values were used to interpret the model and examine feature influence, providing a better understanding of the model's behavior. Additionally, we were able to examine and determine the influence of each feature on churn prediction both globally on the whole dataset and individually on two random customers.
