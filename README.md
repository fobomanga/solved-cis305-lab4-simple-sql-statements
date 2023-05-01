Download Link: https://assignmentchef.com/product/solved-cis305-lab4-simple-sql-statements
<br>
A. List all of the products provided by each supplier in alphabetical order with the least expensive products shown first for each supplier. Hint: Be sure to include the Product ID, Product Description, Supplier ID, Supplier Name, Vendor Part #, and Cost.

B. Which sales representative has the highest dollar amount in total sales? Hint: Provide the name and the total sales amount for that rep only. Do not include the information for other people, and do not list details about orders.

C. List all of the sales reps and their total commission amounts in order of highest sales commission dollar amount first. Hint: Provide all of sales reps’ names and their total commission dollar amounts – imagine that you were going to write one check to each sales rep to pay their total commission amount, so be sure to produce that dollar amount. Extra Hint: Not all of the sales reps have sold any orders.

D. Which sales representative has sold the most products? Hint: Name of the sales rep and a number representing the total number of distinct products sold by that rep. This is the number of different products they have sold, not the quantity of any products.

E. Which sales representative has generated the most profit for the company? Hint: Provide the name of the sales rep and the total profit amount only. This one SQL statement will have subqueries. You must determine the profitability of a product by subtracting its cost from its selling price and multiplying the difference by the quantity sold. Regarding the cost, many products are supplied by more than one suppler, and each supplier may provide a different cost, so when this occurs, use the least expensive cost in measuring your profitability.

F. Provide a listing of all of the details for each order. The report must be organized by sales rep, then alphabetically by each customer for that sales rep, and then by each Order ID for that customer. The listing must include the Sales Rep’s name, Customer Name, Order ID, Order Date, Due Date, Product ID, Product Description, Quantity Purchased, and Unit Price.

G. List the suppliers that provide hack saws, and sort the list with the lowest prices first. Hint: Your SQL statement must look for a “Hack Saw”, and not some ProductID or PartID. Include the Supplier IDs, Supplier Names, Vendor Part #s, and cost.

H. Show the components and cost of materials for fabricating a hack saw. Hint: Your SQL statement must look for a “Hack Saw”, and not some ProductID or PartID. Include the ProductID (really PartID),Product Description, and Quantity Used for each component of a hack saw.

I. Which customer purchased the overall largest dollar amount? Hint: One name and the total dollar amount only – the result should be one record only.

J. Provide an inventory report based on ’17-MAY-2017’ that lists the most costly items first. Hint: The most costly item is the one in which the product (i.e., multiplication) of cost and quantity yields the largest value, in other words, the item that we have spent the most money on. Include Product ID,Product Description, Unit Price, Cost, Quantity Purchased, Amount Spent (the product of Quantity Purchased and Cost), Supplier ID, and Supplier Name.

K. Provide an inventory report based on ’17-MAY-2017’ that lists the most profitable items first. Hint: The most profitable item is the one in which the difference between the sales price and the purchase cost yields the largest value, in other words, the item that we can potentially make the most money on. Include Product ID, Product Description, Unit Price, Cost, Profit Margin (difference between price and cost), Supplier ID, and Supplier Name.

L. List all the employees in alphabetical order and each course they have completed in order of date completed. Hint: Include all employee names even if they didn’t complete any courses, course ID, course name, and date of completion. Also, think about the way to sort individuals by alphabetical order.

M. List the ProductIDs, product descriptions, and unit prices that are valid on July 14, 2015 for all products sorted by ProductID. Hint: Search for prices valid on ’14-JUL-2015’

N. Who are the employees that report directly to Sam Drucker’s manager? Provide the information by their names in alphabetical order, and include their Employee IDs and Job Titles. Hint: Your SQL statement must look for “Sam” and “Drucker”, and not some EmployeeID that was not given to you in the problem statement.

O. What is the information relevant to order ID 1527? I want to know the Customer Name, Customer City, State, Sales Rep’s Name, Order Date, Due Date, Ship Date, Customer PO Number, ProductID, Product Description, Order Quantity, and Unit Price. Hint: Be sure that every item on the order is included and be sure that the price is valid for that order date.