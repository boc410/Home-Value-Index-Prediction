# Home-Value-Index-Prediction
![Houses_thumbnail](https://github.com/user-attachments/assets/d0e1ad60-5c12-4945-80ef-1898376008ff)
A predictive model for the short-term change in home price value in metro areas across the United States.

Market data from Zillow, job opening statistics from the Bureau of Labor Statistics (BLS), and Gross Domestic Product (GDP), population and personal income statistics from the Bureau of Economic Analysis (BEA) were utilized to train and test a variety of models.

The final Random Forest Regression model was able to use 3.5 years of training data across 471 metro areas to predict the home value percentage change with a mean absolute error of .24% (less than 40% of one standard deviation) on the validation dataset covering July 2022 – December 2023. Additionally, the model correctly predicted a decline in home value 90.4% of the time, when there was a true decline in home value. The model correctly predicted an increase in home value 83.3% of the time, when there was a true increase in home value.
