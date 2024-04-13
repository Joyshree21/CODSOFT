# Customer Churn Prediction Model

This project aims to develop a model to predict customer churn for a subscription-based service or business. The model utilizes historical customer data, including features such as usage behavior and customer demographics, to forecast whether a customer is likely to churn.

# Dataset
The dataset used for this project contains historical customer data, including various features related to usage behavior, customer demographics, subscription details, and interaction history. Each row in the dataset represents a customer, and the columns include:
The dataset is available in the folder

Feature 1
Feature 2
...
Churn (Target Variable)
The dataset is stored in the file customer_churn_data.csv.

# Algorithms
The following algorithms are employed to predict churn:

Logistic Regression
Random Forests
Gradient Boosting

# Project Structure


data/: Directory containing the dataset file customer_churn_data.csv.

notebooks/: Directory containing Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.

models/: Directory containing saved trained models.

src/: Directory containing source code for data preprocessing, model training, and evaluation.

README.md: Overview of the project, dataset, algorithms used, and project structure.

# Result


     precision    recall  f1-score   support

           0       0.83      0.97      0.90      1607
           1       0.62      0.19      0.29       393

    accuracy                           0.82      2000
   macro avg       0.72      0.58      0.59      2000
weighted avg       0.79      0.82      0.78      2000


# Conclusion
In this project, we aimed to develop a model to predict customer churn for a subscription-based service or business. Leveraging historical customer data containing features like usage behavior and customer demographics, we employed various machine learning algorithms, including Logistic Regression, Random Forests, and Gradient Boosting, to forecast whether a customer is likely to churn.

After thorough data exploration, preprocessing, and model training, we evaluated the performance of each algorithm using metrics such as accuracy, precision, recall, and F1-score. The models showed promising results in identifying customers at risk of churn, providing valuable insights for proactive retention strategies and customer relationship management.

Overall, this project demonstrates the effectiveness of machine learning techniques in predicting customer churn and underscores the importance of leveraging data-driven approaches to mitigate customer attrition and enhance business sustainability. Moving forward, continuous monitoring and refinement of the predictive models will be crucial to maintaining their accuracy and relevance in dynamic business environments.
