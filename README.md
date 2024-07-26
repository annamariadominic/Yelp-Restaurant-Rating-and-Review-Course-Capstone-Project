# Data Analysis of Restaurant Ratings

## Overview
This repository contains the capstone project for the course DS-GA 1001 Introduction to Data Science. The project, undertaken by Team S.H.A.R.P, focuses on analyzing restaurant ratings using various data science techniques to derive actionable insights. The analysis leverages data provided by Yelp, including business, review, and user datasets. The goal is to understand and predict business popularity, quality, and operational status.

## Team Members
- Siri Desiraju (N14355365)
- Hoa Duong (N11455685)
- Anna Dominic (N18538396)
- Ridhika Agrawal (N13428967)
- Palak Bansal (N11465209)

## Project Structure

### 1. Introduction
The introduction section provides an overview of the dataset and the motivation behind the project. With the rise of online review platforms, understanding the impact of customer reviews on business outcomes has become crucial. The Yelp dataset used in this project includes information on 150,346 businesses and around 7 million reviews.

### 2. Data Preprocessing
Data preprocessing involved handling missing values, extracting relevant features, and performing exploratory data analysis. Key features considered include business hours, customer ratings, and additional attributes such as takeout and delivery options. Sentiment analysis was performed on review texts using the Vader algorithm.

### 3. Inference Questions
The project addresses whether certain restaurant features can predict their popularity and operational status. Using the Mann-Whitney U Test, significant relationships were found between features and business outcomes.

### 4. Prediction Questions
A neural network model was employed to predict restaurant ratings based on various features. The model achieved a training accuracy of 54% and a testing accuracy of 52%.

### 5. Classification Questions
The likelihood of restaurant closures was predicted using neural networks and logistic regression models. K-means clustering was also applied to segment the data. The models achieved an accuracy of around 74% on both training and testing data.

### 6. Summary and Conclusions
The analysis reveals significant insights into factors influencing restaurant ratings and closures. While predictive models for ratings were less accurate, closure predictions were more reliable. The findings can help business owners understand key factors affecting their operations and make informed decisions.

### 7. Appendix
The appendix includes detailed exploratory data analysis, data preprocessing steps, and additional visualizations supporting the project findings.

## Files
- **Project Report:** Detailed report of the project findings (PDF)
- **Code:** Python scripts used for data preprocessing, analysis, and model building
- **Data:** Yelp dataset (linked due to large size)

## Acknowledgements
We would like to thank the instructors and teaching assistants of DS-GA 1001 Introduction to Data Science for their guidance and support throughout this project. Additionally, we acknowledge Yelp for providing the dataset used in this analysis.
