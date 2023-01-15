# Introduction

This project aims to predict market prices using historical data. The dataset used in this project consists of hourly data including spot prices, wind and solar generation, demand and supply, and other relevant information.

# Data Cleaning and Preprocessing

The first step in this project was to clean and preprocess the data. This included removing missing values, handling outliers, and converting categorical variables to numerical using LabelEncoder.

# Feature Engineering
Next, various features were created to improve the performance of the model. These included lagged versions of the target variable, calculating the difference between wind and solar generation, and creating new features by multiplying and dividing existing variables.

# Model Building

The model was built using Random Forest. The model was trained on the training data and evaluated using mean absolute error.
# Backtesting

The model was then used to backtest a trading strategy where the position was opened on spot prices and closed on market prices.

# Conclusion

The model built using Random Forest was able to predict market prices with a decentof accuracy. The backtesting results showed that the strategy was profitable. However, it is important to note that this is a simplified example and in real-world trading, various other factors need to be considered before making any trading decisions.
