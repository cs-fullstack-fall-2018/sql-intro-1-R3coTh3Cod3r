# sql-intro-1

Answer the following questions using the SQL Fiddle here: http://sqlfiddle.com/#!9/bc1df3/1000

- 1.1 Select the names of all the products in the store.
ANSWER:select name from manufactures;

- 1.2 Select the names and the prices of all the products in the store.
ANSWER:select name FROM Manufacturers;

select price from products

-1.3 Select the name of the products with a price less than or equal to $200.
ANSWER:
select name,price from products
where price <=200

- 1.4 Select all the products with a price between $60 and $120.
ANSWER:select price from products
where price between 60 and 120

- 1.5 Select the name and price in cents (i.e., the price must be multiplied by 100).
ANSWER:


- 1.6 Compute the average price of all the products.
ANSWER:select avg (price) from products

where price


- 1.7 Compute the average price of all products with manufacturer code equal to 2.
ANSWER:select code from manufacturers
where code = 2
select avg (price) from products

where price

- 1.8 Compute the number of products with a price larger than or equal to $180.
ANSWER:select name,price from products
where price <=180
- 1.9 Select the name and price of all products with a price larger than or equal to $180, and sort first by price (in descending order), and then by name (in ascending order).
ANSWER:select name,price from products
where price >= 180
order by 

- 1.10 Select all the data from the products, including all the data for each product's manufacturer.
ANSWER:
- 1.11 Select the product name, price, and manufacturer name of all the products.
ANSWER:select name, price from products
