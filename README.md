# 📊 TikTok Engagement & Sentiment Analysis

## 🔍 Overview
This project explores TikTok engagement dynamics using machine learning and sentiment analysis to identify key factors influencing user interaction. By analysing video metadata, user attributes, and sentiment in captions, we predict engagement levels and provide actionable insights for content optimisation.

## 🎯 Key objectives
- Predict engagement levels (Low, Medium, High) using logistic regression, Random Forest, and XGBoost.
- Analyse how hashtags, video length, and music trends impact engagement.
- Perform sentiment analysis on video captions to assess its effect on likes, shares, and comments.
- Provide data-driven strategies to enhance TikTok content performance.

## 📌 Thought process steps
1. Define Project Scope & Key Questions
- Identify the main objectives and research questions.
- Working out the necessary variables that are required for subsequent visualisation, graph, relationships, statistics
- Dataset overview to understand data type of each column
- Convert and unify the data type in each column accordingly
- Drop columns with > 70% missing values or unnecessary columns for subsequent analysis
- Missing value imputation (mean, median, mode or 0)
- View statistics of each variable, histogram or bar plot for distribution
- Handle outliers if necessary
- Sentiment analysis:  
    + Clean word string (remove special characters, etc.)
    + Using python package to count sentiment score for further assessment
    + Plotting bar chart for word frequency
    + Plotting word cloud/ bubble graph for visualisation
    + Can do prediction of sentiment score based on engagement metrics such as like, share, comments, play etc.
    + Plot feature importance or shap score (shap package) to examine in what direction each factor impact the sentiment score?
- Engagement prediction:
    + Calculate engagement score: (like + share + comment)/ follow (or view) * 100
    + Use ML Regression method to predict how other factors such as hashtags, sentiment score, mention, number of followers, account popularity, likes, video duration, kind of music use impact the engagement rate
    + What model would show best evaluation metrics: F1-score, recall, precision, ROC-AUC
    + Can do model tuning to improve the performance
    + Feature importance to examine which factors account for the majority of the prediction, in what direction
 
