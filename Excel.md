# Excel Projects


**Retail Sales Breakdown** <br/>
*Using Targeted Analytics to Understand Customer Trends* <br/>
Using the a retail sales dataset, we have a collection of listed sales for customers of a range of ages, across three different categories of product. Here, using a combination of conditional formatting and a SumIf statement, we are able to see the highest and lowest selling product categories across each age range, as well as the total sales figure from those categories. This would allow us to more directly promote specific products to specific age ranges, as we can tell they are more popular for that group.

For creating these tables and formatting, there are a few steps I needed to take first before even beginning with the end product.:
- Uploaded the raw dataset to be organised and cleaned.
- Formatted the dataset into a table for easier control.
- Checked data types are appropriate for each column, especially on number columns, as if no calculations are needed, they need to be formatted as text to avoid any problems.
- Checked for any duplicates or Null values, or any spelling errors causing multiple instances of the same value.
- Created a new column for arranging Customer ages by a range rather than individual number values, using an IF statement.
- Created a SumIf statement based on new age range column and product categorie sales.

<img src="Images/Retail_Sales_Dataset.png" alt="Excel Table 1" style="width:50%; height:auto;"> <img src="Images/Sales_By_Age_and_Category.png" alt="Excel Table 2" style="width:40%; height:auto;">

As well, making use of Excel PivotTables, PivotCharts and Slicers, we can incorporate visualisations for a wide selection of data, then use the built-in tools to drill down to specific criteria that we might want to investigate. For instance, we can see that Young Adult Male's are most predominantly buying clothing items, followed closely by Beauty products. However, changing the age range to Senior shows a dramatic increase in the purchase of Electronics over clothing and beauty. 

The slicers created allow us to filter these charts based on:
- Age Range
- Category of Item Sold
- Gender

<img src="Images/PivotTables.png" alt="Excel Pivot Tables and Charts" style="width:100%; height:auto;">
