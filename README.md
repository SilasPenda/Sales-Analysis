# Sales Analysis
This is a sales analysis of an online retail store where i answered a questions that will guide decision making
## Project Guide
In this project i used Pandas, Matplotlib to analyze and answer business questions using two online retail sales data. The data contains hundreds of thousands of data broken down into InvoiceID, InvoiveDate, Description, Quantity, UnitPrice, etc

This project was carried out using the following steps:
* Importing the necessary libraries
* Reading the two CSV files into dataframes and renaming and re-arranging the columns so concatenation will be accurate 
* Concatenating the two CSV files into a single CSV file which i read into a dataframe
* Cleaning data by
  * Changing the type of columns (to_numeric, to_datetime, astype)
  * Dropping irrelevant columns
  * Renaming columns appropriately
  * Adding columns

Once i cleaned up the data a bit, i moved to the data exploration section. In this section i explored 5 high level business questions related to the data:
* What is the best sales month and how much was earned that month?
* What country has the highest number of sales?
* What time should we display advertisements to maximize likelihood of customers buying product?
* What products are most often sold together?
*  What product sold the most?
