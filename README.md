Code Descriptions
Program 1: To demonstrate Data Manipulation using Pandas in Python

Reading the data.csv file using read_csv() and showing basic statistical description of the data using describe().
Checking if there are any null values in the data using. If there are null values, replacing the values with mean of the column.
Aggregating the “Duration” and ‘Pulse” data using agg().
Displaying data that has “Calories” column values between 500 and 1000.
Displaying data that has “Calories” column values less than 500 and greater than 1000.
Displaying all the columns except “Maxpulse” using loc().
Deleting the “Maxpulse” column from the dataframe using drop().
Converting the column data type to int data type of “Calories” column using astype().
A scatter plot is drawn for the columns “Duration” and “Calories”.
Program 2: To demonstrate Linear Regression on the Salary_Data.csv file.

Reading the data.csv file using read_csv() and showing basic statistical description of the data using describe().

Entire data is spilt into training and testing data using train_test_splot() method imported from sklearn module.

Linear regression model is imported from sklearn and loaded into “regressor” object. Then the training data and test data is used to tune the weights of the model.

Using predict() method, values are predicted for the test data.

Mean squared error is calculated between the predicted and actual values.

Scatter plots are drawn for training and testing data.

video file [2091840a-c241-4f7e-92bb-37ac649a04c2.webm](https://github.com/user-attachments/assets/5ea78beb-5112-460c-89a9-d2de1fb5eb05)
