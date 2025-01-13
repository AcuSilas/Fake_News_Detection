# Fake_News_Detection

### Overview
In today's digital era, fake news spreads like wildfire, often leading to misinformation and confusion. This project aims to tackle this problem by developing a machine learning model that can distinguish between real and fake news. Using Python and advanced libraries like sklearn, this project leverages techniques such as TfidfVectorizer and PassiveAggressiveClassifier to create an effective solution.

### Introduction
What is Fake News?
Fake news refers to fabricated information or news stories designed to mislead or manipulate readers, often for political or financial gain. Such news spreads rapidly via social media, causing misinformation. Detecting fake news requires sophisticated algorithms that analyze text patterns and contexts.

### Project Goal
The goal of this project is to build a machine learning model that can classify news articles as REAL or FAKE with high accuracy.

### Dataset
The dataset used for this project is named news.csv and contains the following:

### Columns:
ID: Unique identifier for each news article.
Title: The title of the news article.
Text: The body content of the article.
Label: Classification as REAL or FAKE.
Shape: 6335 rows × 4 columns.

### Technologies Used
Programming Language: Python 3.x
Libraries and Tools:
pandas: For data manipulation.
numpy: For numerical operations.
sklearn: For machine learning algorithms.
TfidfVectorizer: For text feature extraction.
PassiveAggressiveClassifier: For building the classification model.

### Project Workflow
Data Loading and Exploration:
Load the dataset and explore the structure and labels.
Data Preprocessing:
Handle missing values, if any.
Split the dataset into training and testing sets.
Feature Extraction:
Convert the textual data into numerical vectors using TfidfVectorizer.
Model Building:
Train a PassiveAggressiveClassifier on the training data.
Evaluate the model on test data using accuracy score and confusion matrix.
Results and Insights:
Analyze the model’s performance.
Visualize results using the confusion matrix.

### Results
Accuracy Score: 92.74%
Confusion Matrix: array([[587,  51],[ 41, 588]]
