# Airbnb-New-User-Bookings

## Dataset Resource
[Kaggle Competition](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/overview)

## Evaluation
The evaluation metric for this competition is NDCG (Normalized discounted cumulative gain) @k where k=5. The fomula is provided in the above link.  

## Final score on Kaggle Leaderboard
* Private: 
  * NDCG score: 0.88472 
  * Rank: 166th out of total 1412 (Top 11.7%)
* Public: 
  * NDCG score: 0.87935 
  * Rank: 197th out of total 1412 (Top 13.9%)
  
 Date: 04/06/2020
  

## Problem
In this recruiting competition, Airbnb challenges you to predict in which country a new user will make his or her first booking.

## Dependency Library
* Numpy
* Pandas
* Seaborn
* Matplotlib
* scikit-learn
* xgboost

## Work Flow
* EDA
* Preprocess data
* Model
  * Gaussion Naive Bayes
  * Logistic Regression
  * Decision Tree
  * Random Forest
  * Grandient Boosting
  * XGBoosting
* Parameters Tuning
* Model Decision (XGBoosting) + Processing web session log for users (sessions.csv)
* Build Final Model and make submission file
