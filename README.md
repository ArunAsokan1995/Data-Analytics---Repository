# Data Analytics - Repository
Data Analytics - Assignment and Projects
## Students Database- Mean, Median and Mode
## Assignment 1 - Data Exploration
Found SUM, Count and Average of the dataset.
Found Min and Max for the product price
Using IF function, added a new column and found the categorisation of the product based on price range
Using SUMIF function, Found the total price of a particular product
Using COUNTIF, found the count of a particular product less the certain price range.
Using LEFT, MID and RIGHT function, found the Day, Country Code and Month from Product ID.
### Assignment 2 Data Cleaning and Transformation
## Handling Missing Values
# First the Product Name has been aligned in Proper
# Then correct the spelling of Category and fill up the missing category based on product name manually
# Replace Electroni with Electronics IF(F3="Electroni","Electronics",F3)
# Manually Replace the Blank Category based on the  Product Type
# Then We can fill out the missing Prices
# Headphones and Sunglasses can be arrived based on Average price of that product and Camping Tent Price can be arrived bases to the average price of Category it is mapped.
## Correcting Inconsistent Data
# First the Product Name has been aligned in Proper
# Then correct the spelling of Category and fill up the missing category based on product name manually
# Replace Electroni with Electronics IF(F3="Electroni","Electronics",F3)
## Removing Duplicates
# 3 Duplications removed by selecting all the columns in Data -> Remove Duplicates
## Splitting and Merging Data
# Splited Product ID to Manufacturing Date and Country code
# Either you can use MID Function or you can use Text to Column in the Data ribbon and can split with separator "-"
# Using Concatenate Function the Brand Name and Product Name can be Merged CONCATENATE(E2&" "&D2)
## Number Formatting
# Formatted Price Column in currency  by selecting Currency type in Home - Section Number - Different Type
# Replace the last 2 words in the product ID to year 2026,  LEFT(A2,LEN(A2)-2)&"2026" and created a new column Manufacturing date. Then in Home -> Number Section -> advance Menu -> Selected Date in DD-MM-YYYY format
## Conditional Formatting
# Price highlighted with Data bars - high to low
# Category - Electronics highlighted with Colour formatting with specific logic
