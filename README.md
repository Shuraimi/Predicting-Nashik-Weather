# Predicting Nashik Weather 

Predicting the weather of Nashik is a multi class classification problem. In this project, the goal is to predict the weather of Nashik based on data of previous two years.

The classes are :-
* clear-day ☀️
* Rain 🌧️ 
* Partly-cloudy-day ☁️

This problem was a hosted playground competition on kaggle and I got 36th rank out of 54 (since this was my first competition😅 and also this was a small community competition).

Here's the link to competition 
(https://www.kaggle.com/competitions/ml-olympiad-nashik-whether)

<img src="https://github.com/Shuraimi/zero-to-mastery-ai-ml-course/blob/main/images/6-step-ml-framework.png" />

## Steps I followed:-

1. **Problem Definition** - Predicting whether the price of a bulldozer given the features.
2. **Data** - Downloaded and imported the data into a DataFrame from Kaggle.
3. **Evaluation** - The evalutaion metric is macro f1 score.
4. **Features** - Defined a data dictionary which defines what a feature means.

<img src='https://github.com/Shuraimi/zero-to-mastery-ai-ml-course/blob/main/images/sklearn-workflow.png' />

5. **Modelling** - This includes
   * Splitting data into features(X) and labels(y)
   * Splitting the features and labels into train and validation splits because test dataset is not available 
   * Choosing the right model/s
   * Instantiating a model
   * Fitting the model/s
   * Evaluating the model
   * Choosing the model with best performance
   * Hyperparameter tuning for better performance of model
   * Evaluation report at the end


After the features section, we import all the necessary libraries, get the data ready and perform Exploratory Data Analysis (EDA) to learn more about the data.

## What I learnt from this project?

* I learnt how to take part in ML competitions on kaggle.
* Learnt how to choose models to try and also select the best model based on its performance on the evaluation metric.
* Fine tune the model by performing hyperparameter tuning using `RandomizedSearchCV` AND `GridSearchCV`.
* Make a custom scorer using`make_scorer` because macro f1 score is not available in `cross_val_score`
* At last, create a submission file with your predictions on the best trained model and submit to kaggle.

This is my first project, and I've learned many things while building it. I'm still eager to learn more through building projects and competing in Kaggle competitions.
