# Spotify Recommendation System
=============================

## Introduction
This repository contains a Spotify recommendation system that uses various machine learning models to predict whether a user will like a song or not. The dataset used in this analysis was collected from the Spotify API, which provides access to a vast repository of music metadata.

# Models
## XGBoost
AUC-ROC: 0.974 Likelihood of liking: 0.082

## Neural Network
Likelihood of liking by user: 0.290

## Ensemble Models
### Random Forest
Accuracy Score: 0.9230769230769231
ROC AUC Score: 0.9236842105263158
### Extra Tree Classifier
Accuracy Score: 0.9487179487179487
ROC AUC Score: 0.9486842105263158
### Bagging Classifier
Accuracy Score: 0.8717948717948718
ROC AUC Score: 0.8723684210526317
### AdaBoost Classifier
Accuracy Score: 0.8717948717948718
ROC AUC Score: 0.8723684210526317
### LightGBM Classifier
Accuracy Score: 0.8717948717948718
ROC AUC Score: 0.8723684210526317
---

# Conclusion
This repository demonstrates the effectiveness of various machine learning models in predicting whether a user will like a song or not. The results show that the XGBoost model performed well in terms of AUC-ROC and likelihood of liking. The ensemble models also showed promising results, with the Random Forest model performing well in terms of accuracy and ROC AUC score.
