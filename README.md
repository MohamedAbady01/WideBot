# WideBot
Title: NLP Text Classification with Random Forest, Decision Tree, and Logistic Regression

Introduction:
This repository contains a Natural Language Processing (NLP) project for text classification
using three different classifiers: Random Forest, Decision Tree, and Logistic Regression. 
The goal of this project is to predict the 'topic' based on the 'story' and 'title' columns in the dataset.
The dataset was preprocessed using Porter Stemmer to reduce words to their base form,
and then it was vectorized for modeling. The target variable 'topic' was encoded using LabelEncoder.
The models were evaluated using various metrics such as R2 Score, Classification Report, and Confusion Matrix.

Dataset:
The dataset used for this project https://www.kaggle.com/datasets/tariqmassaoudi/hespress

Data Preprocessing:

Text Processing: The text data in 'story' and 'title' columns were preprocessed using Porter Stemmer to convert words to their base form.
Vectorization: The preprocessed text data was transformed into numerical feature vectors using CountVectorizer or TF-IDFVectorizer, making it suitable for modeling.

Modeling:
We utilized three classifiers for text classification:

Random Forest
Decision Tree
Logistic Regression
Evaluation Metrics:

R2 Score: To assess the goodness of fit of each model and measure the explained variance in the target variable.
Classification Report: To provide insights into the model's performance for each class, including precision, recall, and F1-score.
Confusion Matrix: To visualize the model's classification performance and identify true positive, true negative, false positive, and false negative predictions.
Usage:

Clone the repository and navigate to the project directory.

Ensure you have the required dependencies installed 

Run the Jupyter notebook or Python script for data preprocessing, modeling, and evaluation.
Results:
The results for each model can be found in the project's Jupyter notebook or Python script.
The evaluation metrics and performance of each model on the test set are presented in detail.

Conclusion:
This NLP text classification project demonstrated the application 
of three classifiers to predict the 'topic' based on the 'story' and 'title' columns. 
The models' performance was evaluated using R2 Score, Classification Report, and Confusion Matrix. 
The insights gained from this project may serve as a foundation for further improvements and feature engineering
to enhance model performance.
