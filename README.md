# Predicting-Sale-Price-of-Bulldozers
we're going to go through an example ML project with the goal of predicting the sales price of bulldozers.


# 1. Problem definition
how well can we predict the future sales price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

 
# 2. Data
The data is downloaded from the Kaggle Bluebook for bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data.
There are 3 main datasets:
* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to * create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.


# 3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
For more on the evaluation of this project, check: www.kaggle.com/competitions/bluebook-for-bulldozers/overview/evaluation
Note: the goal for most regression evaluation metrics is to minimize the error. For example, our goal for this project will be to build a ML model which minimises RMSLE.

# 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset. Feature importance seek to figure out which different attributes of the data were most important when it comes to predicting the target variable (SalePrice).
