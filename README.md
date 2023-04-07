# SQL Case Study

This GitHub repository contains SQL queries to solve a case study. The queries are written in T-SQL, which is a proprietary procedural language used by Microsoft in SQL Server.

### Dataset

The dataset consists of three tables:

**fact** - contains data on sales, profits, marketing expenses, inventory, and total expenses of products.<br>

**location**- contains data on the states and area codes of the locations where the products were sold.<br>

**product** - contains data on the type and name of the products.

### Queries

The queries solve the following problems:

- Display the number of states present in the location table.
- Find the number of products that are of regular type.
- Calculate the amount spent on marketing product id 1.
- Find the minimum sales of a product.
- Display the maximum Cost of Goods Sold (COGS).
- Display the details of the productid where the product type is coffee.
- Display the details where the total_expenses is greater than 40.
- Find the average sales in area_code 719.
- Find the total profit generated by Colorado state.
- Display the average inventory for each productid.
- Display the state in sequential order in the location table.
- Display the average budget margin where the average budget margin should be greater than 100.
- Find the total sales done on date 2010-01-01.
- Display the average total expense of each productid on an individual date.
- Display the table with the following attributes: Date, productid, product_type, product, Sales, Profit, State, and Area_Code.
- Display the rank without any gap to show the Sales wise rank.
- Find the State-wise Profit and Sales.
- Find the State-wise Profit and Sales along with the Product Name.
- If there is an increase in sales of 5%, calculate the increased sales.
- Find the maximum profit along with the Product id and Product Type.
- Create a stored procedure to fetch the result according to the product type from Product.
- Write a query by creating a condition in which if the total_expenses is less than 60, then it is a profit or else loss.
- Give the total weekly sales value with the Date and productid details. Use roll-up to pull the data in hierarchical order.
- Apply union and intersection operators on the tables that consist of attribute area_code.
- Create a user-defined function for the product table to fetch a particular product type based upon the user’s preference.

### Conclusion

These queries demonstrate how T-SQL can be used to extract meaningful insights from a dataset. They cover a wide range of SQL concepts such as aggregation, joins, window functions, and stored procedures, among others. These queries can be used as a reference for SQL beginners who are starting to learn SQL or for experienced SQL developers who want to refresh their knowledge.
