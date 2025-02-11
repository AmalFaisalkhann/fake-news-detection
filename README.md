# fake-news-detection
This project is a Fake News Detection system built using Python and machine learning techniques. It utilizes logistic regression to classify news articles as either true or fake based on their content. The dataset includes labeled true and fake news articles, which are vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) and then fed into a machine learning model for training and evaluation.

Features

Dataset Handling:Loads true and fake news datasets from CSV files.
Assigns labels (1 for fake news, 0 for true news).
Merges and shuffles the datasets to ensure randomness.

Feature Engineering:
Combines title, text, and subject fields to create a unified text feature.
Uses TF-IDF vectorization to convert text into numerical representations.

Model Training:
Splits data into training and testing sets.
Trains a logistic regression model on the processed data.

Evaluation:
Generates confusion matrices to visualize classification results.
Computes performance metrics such as accuracy, precision, recall, and F1-score.
Displays a classification report for detailed analysis.

Visualization:
Uses Seaborn and Matplotlib to plot the confusion matrix for better understanding.
