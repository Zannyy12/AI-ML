📧 Spam Mail Detection System using Python

A simple yet effective Spam Mail Detection System built using Python and machine learning.
This project uses a Kaggle email dataset and applies a Logistic Regression model to classify emails as Spam or Ham (Not Spam).

🚀 Features

Preprocessing and cleaning of dataset

Conversion of text into numerical features

Train–test data split for model evaluation

Logistic Regression machine learning model

Achieves high accuracy on real-world email data

Easy to extend for deployment or UI integration

🧰 Technologies & Libraries Used

Python

NumPy

Pandas

Scikit-learn (sklearn)

train_test_split

LogisticRegression

CountVectorizer or TfidfVectorizer (optional depending on your code)

📂 Dataset

The dataset used in this project is taken from Kaggle:

🔗 "Spam or Ham Dataset" or any similar dataset available on Kaggle.
(You can add the exact dataset link here.)

The dataset contains:

Email text

Label: spam or ham

📊 Project Workflow

Load Dataset using Pandas

Clean & preprocess the text data

Convert text to numerical vectors using CountVectorizer or TF-IDF

Split dataset into training and testing sets

Train Logistic Regression model

Evaluate the model using accuracy score, confusion matrix, etc.

Predict whether new emails are spam or ham
