# PracticalApplicationAssignment11.1UsedCars
Practical Application Assignment 11.1: What Drives the Price of a Car?


## Data Summary
After loading the dataset, we found that there were missing values in the dataset. 
We decided to drop the missing values to ensure the quality of the data. 
We also found that there were some rows where the price was 0, which is not possible. We dropped these rows as well. 
The summary statistics of the dataset show that the average price of a used car is around  1 and a maximum price of  50,000. 
The dataset contains 426,880 entries and 18 features related to various aspects of used vehicles. 
Features include identifiers (like id and VIN), vehicle characteristics (manufacturer, model, year, cylinders, etc.), condition, and transactional details (price, title_status). The dataset also contains features like odometer, transmission, drive, fuel, and type of vehicle. These features will be used to predict the price of a used car.
The dataset includes a wide range of years, from 1900 to 2022. There are missing values in several important columns like year, manufacturer, model, condition, and odometer. The price variable, which is our target variable, has a wide range, from 0 to over 3 billion, suggesting possible outliers or data entry errors. Some entries in the initial rows have missing values across multiple field The dataset contains a mix of numerical and categorical variables, which will require preprocessing before modeling.



## Data Preparation

After our initial exploration and fine tuning of the business understanding, it is time to construct our final dataset prior to modeling. Here, we want to make sure to handle any integrity issues and cleaning, the engineering of new features, any transformations that we believe should happen (scaling, logarithms, normalization, etc.), and general preparation for modeling with sklearn.


## Data Cleaning: 
Address missing values and filter out unreasonable or incorrect entries (e.g., extremely high prices, very old vehicle years).
Feature Selection: Decide which features are relevant for the price prediction model.
Exploratory Data Analysis: Further analyze the distribution of key variables and their relationships.


### Evaluation

With some modeling accomplished, we aim to reflect on what we identify as a high quality model and what we are able to learn from this.  We should review our business objective and explore how well we can provide meaningful insight on drivers of used car prices.  Your goal now is to distill your findings and determine whether the earlier phases need revisitation and adjustment or if you have information of value to bring back to your client.

### Conclusion

In this notebook, we have explored the data, cleaned it, and built a model to predict the price of used vehicles. We have used multiple regression models and evaluated them using mean squared error and R2 score. We have also used cross validation and hyperparameter tuning to improve the models. Finally, we have saved the best model and made predictions on the test set. We have also analyzed the feature importances and identified the manufacturer with the highest average price.
Ridge regression model was the best model with the lowest mean squared error and highest R2 score.
The most important features for predicting the price of a vehicle were the year, odometer, and the manufacturer.
The manufacturer with the highest average price was tesla.


