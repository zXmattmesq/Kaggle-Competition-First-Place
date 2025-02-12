Stock Purchase Decision Classifier
Overview
This project aims to predict whether a stock's value will increase or decrease over a year, assisting traders in making informed buy or hold decisions. The classification model was developed for a competition focused on stock market predictions, where it achieved first place on the private leaderboard and third place on the public leaderboard.

Project Description
The objective is to classify stocks into two categories:

Class 1: Stocks whose value is expected to increase over the year (recommended to buy at the start of the year and sell at the end).
Class 0: Stocks whose value is expected to decrease over the year (not recommended to buy).
The dataset includes various features related to stock performance and sector information. The target variable is the 'Class' label indicating the stock's performance category.

Model Development
The project employs a combination of machine learning models to enhance predictive performance:

Neural Network: A feedforward neural network with hyperparameter tuning using Keras Tuner.
Random Forest Classifier: An ensemble learning method using multiple decision trees.
Gradient Boosting Classifier: An ensemble technique that builds models sequentially to reduce errors.
The final predictions are generated using a stacking ensemble method that combines the outputs of the individual models.

Results
The model achieved the following performance:

Public Leaderboard: 3rd place
Private Leaderboard: 1st place
Score:0.69
The primary evaluation metric was the Area Under the Receiver Operating Characteristic Curve (AUC-ROC).
