# NBAFreeAgentPredictor
Using Machine Learning to predict the 2020 NBA MVP Winner and Votes won by top players.

Scraped and cleaned 36 years of NBA data using Pandas in Python. 

Used Random Forest Regression with (12 features, 50 estimators) to predict that Giannis will win 2020 MVP with 786 votes. 
Correctly predicted that Giannis would win 2019 MVP (model predicted 764 votes, in reality he had 741 votes).

Tried using several different models and calculated Mean Squared Error for each model (and performed hyperparameter tuning) to determine the best model (Random Forest Regression) for this use case. 
