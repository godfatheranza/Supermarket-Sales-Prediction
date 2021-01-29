# Supermarket Sales Prediction Using Time Seriese Sales Forecasting ARIMA and Tableau Visualization for Desicion Making.

<p>In this project our main goal is to use the power of traditional statistical model like ARIMA for forecasting sales prediction of supermarket sales data.This will help any supermarket to find any seasonal, trend and patterns in their sales as well as from forecasting they can plan in well advance for future goal.The data we have used in order to do this project is from Kaggle.<p>

**Data Set Link:** https://www.kaggle.com/aungpyaeap/supermarket-sales

**Things which we have perfromed in Python Notebook or our data pipeline:**

1. Basic Exploration Of Data
2. Converting Date Column Into Datetime Format
3. Filtering Sales Data For Yangon City
4. Testing For Stationarity
5. Resampling Data
6. Forecasting With ARIMA


# Data Description:

This data is about supermarket sales, and this data is for three diffrenet brnach over the period of three months between January 2019 to March 2019. Each row represent the purchase made by any customer or we can say Invoice ID.

**Below is brief description of each columns in our data.**

1. **Invoice id (Numerical):** Computer generated sales slip invoice identification number
2. **Branch (Categorical):** Branch of supercenter (3 branches are available identified by   A, B and C).
3. **City (Categorical):** Location of supercenters
4. **Customer type (Categorical):** Type of customers, recorded by Members for customers using member card and Normal for without member card.

5. **Gender (Categorical):** Gender type of customer
6. **Product line:** General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
7. **Unit price (Numerical):** Price of each product 
8. **Quantity (Numerical):** Number of products purchased by customer
9. **Tax (Numerical):** 5% tax fee for customer buying
10. **Total (Numerical):** Total price including tax
11. **Date (Numerical):** Date of purchase (Record available from January 2019 to March 2019)
12. **Time (Numerical):** Purchase time (10am to 9pm)
13. **Payment (Categorical):** Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet) 14. **COGS (Numerical):** Cost of goods sold
15. **Gross margin percentage (Numerical):** Gross margin percentage
16. **Gross income (Numerical):** Gross income generated from particular product sold
17. **Rating (Numerical):** Customer statification rating on their overall shopping experience (On a scale of 1 to 10)




