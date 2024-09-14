# IPL_First_Innings_Score_Prediction
This project predicts IPL first innings scores using Linear,Random forest and Polynomial Regression models. The dataset covers IPL matches from 2008 to 2023, and the models are used to predict scores for the 2024 season. Polynomial Regression (degree 2) was selected for its strong generalization performance.

# Project Overview
The goal is to predict the first innings total score in an IPL match using features such as runs, wickets, and overs. The project experimented with multiple regression techniques, with Polynomial Regression (degree 2) being the most successful model in terms of generalization. Random Forest was also tested but showed signs of overfitting.

# Dataset
- The dataset used is sourced from Kaggle: IPL Ball-by-Ball Dataset (2008-2023)
- Some manually added data from 2024 IPL to prediction of unseen data. 

# Key features include:

- Match ID,
- Year
- Batting and Bowling Teams
- Overs
-  Balls
- Total Runs
- Wickets
- Run Rate
- Runs/Wickets in Last 5 Overs

# Models Used
We tested the following models:

- Linear Regression
- Polynomial Regression (degree 2)
- Random Forest: Though it performed well on the training data, it overfitted, leading to poor generalization on unseen data.
- Lasso and Ridge Regression (Explored but not chosen)

- Final Model: Polynomial Regression (degree 2)
Polynomial Regression (degree 2) was chosen as the final model because it performed better on unseen data, with a good balance between training and validation errors.



- Example Predictions:

Actual Runs	   :147

Predicted Runs : 142

# Visualizations
Key visualizations include:

- Correlation Heatmap: Displays feature relationships.
- Run Distribution: Shows IPL team performance over the years.
- Model Error Plots: Visualizing the training and validation errors across folds for different models.


# Future Work
-  In the future, We can improve the accuracy of the model used in this project. Factors like toss and pitch can be considered for the prediction.
- To improve further, we could explore advanced models like Gradient Boosting or Neural Networks. Also, better feature engineering or the use of more complex ensembling methods could reduce overfitting in the Random Forest model.
