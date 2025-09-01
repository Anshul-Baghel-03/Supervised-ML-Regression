# 📊 Supervised ML Regression – Yes Bank Stock Closing Price Prediction  


![Yes Bank Logo](https://upload.wikimedia.org/wikipedia/commons/d/d1/Yes_Bank_Logo-01.png)

---

## 📌 Project Summary  
Yes Bank was a very reputable bank till 2018. After 2018, the bank came under the umbrella of risk-inflated banks because of the fraud case by Rana Kapoor.  

This project would help not only Yes Bank but also other banks who want to predict their future stock prices and reduce uncertainty. By leveraging Machine Learning — especially Linear Regression and other regressors — we can provide insights that help firms sustain in the market.  

The dataset includes monthly Open, Close, Low, and High prices of Yes Bank stock, which were used to train the models and make predictions.  

---

## 🛑 Problem Statement  
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this, it was interesting to analyze how the scandal impacted the stock prices and whether predictive models could provide accurate forecasts.  

The dataset contains monthly stock prices (Open, High, Low, Close) since the bank’s inception. The main objective is to predict the **closing stock price of the month**.  

---

## 📊 Variable Description  

- **Date**: Month and year for a particular price.  
- **Open**: Price at which the stock started trading.  
- **High**: Highest price traded during a period.  
- **Low**: Minimum price traded during a period.  
- **Close**: Final trading price of the stock (dependent variable).  

---

## 🎯 Objective  
The objective of this project is to predict the Yes Bank stock closing price of the month through the following steps:  

1. Loading the data into a DataFrame  
2. Cleaning the data  
3. Exploratory analysis and visualizations  
4. Feature manipulation and selection  
5. Train-Test split  
6. Model implementation  
7. Selecting the best model  
8. Model deployment  

---

## 📌 Importance of Closing Price  

- **Investors**: Used to evaluate company health, market value, and performance.  
- **Traders**: Helps in making trading decisions and maximizing returns.  
- **Analysts**: Essential for calculating metrics like market capitalization and trading volume.  

---

## 🤖 Models Implemented  

- Linear Regression  
- Lasso Regularization  
- Ridge Regularization  
- Elastic Net  
- Random Forest Regressor  
- XGBoost Regressor  

✅ **Best Performing Model**: **Ridge Regularization**  
- Training Accuracy: 95%  
- Testing Accuracy: 94%  
- RMSE: 0.219 (untuned)  
- After hyperparameter tuning: Training 97%, Testing 94%  

📌 **Key Insights**  
- Features **High, Low, Open** are strongly correlated with **Close**.  
- Feature **Low** has the highest importance.  
- Evaluation metrics used: **R² Score** and **RMSE**.  

---

## 📈 Results  
The Ridge Regularization model proved to be the most effective in predicting Yes Bank’s closing stock prices.  
This demonstrates how supervised learning algorithms can be applied to financial data for better risk management and fraud impact analysis.  

---
