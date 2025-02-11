# 📊 TikTok Engagement & Sentiment Analysis

## 🔍 Overview
This project explores TikTok engagement dynamics using machine learning and sentiment analysis to identify key factors influencing user interaction. By analysing video metadata, user attributes, and sentiment in captions, we predict engagement levels and provide actionable insights for content optimisation.

## 🎯 Key objectives
- Predict engagement levels (Low, Medium, High) using logistic regression, Random Forest, and XGBoost.
- Analyse how hashtags, video length, and music trends impact engagement.
- Perform sentiment analysis on video captions to assess its effect on likes, shares, and comments.
- Provide data-driven strategies to enhance TikTok content performance.

## 📌 Thought process steps
**1. Define Project Scope & Key Questions**
- Identify the main objectives and research questions.
**2.Determine Required Variables**
- Select relevant variables for visualizations, relationships, and statistical analysis.
**3.Dataset Exploration & Preprocessing**
- Examine the dataset to understand the data types of each column.
- Standardise and convert data types as needed.
- Remove columns with more than 70% missing values or those irrelevant to the analysis.
- Handle missing values using appropriate imputation methods (mean, median, mode, or zero).
- Generate summary statistics and visualize distributions using histograms or bar plots.
- Identify and address outliers if necessary.
**4. Sentiment analysis**
- Clean text data (remove special characters, etc.).
- Compute sentiment scores using Python libraries.
- Visualise text data through
  + Bar charts for word frequency.
  + Word clouds or bubble graphs for keyword emphasis.
- Explore the relationship between sentiment and engagement (likes, shares, comments, play count).
- Use SHAP scores to assess the impact and direction of each factor on sentiment scores.
**5.Engagement prediction**
- Compute engagement score: (like + share + comment)/ follow (or view) * 100
- Use ML Regression method to predict how other factors such as hashtags, sentiment score, mention, number of followers, account popularity, likes, video duration, kind of music use impact the engagement rate
- Or categorise engagement score according to quantiles and use ML Classifier method to assess the above factors.
- Evaluate models using F1-score, recall, precision, and ROC-AUC.
- Perform hyperparameter tuning to improve model performance.
- Analyse feature importance to identify the most influential factors and their impact direction.
