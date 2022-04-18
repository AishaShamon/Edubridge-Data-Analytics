## objective
Predict the marketing trend
## About Data:
Context

The growth of supermarkets in most populated cities are increasing and market competitions are also high.
The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data.
Predictive data analytics methods are easy to apply with this dataset.
Attribute information

Invoice id: Computer generated sales slip invoice identification number

Branch: Branch of supercenter (3 branches are available identified by A, B and C).

City: Location of supercenters

Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.

Gender: Gender type of customer

Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages,
Health and beauty, Home and lifestyle, Sports and travel

Unit price: Price of each product in $

Quantity: Number of products purchased by customer

Tax: 5% tax fee for customer buying

Total: Total price including tax

Date: Date of purchase (Record available from January 2019 to March 2019)

Time: Purchase time (10am to 9pm)

Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)

COGS: Cost of goods sold

Gross margin percentage: Gross margin percentage

Gross income: Gross income

Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)
## Structure:
## Task 1: Load the Data and Import Libraries
Load the dataset using pandas.
Import essential modules and helper functions from NumPy and Matplotlib & sklearn.
Explore the dataframe using the head().
## Task 2: Inspect the Data
Explore the dataframe using the shape, info() functions.
Check the null values
Get Statistical Overview using describe()
## Task 3: Exploratory Data Analysis
For this dataset, I used a histogram, correlation matrix, barplot(), lineplot(), piechart, pointplot(), scatterplot()
using Seaborn & Matplotlib to visualize the data
Used boxplot()/jointplot() to check outliers in data
## Conclution
Through this preliminary analysis, I would suggest to the company that they should revamp their membership program because clearly it is not very effective.
Based on the ratings, members are not any happier with service than non-members and they are only slightly more likely to spend more money. 
This should not be the case.
