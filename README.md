Dataset Overview:
Features:
Date (1987 to 2023)
Average Earning of the people in the US
GDP of the US
Mortgage rates
Population of the US
Unemployment rate in the country
Target Variable:
CSUSHPISA
Methodology
Data Loading and Preprocessing:
Loaded the dataset from 'US_price_data.csv'.
Converted the 'DATE' column to datetime format.
Set 'DATE' as the index for time series data.
Selected relevant features and ensured there were no missing values.
Missing values are filled by using interpolate method.
Data Splitting:
Split the data into training and testing sets (80% training, 20% testing).
Linear Regression Model:
Utilized the scikit-learn library to implement a Linear Regression model and 
Trained the model using the training dataset.
RandomForestRegressor Model:
Utilized the scikit-learn.ensemble to implement a RandomForestRegressor model and 
Trained the model using the training dataset.
Model Evaluation:
Evaluated the model performance on the testing dataset.
Calculated Mean Squared Error (MSE) and R-squared.
Visualization:
Plotted a scatter plot to visualize the relationship between actual and predicted prices.
Results
Mean Squared Error (MSE):
The model achieved a MSE of {mse1,mse2} on the testing dataset.
R-squared:
The R-squared value, a measure of how well the model explains the variance in the target variable, is {r2,r3}.
Conclusion
The linear regression model and RandomForestRegressor Model provides insights into the relationship between the selected features and the Home prices.
