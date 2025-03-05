# Credit Risk Modeling for Loan Default Prediction

## Overview
This project aims to develop a machine learning model for predicting loan defaults, a key aspect of credit risk modeling. The dataset used (`bankloans.csv`) contains information on loan applicants, and the task is to predict whether a loan applicant will default based on various features. The project involves data preprocessing, model development, evaluation, and comparison using two machine learning algorithms: Random Forest and XGBoost.

## Key Insights:
- The Random Forest and XGBoost classifiers were both effective in predicting loan defaults with high accuracy.
- XGBoost achieved a slightly higher AUC-ROC score, indicating better model performance in distinguishing between default and non-default classes.

## Skills Learned:
- **Credit Risk Modeling**: Applied machine learning to predict loan defaults.
- **Data Preprocessing**: Managed missing values, scaled features, and split data into training and testing sets.
- **Model Training and Evaluation**: Used Random Forest and XGBoost for classification and evaluated models using accuracy, AUC-ROC, and classification report.
- **Python Libraries**: Worked with pandas, scikit-learn, and XGBoost for modeling.

## Future Work
- **Hyperparameter Tuning**: Explore fine-tuning model parameters (e.g., grid search or random search) to improve performance.
- **Model Interpretability**: Implement SHAP or LIME to understand model predictions and improve transparency.
- **Additional Models**: Experiment with other models like logistic regression, SVM, or neural networks.


## Acknowledgments
- Dataset: `bankloans.csv` (publicly available for credit risk prediction tasks).
