# IPL-Score-Prediction
This model attempts to predict the first inning score of an IPL match.


Background:  In a cricket match, we often see the prediction line showing the probability of the team winning based on the current match situation. We all have often saw score line showing the projected score of the innings too.Inspired from that and to explore the importance and possibilities of implementation of statistics or in particular, Machine Learning (ML) in Sports I attempted to predict the first inning score of an IPL match. 

Objective: The objective of this problem is to develop a machine learning model that can predict the total score of a cricket team at the end of the first innings, given the current match situation.

To achieve this goal, we have used a Regression approach, which is a Supervised Learning technique in Machine Learning.

Data: The dataset used in this project contains ball by ball information of the matches played between IPL Teams of Season 1 to 10, i.e. from 2008 to 2017.
The data for this problem consists of a dataset with columns including match ID, date, venue, batting team name, bowling team name, batsman, bowler, runs scored by team, number of wickets fallen, number of overs bowled, runs scored in the previous 5 overs, number of wickets fallen in the previous 5 overs, strike rate of the striker and non-striker, and total runs scored by batting team at the end of the first innings.

Evaluation: The performance of the machine learning model will be evaluated using a suitable metric such as mean squared error (MSE), root mean squared error (RMSE) and R-Squared value. The model will be trained and evaluated on the dataset. The goal is to minimize the error between the predicted score and the actual score of the batting team at the end of the first innings.

Outcome:   The best model achieved in this project is Random Forest with an R2 score of 93%.
