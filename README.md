# 🏏 IPL First Innings Score Prediction

This project predicts **first innings scores** in IPL matches using various regression models including **Linear Regression**, **Random Forest**, and **Polynomial Regression**. The dataset spans matches from **2008 to 2023**, with manually added data from **IPL 2024** for prediction.  
✅ **Polynomial Regression (Degree 2)** was selected as the final model due to its strong generalization ability.

---

## 📌 Project Overview

The goal of this project is to **predict the total score in the first innings** of an IPL match based on current match features like runs, wickets, and overs.

- Multiple regression models were tested.
- Polynomial Regression (degree 2) emerged as the best performer.
- Random Forest showed overfitting on training data.
- Lasso and Ridge were explored but not selected.

---

## 📊 Dataset

- 📂 **Source**: [Kaggle - IPL Ball-by-Ball Dataset (2008-2023)](https://www.kaggle.com/)
- 🗂️ **Additional Data**: Manually added 2024 match data for score prediction

### 🔑 Key Features

- Match ID  
- Year  
- Batting Team  
- Bowling Team  
- Overs  
- Balls  
- Total Runs  
- Wickets  
- Run Rate  
- Last 5 Overs: Runs & Wickets  

---

## 🧠 Models Used

We experimented with several regression models:

- 🔹 **Linear Regression**
- 🔹 **Polynomial Regression (Degree 2)** ✅ *(Final Model)*
- 🔹 **Random Forest** – good training accuracy but poor generalization
- 🔹 **Lasso & Ridge Regression** – explored but not selected due to lower performance

### ✅ Final Model: Polynomial Regression (Degree 2)

- Better generalization on unseen data  
- Balanced training vs validation errors

## 📈 Visualizations
Key visual analysis includes:

- 📊 **Correlation Heatmap** – Understand feature relationships  
- 📉 **Run Distribution** – Explore team-wise performance trends  
- 🧪 **Model Error Plots** – Visualize training vs validation errors across folds

---

## 🔭 Future Work

- Include additional factors like **toss decision**, **venue**, and **pitch report**
- Experiment with **Gradient Boosting**, **XGBoost**, or **Neural Networks**
- Improve **feature engineering** and use **ensemble methods** to reduce overfitting in Random Forest

---

## 🏁 Outcome

This project demonstrates how statistical modeling and feature analysis can be used to forecast first innings totals in T20 cricket, providing valuable insights for teams, analysts, and sports enthusiasts.
