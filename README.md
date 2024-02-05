# Bank Customer Churn Prediction Project

---

Welcome to the Customer Churn Prediction Project! This project aims to predict whether a bank customer will leave the company based on their past behavior and contract termination history. The project involves data preparation, model training, and evaluation to achieve the highest F1 score possible. Additionally, we'll explore techniques to handle class imbalance and compare the F1 score with the AUC-ROC metric.

## Project Description

In the banking sector, retaining loyal customers is more cost-effective than acquiring new ones. Our task is to predict customer churn by analyzing historical data and customer behavior. The dataset contains various features such as credit score, age, tenure, balance, and more. The target variable 'Exited' indicates whether a customer has churned (1) or not (0). We aim to build a predictive model with a minimum F1 score of 0.59 on the test dataset.

## Project Structure

1. **Data Preparation**: Download and preprocess the dataset. Ensure that all features are processed adequately, and handle any missing values or outliers.

2. **Class Balance Check**: Examine the balance of each class in the dataset to understand the distribution of churned and retained customers.

3. **Baseline Model**: Train a model without considering class imbalance and evaluate its performance using metrics such as precision, recall, F1 score, and AUC-ROC.

4. **Imbalanced Class Handling**: Implement at least two techniques to address class imbalance, such as oversampling or undersampling. Train multiple models and select the best performing one.

5. **Model Evaluation**: Perform a final evaluation of the selected model using the test dataset. Compare the F1 score with the AUC-ROC metric and document the results.

## Data Description

### Features

1. **RowNumber**: Index string data
2. **CustomerId**: Customer ID
3. **Surname**: Last name
4. **CreditScore**: Credit score
5. **Geography**: Country of residence
6. **Gender**: Gender
7. **Age**: Age
8. **Tenure**: Duration of the fixed-term deposit (in years)
9. **Balance**: Account balance
10. **NumOfProducts**: Number of bank products used by the customer
11. **HasCrCard**: Whether the customer has a credit card (1 for yes; 0 for no)
12. **IsActiveMember**: Customer activity level (1 for yes; 0 for no)
13. **EstimatedSalary**: Estimated salary

### Target

- **Exited**: Whether the customer has left (1 for yes; 0 for no)

## Evaluation Criteria

The project will be evaluated based on the following criteria:

- Data preparation process and feature engineering.
- Handling of class imbalance and exploration of alternative techniques.
- Model training, validation, and final testing procedures.
- Achievement of F1 score threshold (minimum 0.59) on the test dataset.
- Consideration of AUC-ROC metric and comparison with F1 score.
- Project structure and code organization.

## Instructions

1. Download the dataset from `/datasets/Churn.csv`.
2. Follow the steps outlined in the project description.
3. Ensure thorough documentation and explanation of your approach.
4. Aim to achieve the highest F1 score possible on the test dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---