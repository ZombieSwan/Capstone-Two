# Predicting IPO Excess Returns: A Sentiment Analysis Approach

### Overview:
This project explores the prediction of IPO excess returns for 2019-2021 using various predictor variables, focusing on the potential of Twitter sentiment scores related to tech giants like Amazon, Apple, Google, Microsoft, and Tesla.

### Data Sources:
University of Florida's IPO Database: Historical IPO data covering variables like the type of IPO, the year of founding, etc.
Kaggle - Company IPOs (2019 - 2021): IPO offer price dataset.
Kaggle - Tweets about the Top NASDAQ Companies (2015 - 2020): Raw tweets data for sentiment analysis.
Yahoo Finance API: Stock price data.

### Project Structure:
Data Cleaning and Preprocessing: Ensuring data quality and completeness.
Feature Selection: Identification of key predictor variables.
Model Selection and Training: Lasso Regression and Random Forest Regressors utilized.
Hyperparameter Tuning: Optimization with RandomizedSearchCV.
Validation: Testing the optimal models on test data.

### Key Findings:
Random Forest showcased varying accuracy across different time horizons.
Sentiment scores were influential but inconsistent predictors.
'Age at IPO' and 'IPO Price' emerged as crucial predictors.

![image](https://github.com/ZombieSwan/Capstone-Two/assets/128863293/c01f9998-b210-45e3-a06b-cfc6acda1398)


### Conclusions:
Sentiment data combined with traditional financial indicators can predict IPO excess returns to a certain extent. However, accuracy tends to decrease for longer-term horizons.

### Future Directions:
Dataset expansion for more IPOs and broader Twitter data.
Advanced sentiment analysis techniques for better accuracy.
Emphasis on short-term prediction due to diminishing long-term accuracy.

