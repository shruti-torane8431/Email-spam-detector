Spam Detection Project
This project employs machine learning techniques to detect spam messages from a dataset. The goal is to predict whether a given message is spam or not. The project uses Multinomial Naive Bayes (MultinomialNB) and CountVectorizer to transform text data into numerical features for model training.

Project Overview
Objective: Build a machine learning model to classify messages as spam or not spam.

Techniques Used:

Multinomial Naive Bayes: A classification algorithm suitable for word count data.

CountVectorizer: Converts text data into a matrix of token counts (bag-of-words representation).

Dataset
The dataset consists of two columns:

message: Contains the actual message text.

category (Initially): Labels the message as spam or not spam (later removed and replaced with a new column).

Data Preprocessing
Column Transformation:

The category column was removed.

A new boolean column, spam, was added to indicate whether a message is spam (True) or not (False).

Model Pipeline
The project follows a pipeline architecture that includes the following steps:

Data Cleaning and Transformation: Preparing and converting raw text data into a suitable format.

Text Vectorization: Using CountVectorizer to convert the text data into numerical form (a bag-of-words matrix).

Model Training: Training the data using Multinomial Naive Bayes (MultinomialNB) on the transformed dataset.

Model Evaluation: Evaluating the model using classification metrics like accuracy, precision, recall, and F1-score.

Achievements
Accuracy: The model achieves 98% accuracy on the test set.

The classification report shows excellent performance with high precision, recall, and F1-score.

Steps Involved
Data Preprocessing:

Cleaning the dataset.

Converting messages into numerical features.

Replacing the category column with the spam boolean column.

Splitting the Data:

Dividing the data into training and testing sets for model evaluation.

Model Training:

Training a Multinomial Naive Bayes model using the processed data.

Evaluation:

Evaluating the model’s performance using accuracy and generating a classification report.

Installation
