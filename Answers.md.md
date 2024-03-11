
# Assignment Answers

### 1) Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.

"Product" table consists of "category_id" which is a foreign key referencing the category to which the product belongs.

So the relationship between the "Product" and "Product_Category" table is done with  **"category_id"** attribute present in "Product" table.

Here the **"category_id"** is a foreign key which points towards the "id" attribute in "Product_Category".


### 2) How could you ensure that each product in the "Product" table has a valid category assigned to it?

To ensure that each product in the "Product" table has a valid category assigned to it, we can use database constraints, specifically foreign key constraints. Foreign key constraints ensure that the values in a column (like the "category_id" column in the "Product" table) match the values in a referenced column (the "id" column in the "Product_Category" table).
