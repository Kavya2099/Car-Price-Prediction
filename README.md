# Car-Price-Prediction
**Car Price Prediction model created based on Regression algorithm** created with reference to **DataTalks.Club mlzoomcamp** course created using Google Colab


Dataset: https://raw.githubusercontent.com/alexeygrigorev/mlbookcamp-code/master/chapter-02-car-price/data.csv

# 1. **Data Preparation**

Reading the data from csv file and making initial data cleaning process of changing all texts to lowercase and removal of special characters and replacing spaces with underscore
      
# 2. **Exploratory Data Analysis**

* Checking for null values and examining important features.
* Feature engineering - adding new column to get better prediction.
* Using log expression to filter out  less important areas. Data visualization using histplot
      
# 3. **Model**
      
* Implementing **Randomforest regressor** without pipleine using numerical features   
* Implementing Randomforest regressor without pipleine using feature engineering     
* Implementing **Pipeline** with Randomforest regressor algorithm using both all features     
* Implementing Pipeline with **XGBRegressor** algorithm using both all features     
* Implementing XGBRegressor without pipleine using both all features
* Trying out **Crossvalidation**

      
 Picking the best model based on **Mean Absolute Error (MAE) and Mean Squared Error(MSE)**
 
 Predicting the price of the car using the final model with test data
 
 Will improve the model performance better in future!!
 
 
