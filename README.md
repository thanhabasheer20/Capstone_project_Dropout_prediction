# Predicting Student Dropout Likelihood in Personalized Learning Environments
## Overview

This project aims to predict student dropout likelihood in personalized learning environments using machine learning. It leverages student data to identify at-risk students and provide actionable insights for improving retention and student success.

## Problem Statement

Student dropout remains a significant concern in education, especially in personalized learning environments. Early identification of at-risk students is crucial for timely interventions and support.

## Objectives

1. Identify factors influencing student dropout in personalized learning.
2. Develop a predictive model for early identification of at-risk students.
3. Provide actionable insights to improve student retention and success.

## Data Description

**Source:** Kaggle ([https://www.kaggle.com/datasets/adilshamim8/personalized-learning-and-adaptive-education-dataset](https://www.kaggle.com/datasets/adilshamim8/personalized-learning-and-adaptive-education-dataset))

**Features:**

* Age
* Gender
* Education Level
* Course Name
* Time Spent on Videos (mins)
* Quiz Attempts
* Quiz Scores (%)
* Forum Participation (posts)
* Assignment Completion Rate (%)
* Engagement Level
* Final Exam Score (%)
* Learning Style
* Feedback Score (1-5)

**Target Variable:**

* Dropout Likelihood (Yes/No)

## Methodology

1. **Data Preprocessing:** Handling missing values, duplicates, skewness, and outliers.
2. **Exploratory Data Analysis:** Visualizing data patterns and relationships.
3. **Feature Engineering:** Encoding categorical variables and selecting relevant features.
4. **Model Selection:** Training and evaluating various machine learning models (Decision Tree, Random Forest, SVM, KNN, Gradient Boosting).
5. **Hyperparameter Tuning:** Optimizing the best-performing model (Random Forest).
6. **Model Evaluation:** Assessing model performance using accuracy, precision, recall, and F1-score.
7. **Model Deployment:** Creating a pipeline for automated prediction.

## Results

* The Random Forest Classifier achieved the highest accuracy (82.6%) in predicting student dropout likelihood.
* Key factors influencing dropout include time spent on videos, quiz scores, and final exam scores.
* SMOTE (Synthetic Minority Over-sampling Technique) effectively handled class imbalance, improving prediction accuracy for at-risk students.

## Recommendations

* Utilize the model and identified risk factors for early intervention.
* Offer personalized support based on student needs and learning styles.
* Address course-specific challenges to improve retention.
* Continuously monitor and update the model for optimal performance.

## Future Directions

* Explore more advanced feature engineering techniques.
* Investigate social and emotional factors impacting dropout.
* Develop a user interface for educators to access model predictions.
* Validate the model on a larger and more diverse dataset.



