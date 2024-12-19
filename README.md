Quick attempt at the drivendata.org challenge to predict cognitive scores from social determinants of health.

My approach was to train a few different regression models (lightgbm) based on which years of questions were filled in, and which target years were being predicted for.

I got a RMSE of 38.34 in 3 submissions with this method, giving me a rank of #30 on the public leaderboard as of 19/12/2024. I only made one day of submission attempts, with more time I would like to have expanded more on my EDA and manual inputing of missing values, extra constructed features also likely would have helped. More investigation into how effective my intuitions actually were for improving the predictors would also be a high priority with more time invested.