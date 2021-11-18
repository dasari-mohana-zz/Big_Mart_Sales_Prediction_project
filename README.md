# Big_Mart_Sales_Prediction_project

# Data Description:

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim of this data science project is to build a predictive model and find out the sales of each product at a particular store.

Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

The data has missing values as some stores do not report all the data due to technical glitches. Hence, it will be required to treat them accordingly.

# Objective: 

The aim of this project is to build a predictive model and find out the sales of each product at a particular store.

## Data fields:

1.	Item_Identifier: Unique product ID
2.	Item_Weight: Weight of product
3.	Item_Fat_Content: Whether the product is low fat or not
4.	Item_Visibility: The % of total display area of all products in a store allocated to the particular product
5.	Item_Type: The category to which the product belongs
6.	Item_MRP: Maximum Retail Price (list price) of the product
7.	Outlet_Identifier: Unique store ID
8.	Outlet_Establishment_Year: The year in which store was established
9.	Outlet_Size: The size of the store in terms of ground area covered
10.	Outlet_Location_Type: The type of city in which the store is located
11.	Outlet_Type: Whether the outlet is just a grocery store or some sort of supermarket
12.	Item_Outlet_Sales: Sales of the product in the particulat store. This is the outcome variable to be predicted.


# My Approch:

1.	Importing the required libraries and reading the dataset. 

    a.	 Merging of the two datasets 
    
    b.	 Understanding the dataset

2.	Feature Engineering 

    a.	 Dropping of unwanted columns and values (closed stores)
    
    b.	 Filling Missing Values with Imputation
    
    c.   Outliers Detection and removal

3.	Exploratory Data Analysis (EDA) –

    a.	 Data Visualizatiom

4.	Label Encoding & Robust Standardization

5.	Model Building 

    a.	 Performing train test split 
    
    b.	 GradientBoosting Regression Model  
    
    c.	 MultiLayer Perceptron Regression
    
    d.   GridSearch CV
    
6.	Model Validation 

    a.	 Root mean squared error

7.	Creating the final right model and save the model with best hyperparameters

8.	Conclusion
