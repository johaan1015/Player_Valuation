# Player-Valuation

## Overview

This project aims to predict the market value of football players using different machine learning models. 
The project uses player data scraped from a popular football website sofifa and cleans and preprocesses the data using various techniques.
The cleaned data is then used to train different machine learning models to predict the market value of each player.

## Project Files

- `work/`: Contains all the scratch work for the project, including scraping, EDA, and modeling.
- `player-valuation.ipynb`: The final code for the project that includes all the preprocessing, modeling, and evaluation steps.
- `raw-scrape`: Raw scraped data containing player information.
- `scrape-final`: Cleaned data after all preprocessing steps.

## Data Sources

The player data used in this project is scraped from a popular football website sofifa using Python's BeautifulSoup library. 
The data includes player statistics, such as age, position, club, height, weight, and performance metrics.

## Data Cleaning and Preprocessing

The raw scraped data is cleaned and preprocessed using various techniques, including:

- Handling missing values by imputing them with appropriate values.
- Handling categorical variables by one-hot encoding them.
- Removing outliers and irrelevant variables.

## Modeling

The cleaned data is split into training and testing sets, and different machine learning models are trained and evaluated on the data. The models include:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Polynomial Regression
- Lasso, Ridge

The performance of each model is evaluated using various metrics, including Root mean squared error (RMSE),AIC, BIC and R-squared (R2).

## Conclusion

The project demonstrates the use of different machine learning models to predict the market value of football players. 
The best performing model is selected based on the evaluation metrics, and it can be used to predict the market value of new players or to
compare the market value of existing players. The project can be extended by including more player statistics or by using more advanced machine learning models.
