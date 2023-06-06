What are missing values?
While collecting data by web scrapping or from other sources some values may be missing or may not be present and those values are called as missing values.
The reason behind missing values may be due to data corruption, observation error , user might have missed to provide data etc.

Types of missing values:
1)	Missing completely at random(MCAR):
Here the pattern of missing data cannot be predicted and it is missing completely at random.
2)	Missing at random(MAR):
Some pattern of the missing values can be identified and it is not missed completely at random.
3)	Missing not at random(MAR):
Some values are not missed at random but the user might have purposefully avoided giving the data.

Handling missing values using machine learning:
Filling missing values using Linear Regression
Step 1: Test data will be missing values
Step 2: Drop the null values and consider it as train data
Checking null values in train data.
Step 3:  Create x_train and y_train from the dataset
y_train is the rows of age with non null values
x_train is the dataset except age column with non null values
Step 4 : Building the model
Step 5: Creating X_test from Test_data
Step 6: Applying the model and predicting the missing values
Step 7: Replacing the missing values by predicted values:

