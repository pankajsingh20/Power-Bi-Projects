# Coffee Shop Sales

Goal: Apply time series analysis to historical coffee sales data in order to spot patterns, boost revenue, and improve customer satisfaction.

Process: Create a CSV file from the Excel file:
Access the Excel document holding the sales information.
To ensure compatibility for SQL import, use the "Save As" feature to export the file as a CSV (Comma Separated Values) file.

Create a CSV file import in SQL Workbench:
Launch SQL Workbench, then select an existing database or create a new one.
To upload the CSV file into a database table, use the "Load Data" or "Import" function.
Try previewing the data with a basic SELECT query to confirm that the import went well.

Clear the Data and Modify the Types of Data:
SQL queries can be used to find and address errors, duplication, and missing or null values in a dataset.
Convert data types—like dates and numerical values—when needed.

Run SQL queries:
Calculate average sales, total sales, etc. using aggregation functions.
Date and Time Functions: For time series analysis, take the year, month, or day out of the sale date.
Joins: Merge sales data with pertinent information from other tables, like customer records.
Subqueries: To find particular insights, use nested queries.

Into Power BI, import the cleaned data:
Go to the SQL database and launch Power BI Desktop.
Fill Power BI with the cleaned and processed sales data.
If necessary, establish linkages between tables to guarantee the integrity of the data.

Run DAX queries and make trend charts and KPIs:
Create calculated columns and measurements by using DAX (Data Analysis Expressions).
Create Key Performance Indicators (KPIs) to monitor key performance metrics like average monthly sales, top-selling products, etc.
To see trends in sales over time, make trend charts.
To display annual or monthly sales trends, use line charts.
To compare sales across various product categories, use bar charts.

Create a Sophisticated Dashboard to Show Insights:
Create a thorough Power BI dashboard with the following features: Sales trends over several time periods.
KPIs gives fast access to important performance indicators.
Users can go further into particular products, dates, or client segments with the use of interactive filters.
Incorporating visual components such as interactive charts, maps, and slicers can improve user experience and enable more thorough data investigation.
Make sure the dashboard has an easy-to-use layout, with labels that are clear.
<br>
Tools Employed:
SQL Workbench: For SQL querying, cleaning, and data import.
Excel: For managing original data and converting it to CSV.
Power BI: For creating dashboards, DAX queries, and sophisticated data visualisation.
<br>
Author - Pankaj Singh
