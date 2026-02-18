Here is a simple explanation of your SQL program:
1️⃣ Create Table – buyers_data
A table is created to store buyer details.
Columns: buyer_id, buyer_name, city, purchase_amount.
2️⃣ Insert Data
Added 4 buyers:
Kavya – Chennai – 28000
Ramesh – Mumbai – 19000
Divya – Delhi – 35000
Suresh – Bangalore – 22000
3️⃣ SELECT *
Displays all buyers in the table.
4️⃣ WHERE (purchase_amount > 20000)
Shows buyers who purchased more than 20000.
Result: Kavya, Divya, Suresh.
5️⃣ ORDER BY (DESC)
Displays buyers in descending order of purchase amount.
Highest purchase shown first.
6️⃣ AVG()
Finds average purchase amount.
Result: 26000
7️⃣ GROUP BY (city)
Calculates total purchase for each city.
8️⃣ Create orders_data Table
Stores order details:
order_id
buyer_id
product
quantity
9️⃣ Insert Orders
Laptop, Mobile, Tablet, Headphones added.
🔟 JOIN
Combines buyers and orders using buyer_id.
Shows buyer name + product + quantity.
1️⃣2️⃣ VIEW
Creates a virtual table (buyer_view) from buyers_data.
Used to display selected columns easily.
✅ Overall:
This program shows how to create tables, insert data, filtters etc...
