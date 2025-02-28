# NLP Final Project 2025
## SVM, Random Forest, and Naive Bayes Machine Learning Models for Text Classification Tasks in Swahili
# Project Overview
This project focuses on developing machine learning models for text classification, specifically for Swahili online news platforms. The goal is to automatically organize articles into predefined categories, making it easier for readers to locate relevant news. This project also aims to enhance the representation of the Swahili language in digital applications and online platforms.
# Dataset
The dataset consists of 6439 rows of news articles from various sources in Tanzania, categorized into five different news categories:
1. Kitaifa (National)
2. Kimataifa (International)
3. Biashara (Business)
4. Michezo (Sports)
5. Burudani (Entertainment)

- The dataset can be accessed from Zindi. (https://zindi.africa/competitions/swahili-news-classification/data)
Project Steps
- Dataset Loading: Importing and preparing the dataset for analysis.
- Feature and Target Variable Analysis: Understanding the structure and significance of the features and target labels.
- Data Preprocessing: Cleaning and refining the dataset to ensure quality and consistency.
- WordCloud Visualization: Generating word clouds to analyze common words in the dataset.
- Label Encoding: Converting categorical labels into numerical representations.
- Word Embedding: Transforming textual data into vector representations for model input.
- Model Development: Implementing machine learning algorithms, including:
  a) Support Vector Machine (SVM)
  b) Random Forest
  c) Naive Bayes

## Code Structure
- The code is structured into several sections, each corresponding to a step in the project:
- Mounting Google Drive: Accessing the dataset stored in Google Drive.
- Importing Libraries: Importing necessary libraries such as pandas, numpy, matplotlib, seaborn, nltk, and scikit-learn.
- Loading the Data: Loading the training, testing, sample submission, and variable definitions datasets.
- Data Exploration: Exploring the dataset to understand its structure and content.
- Data Preprocessing: Cleaning and preprocessing the text data.
- Visualization: Generating word clouds and other visualizations to understand the data distribution.
- Model Development: Implementing and training machine learning models.
- Model Evaluation: Evaluating the models using accuracy and classification reports.

## Requirements
To run the code, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- wordcloud
- scikit-learn
