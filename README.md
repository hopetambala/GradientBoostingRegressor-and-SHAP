Predicting NBA player salaries 🏀
=====
###### predicting NBA player salaries with a GradientBoostingRegressor and explaining the model predictions with SHAP

Notes
------
The full length code is available in the accompanying notebook and can be viewed on [nbviewer](https://nbviewer.jupyter.org/github/stevhliu/gradientboostingregressor-and-SHAP/blob/master/nbaplayers%20demo.ipynb). A writeup for this project can be found [here](https://towardsdatascience.com/building-a-gradientboostingregressor-to-predict-nba-player-salaries-65addc237f9d?source=friends_link&sk=4c3326640d3f6e1648ed339feb164bd2).

Summary
------
This notebook uses kaggle's NBA player dataset to guide users on model selection, validation and hyperparameter tuning. We also examine how we can explain the model's predictions with SHAP.

In this notebook, we train a gradient boosting regressor on NBA player statistics to predict their salaries. Next, we explain the different grid search strategies and cross-validation strategy to generate the best combination of hyperparameters to use with the model. In doing so, we are able to increase the model's prediction accuracy by 16%. Finally, we discuss the model outputs with SHAP values to explain the features that contribute to a player's salary and we summarize the impact of all features.

<p align='center'>
  <img width='700' src='https://github.com/stevhliu/gradientboostingregressor-and-SHAP/blob/master/SHAP.png' />
</p>
