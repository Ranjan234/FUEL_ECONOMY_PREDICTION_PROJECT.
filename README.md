# FUEL_ECONOMY_PREDICTION_PROJECT.
Build a linear regression model to predict a vehicle's fuel efficiency. 

# The SITUATION
- You've just been as a Product Data Scientist for Consumer Reports Magazine,a trusted source for information on consumer products and services.
  
# The ASSIGNMENT
- Fuel economy is a major factor in the cost of owning a car, so they are studying the automobile characterstics that impact fuel economy for an upcoming article.
- You've been asked to build a regression model to predict fuel economy based on characterstics like the car's weight, model year, acceleration, and more.
  
# The OBJECTIVES
* Prepare and explore the data
* Split the data and build a multiple regression model
* Evaluate model test performance and interpret the model
* Challenge: Build a ridge regression model and compare the results

# OBJECTIVE: 1- DATA PREP & EDA
- Import Data,Filling Missing Values, EDA
- Read in the auto-mpg.csv dataset, and check datatypes and columns for missing or unusual values
- Convert ‘origin’ to a categorical feature
- Calculate summary statistics for each of the numeric columns in the dataset including min, max and mean, then build a histogram of the target variable (‘mpg’)
- Explore relationships between the features and the ‘mpg’ column, and use scatterplots and build a correlation heatmap. Which column is most strongly correlated with ‘mpg’?

 # OBJECTIVE -2: Split the data and build a multiple regression model
- Split the data into train and test, then then set up a validation scheme of your choice- Fit a baseline regression model using the feature with the strongest correlation to the target (‘mpg’)
  
-Fit a multiple regression model. Perform any feature selection and feature engineering necessary, fixing any violated assumptions along the way

# OBJECTIVE:3 - TEST & INTERPRET MODEL
- Score your final model on the test set, calculating both R2 and MAE. If your test R2 is less than 8, revisit the modelling process
- Interpret your model. What impact does a one-year increase in model year have on the predicted mileage?
- BONUS: Repeat the modelling process using ridge regression. How much better was the ridge model than traditional regression, if at all?
