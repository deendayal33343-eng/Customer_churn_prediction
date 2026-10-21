# Customer Churn Prediction

## Project Overview
This project uses machine learning to predict customer churn for a telecommunications company. The goal is to identify customers who are likely to discontinue their services and understand the factors associated with churn.

## Objectives
- Explore and analyze customer data.
- Perform data cleaning and preprocessing.
- Encode categorical features using One-Hot Encoding.
- Train and evaluate multiple machine learning models.
- Compare model performance, with particular attention to identifying customers likely to churn.

## Dataset
The project uses a telecommunications customer churn dataset containing customer demographics, subscribed services, account information, and churn status.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Workflow
1. Data cleaning and exploratory data analysis (EDA).
2. Feature and target separation.
3. Train-test split with stratification.
4. Categorical feature encoding.
5. Model training and evaluation.
6. Stratified cross-validation using F1-score.
7. Comparison of model performance.

## Models
- Logistic Regression(Final model)
- Decision Tree Classifier
- Random Forest Classifier

Class weighting was explored to improve the identification of customers who churn.

## Evaluation Metrics
The models were evaluated using accuracy, precision, recall, F1-score, and confusion matrices. F1-score and recall for the churn class were given particular attention because missing a potential churn customer can be costly. The model has the churn recall of about 82% and churn precision of 53% and an overall accuracy of 76%

## Key Learning Outcomes
- Data preprocessing and categorical encoding.
- Exploratory data analysis.
- Training and evaluating classification models.
- Understanding the precision-recall trade-off.
- Using stratified cross-validation to assess model performance.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
3. Open the Jupyter Notebook.
4. Run the cells from top to bottom.

## Future Improvements
- Use a Scikit-learn Pipeline to combine preprocessing and model training.
- Tune classification thresholds using validation data.
- Perform further hyperparameter tuning and model comparison.

