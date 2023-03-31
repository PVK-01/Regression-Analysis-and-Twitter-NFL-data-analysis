# Regression Analysis and Twitter NFL data analysis
## Introduction, and Aim
The main aim of the regression project is to explore different feature engineering and model selection methods that are specific to regression.
The target variable is price which is the price of the diamond, and the independent variables are carat, table, depth, x, y, and z. This project contains the following parts:
1) Using linear, lasso, ridge regression with hyper parameter tuning for both Mutual information based and F- score based methods.
2) Standardization vs non standardaized data
3) Polynomial regression with hyper parameter tuning
4) Using neural networks
5) Random forests with hyper parameter tuning and effects of each hyper parameter.

The main aim of the twitter NFL data analysis is to create a model that would use the tweets from the hashtags related to NFL matches and super bowl and fit a model that we explain some phenonmenon from the data.

## Data
The data for the twitter data anaysis is in XML form where the details related to each tweet are present. There are 6 hashtags and the data scorresponding to the 6 hastags are present.

Word cloud was used as an exploratory data analysis technique for the tweets data. Then the nfl game package from python was used to get other realtime details that happened in the match and to match them with our twitter tweets.

Then the main aim was that to predict the wininn gteam in the super bowl based on a text input. So, for this preprocessing was done.