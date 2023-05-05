# Ohile
Test Assessment


## Load Data
Load the data(Sheet1 & Sheet3) from the Excel file into two dataframes using the read_excel function from the pandas library.

## Transform Data 
X: DataFrame that contains every 10th row from sheet1 ,You can use the iloc function to select every 10th row from Sheet1
<br>
y: sheet3 

## Splitting DataSet
Splitting the X, y such that the test_size of 20% and random_state=1 into X_train, X_test, y_train, y_test

## Feature Scaling 
Feature scaling performs for better accuracy of the model 
<br>
Used Standard Scaler

## Train the Model
Create a linear model for predicting dependent variable y from X.
<br>
Predict the values Va, Vb ,Vc from the independent variables a,b,c,q,d.

## Metrics
Evaluate the models performance with the y_test,y_predict such as 
### mean_squared_error
### mean_absolute_error
### r2_score

## Make Sample Predictions 
### optional
Test the model with some inputs of the sheet1 contains the inputs to a correction system.
