1). The relationship between the "Product" and "Product-Category" entities from the diagram:
 
  The relationship between the "Product" and "Product-Category" entities is a "category-id" column from the "Product" table. The "category-id" column is a Foreign key that referencing the "id" column in the "Product-Category" table. This can be one to many relationships, because the the product category can have many products and products have one product category.

2). How could ensure that each product in the "Product" table has a valid category assigned to it:

  We can ensure that each product in "Product" table has a valid category assigned to it by we can add category-id column in "product-inventory" table and assigned it as foreign key to the "Product-Category" table as an id column.