# Sentiment Analysis

## Introduction
The number of data, both quantitative and qualitative, increases dramastically in the era of big data. In E-commerence industry, more and more reviews on products can be made more conveniently. Hence, it is extremely costly, if not impossible, for company to go through every review one by one manually to gain insights on the sentiment towards their products. Therefore, having a machine learning tool to analysis the huge amount data systematically and automatically could boost the company's efficieny and become essential in this era. <br> <br>
In this project, we are going to develop a machine learning model based on real-life data to help us perform sentiment analysis. The dataset consists of a nearly 3000 Amazon customer qualitative reviews, star ratings, date of review, variant and sentiment of various Amazon Alexa products.

## Acknowledgement
The dataset used in this project is retrieved from Kaggle dataset 'Amazon Alexa Reviews' contributed by Manu Siddhartha and Anurag Bhatt. You may access the dataset by https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews. <br> <br>
Besides, this project is inspired by Ryan Ahmed in the Coursera's guided project 'NLP: Twitter Sentiment Analysis', which can be accessed by https://www.coursera.org/projects/twitter-sentiment-analysis. On top of the skeleton provided, I have made the following modifications in the project:
- commenting on exploratory data analysis
- further investigating on the relation between review lengths and sentiments
- including logarithmic review length as an input feature
- adapting Logistic Regression and k-Nearest Neighbor instead of Naive Bayes
- splitting dataset into validation set also
