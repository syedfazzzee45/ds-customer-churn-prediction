# 📊 Telco Customer Churn Prediction

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. In this project, machine learning techniques are used to predict whether a customer is likely to leave a telecommunications company based on demographic information, account details, and service usage.

The objective is to compare multiple machine learning algorithms and identify the model that provides the best predictive performance.



## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer information including:

- Customer demographics
- Account information
- Services subscribed
- Contract type
- Monthly charges
- Total charges
- Customer churn status (Target Variable)



## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook



## Exploratory Data Analysis

The project includes:

- Dataset inspection
- Missing value analysis
- Feature distributions
- Customer churn visualization
- Correlation analysis



## Data Preprocessing

The following preprocessing steps were performed:

- Missing value handling
- Data type conversion
- One-Hot Encoding
- Feature Scaling
- Train-Test Split



## Machine Learning Models

The following classification models were implemented and compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost



## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|-------|---------:|----------:|--------:|---------:|--------:|
| Logistic Regression | 0.787 | 0.621 | 0.516 | 0.564 | **0.832** |
| Decision Tree | 0.775 | 0.576 | **0.591** | 0.583 | 0.813 |
| Random Forest | **0.792** | **0.647** | 0.476 | 0.549 | 0.820 |
| XGBoost | 0.790 | 0.628 | 0.519 | 0.568 | 0.824 |



## Feature Importance

Feature importance analysis identified several key variables influencing customer churn, including:

- Contract Type
- Tenure
- Monthly Charges
- Total Charges
- Internet Service

These features provide valuable insights into customer retention strategies.



## Conclusion

Multiple machine learning models were developed and evaluated for customer churn prediction.

- Random Forest achieved the highest **Accuracy (79.2%)**.
- Logistic Regression achieved the highest **ROC-AUC (0.832)**.
- XGBoost produced competitive performance across all evaluation metrics.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and interpretation.



## Future Improvements

Potential enhancements include:

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature engineering
- SHAP explainability
- Model deployment using Flask or Streamlit
- Real-time customer churn prediction dashboard



## Author

**Faizan Syed**

- GitHub: https://github.com/syedfazzzee45



## Repository Structure

```text
ds-customer-churn-prediction/
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks/
│   └── 01_data_understanding.ipynb
├── requirements.txt
└── README.md
```
