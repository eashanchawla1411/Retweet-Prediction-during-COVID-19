# Retweet-Prediction-during-COVID-19

**Note: This is a work in progress. The work done till now is being built upon**


My work on this problem is adapted from ACM 29th ACM International Conference on Information and Knowledge Management (CIKM2020) Analytics Retweet Prediction challenge (https://www.cikm2020.org/covid-19-retweet-prediction-challenge/). The goal is to “predict the popularity of COVID-19-related tweets in terms of the number of their retweets,” meaning, predict a tweet’s popularity (as measured by its retweets) via other factors related to it. 

**Steps Followed:**
1. Exploratory Data Analysis
2. Data Preprocessing to remove columns that are not required, stop words. Duplicates also handled here. 
3. Normalization of numerical columns
4. Model Training and Testing

**Following improvements can be (and are in the processing of being) made:**
1. Hyperparameter tuning to tune parameters of models built. 
2. Instead of a train test split, we could do cross validation to 
  a. Select a model out of the various models trained. 
  b. Tune hyperparameters
