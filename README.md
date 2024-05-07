# Car_price-Regression
This is for practice

Here we have a linear regression project based on the car price dataset.
In this project, the goal is to estimate the price of the car.
The dataset is a lightweight dataset that has 301 rows and 9 columns.
 columns:
'Car_Name',
 'Year',
 'Selling_Price',
 'Present_Price',
 'Kms_Driven',
 'Fuel_Type',
 'Seller_Type',
 'Transmission',
 'Owner'

Challenges:
One of the challenges we are facing is that the model only understands the number, so we have to convert the object format columns to the numeric format.
Another challenge is handling outliers, which we handled a series of commands, if outliers are not handled, it may cause the model to deviate.
In order to put our data in the same range and have the same data distribution, we have to normalize our data.
In order to increase the accuracy of the model, we integrated a series of features that had the greatest impact on the target, and in the end, our model reached an accuracy of 96%.
Now we will define a function that, if new data is entered into the model, it will perform all operations of converting string to number and normalization.
