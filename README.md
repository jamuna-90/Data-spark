Data Spark Project
! pip install pandas(installing )
import pandas as pd (import on the pandas library)

Data cleaning process:
1.customer details:
   First, analyze and clean the customer tables. Begin by analyzing and cleaning the customer tables
   #I used a regular expression to change the column names to their alphabetic values.
   #I converted the birthday columns to datetime functionality.
   #I converted the zip code dtype to int
   #Filled the null values for the State Code.
   #I converted the customer details to a CSV file
   
2.sales details:
   ##/ are replace the '-'
   #I converted the Order Date and Delivery Date to the appropriate datatype.(datetime functionality)
   #sales details store in csv file
   #I removed duplicate values from the sales data.
   #I converted the sales details to a CSV file

3.Products details:
  #Convert all values to strings first, strip the $ sign, then remove the Unit Cost USD and Unit Price USD prefixes, and convert the cleaned strings to numeric values for Unit Cost USD and Unit Price USD.
  #I removed duplicate values from the product data.
  #I converted the product details to a CSV file
  
4.store details:
  #I converted the Open Date to the date and time datatype.
  #I filled the null values for Square Meters columns.
  #I converted the store details to a CSV file
  
5.Exchange_Rates details:
  #data are converted to the date and time
  #I converted the Exchange_Rates details to a CSV file

Data store in SQL database:
  #.I am using the XAMPP server.
  # Create the database for Dataspark first, and then create the table.
  # Insert the values into the Customer Details, Sales Details, Product Details, Store Details, and Exchange Rates tables, and display the results in a tabular format.

Power BI:
  #i am using the power BI desktop.
  #Customer Details, Sales Details, Product Details, Store Details, and Exchange Rates tables connceted to the table.sales is the fact table,remaining are dimensional   table.Fact table connct to the all dimensional table using common columns.

SQL Query:
# I am creating the 10 sql query and the display the answers..

  

