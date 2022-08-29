# NBA Draft Prediction

## Overview
This project analyzes the data from College Baseketball Players Dataset in Kaggle. The data consists of detailed college players stats from 2009 - 2021, and players stats from 2022. Another data contains the info of college players who were drafted to NBA teams in both round 1 & 2.

Based on dataset, I am using machine learning models to determine the college players' quality for for draft round 1 and draft round 2.

## Data Understanding
The College Basketball Players 2009-2021 (`CollegeBasketballPlayers2009-2021.csv`) has the detail statistics of each college players from 2009 to 2021. We combined it with DraftedPlayers2009-2021(`DraftedPlayers2009-2021.xlsx`), so we have the draft pick info if the players were drafted to the NBA teams.

The College Basketball Players 2022 (`CollegeBasketballPlayers2022.csv`) has the detail statistics of each college player from 2022, which we have tested on our final model.

## Methods
This project tests various machine learning models, including Logistic Regression, Decision Tree, K-Nearest Neighbor, Random Forest, Extra Trees, and various other ensemble methods. I first created the baseline models with basic parameters to analyze how the predictors performed. I further optimize by combining the tuned models into various ensemble models such as Stacker Classifier and AdaBoosting.

## Conclusions
After many tests, the best model is GradientBoosting from sklearn.ensemble. The best model reached 77% accuracy scores on testing data.

![final_model.png](/Users/brianchoi/Documents/Data_Science/Projects/NBA_Draft_Prediction/final_model.png) 