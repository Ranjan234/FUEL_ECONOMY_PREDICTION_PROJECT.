# FUEL_ECONOMY_PREDICTION_PROJECT.
Build a linear regression model to predict a vehicle's fuel efficiency. 



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
