# SMS Spam Classification Model

This project aims to build an AI model capable of classifying SMS messages as spam or legitimate. The model utilizes various techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings in conjunction with classifiers like Naive Bayes, Logistic Regression, or Support Vector Machines (SVM) to identify spam messages accurately.

# Dataset
The dataset used for this project contains a collection of SMS messages labeled as spam or legitimate. Each message in the dataset is labeled with its corresponding class (spam or legitimate).

The dataset is stored in the file sms_spam_data.csv.

# Techniques Used
The following techniques are employed for SMS spam classification:

TF-IDF (Term Frequency-Inverse Document Frequency)
Word Embeddings

# Classifiers Used
The following classifiers are utilized for SMS spam classification:

Naive Bayes
Logistic Regression
Support Vector Machines (SVM)

# Project Structure

data/: Directory containing the dataset file sms_spam_data.csv.
notebooks/: Directory containing Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
models/: Directory containing saved trained models.
src/: Directory containing source code for data preprocessing, model training, and evaluation.
README.md: Overview of the project, dataset, techniques used, classifiers employed, and project structure.

# Result 
Support Vector Machine (SVM) Model:
[[886   3]
 [ 14 131]]
              precision    recall  f1-score   support

           0       0.98      1.00      0.99       889
           1       0.98      0.90      0.94       145

    accuracy                           0.98      1034
   macro avg       0.98      0.95      0.96      1034
weighted avg       0.98      0.98      0.98      1034

Accuracy:  0.9835589941972921
r2_Score:  0.8636360110158644
Precision_score:  0.9776119402985075
Recall_score:  0.903448275862069
f1_score:  0.939068100358423


# Conclusion 

In this project, we developed an AI model for classifying SMS messages as spam or legitimate. Leveraging techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) and word embeddings in combination with classifiers like Naive Bayes, Logistic Regression, and Support Vector Machines (SVM), we achieved accurate identification of spam messages.

After thorough data exploration, preprocessing, and model training, we evaluated the performance of each classifier using metrics such as accuracy, precision, recall, and F1-score. The models demonstrated strong performance in distinguishing between spam and legitimate messages, effectively identifying potential threats and minimizing user exposure to unsolicited content.

Overall, this project showcases the effectiveness of machine learning techniques in addressing the challenge of SMS spam classification, highlighting the importance of leveraging advanced algorithms and feature extraction methods to enhance message filtering capabilities. Moving forward, continuous monitoring and refinement of the classification models will be essential to adapt to evolving spam patterns and ensure robust protection against unwanted communications.
