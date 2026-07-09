# Power Bi
## [Return to Main Page](/README.md)
**European Sales Figures**<br/>
*Exploring Relational Databases through Power Bi Visuals* <br/>

Here, we have a collection of sales data covering the entirety of Europe, for furniture, technology and office supplies. We also have a much broader range of details compared to our porevious sets, now including map data for specific cities through longitude and latitude coordinates, as well as further details on the particulars of the sale itself, such as any discounts being applied per sale, or the shipping date and method. 

Compared to Excel and Tableau, we now clean and transform a lot of our data using Power Query, as it allows a much more thorough and in-depth understanding of the quality of our data prior to importing it into Power Bi and creating our relationships. We also start to implement methods of anonymising specific data, such as removing the details of the "Customer Name" column here, as it is unnecessary for our analysis and contains sensitive customer information.
<img src="Images/PowerQuery.png" alt="Power Query Cleaning" style="width:100%; height:auto;">

Once cleaned, we now have the dataset in Power Bi itself, and need to set up the relationships to link the different tables. Without them, we would only ever be referencing one single table at a time, and the options we have for analysis are very limited. Linknig these two via their shared Order_ID means that we can use the combiend sets of data without actually combining them, keeping each tables purpose clear while still allowing us a thorough analysis. This is an example of a 1-to-many relationship, with their only ever being 1 specific order ID in the Order_details table, but the potential for multiple in Order_Information, where we can use it to reference the multiple different details kept in the Information tables columns.
<img src="Images/BiRelationship.png" alt="Power Bi Relationship" style="width:100%; height:auto;">

With the relationships set, we can now start analysing specific parts of the data using visualisations. As this is obviously a sales dataset, we want to analyse the different aspects that affect those sales. The two keys to this dashboard are the decomposition tree and the Geographic breakdown. Not only do these give a good understanding of specific regions themselves, they can also be used to inspect particular countries, which will adjust the bar and pie chart to give more detailed information for that region. We can also see on the map where the higher concentration of sales are in each region based on the size of the circles, showing our most frequent customer areas more easily.

Similar to Tableau, there is a live representation of the data, availabe here: [Live Sales Data Dashboard](https://app.powerbi.com/groups/me/reports/512b7816-5fa6-4572-87ad-6f32f802d764/b91c20d19db3bb06e33e?experience=power-bi)

<img src="Images/BiDashboard.png" alt="Power Bi Sales Dashboard" style="width:100%; height:auto;"> <br/>
