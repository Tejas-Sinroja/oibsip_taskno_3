# Car price prediction
Here the task is to train a machine learning model that can learn from the different factor of car and predict the selling price.

## workflow :

1. Data Acquisition: The car feature & price dataset consist 301 samples with 8 features and 1 target variable(price).
2. Data preprocessing and EDA : This is the crucial step in any machine learning project. Here handling the duplicate values, converting categorical variable into numerical, visulizing the data for analysis using python libraries and checking correlation between features.
3. Splitting the data and model training : model that are used here :  
   Linear regression  
   Random forest regression  
   Ridge regression  
   Lasso regression  
   Elastic net regression  
   Gradient boosting regression  
   XGBoost regression(best fit)  

4. Result : Comparing the final result and saving the best fit model. Here the XGBoost regression gives the highest R2 score : 0.9380
