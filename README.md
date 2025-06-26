# E-commerce-Return-Rate-Reduction-Analysis uning Python, SQL and Power BI
First creating a data set that contains the data related to ecommerce return data which can help us to find the risk score probability.
First observe the dataset and change the datatype to the columns order_date, category and returned.
Then create a new note book in python and use the dataset and handled the missing values in the dataset and build the logistic regression model in Python.
Finding the return risk score based on the return data and nammed it as risk probability.
Predicting the return probability.
https://www.kaggle.com/code/nandukumar07/return-risk-probability.
created a new column for the high risk products which are greater than (Return_risk_score> 0.7).
Exported the High risk Products data into the CSV file.
Importing the data in to mysql and created a column output for the return percentage for the products and grouped by category and repeted the same for the products grouped by Geography.
Created a dashboard for the Risk Rate data by importing the data into power BI desktop.
Create calculated columns for the Total Orders,Return rate, Revenue Lost, Total Revenue and created a new column for the Order Month from the Order_date.
Create calculated columns for the High Risk = Return_Probability > 0.7 else Low Risk and High Risk Percent.
Built the KPI cards for Total orders, High Risk %, Return probability and delivery time days.
Built the vbar chart for Return probability vs Category and Return % vs Supplier.
Built the Pie Chart to show distribution with the Marketing Channel.
Created the slicers for the Category, Supplier, High Risk, Geography and Marketing Channel.
Created a new page with the Product details and added the drill-through section with Category.
