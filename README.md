# StarbucksCapstone
This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.

## Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers

### 1. Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

- pandas
- numpy
- math
- json
- pickle
- datetime
- xgboost
- sklearn.model_selection (train_test_split module)
- sklearn.metrics (roc_auc_score)
- sklearn.linear_model (Ridge)
- sklearn.model_selection (GridSearchCV, cross_val_score)
- matplotlib

### 2. Project
Since Starbucks launched their rewards program, Starbucks have sent users offers from time to time. After a certain period of time, Starbucks is curious about how users reacted to the offers. For customers who complete the offers after viewing the offers, Starbucks would like to keep sending them offers to develop customer loyalty. For customers who complete transactions regardless of the offers, Starbucks may stop or reduce the frequency of sending them offers because they know the customers will purchase anyway. For customers who never make any purchases after the offers are sent, Starbucks may stop sending them offers. This is a real-life marketing strategy study based on simulated data set that mimics customer behavior on the Starbucks rewards mobile app.

Problem Statement:
What drives Starbucks user to respond to an offer?

Conclusion:
The model indicates that income is the biggest predictor of the effectiveness of an offer. Whether the offer is posted on social media and tenure of a member are the two next important features. Offer duration is also an important feature but relatively unimportant compared with the other three.

### 3. File Descriptions
This repo contains 4 files. 
Code: Starbucks_Capstone_notebook
Data: portfolio.json, profile.json and transcript.json

### 4. Licensing, Authors, Acknowledgements, etc.

Data for coding project was provided by Udacity.
