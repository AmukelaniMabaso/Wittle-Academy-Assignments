# Project Overview

## This project is an Entity Relationship Diagram (ERD) for the WitleShop Online Retail System.

### WitleShop is an online retail company that sells electronics, clothing and home appliances. The purpose of this project was to design a database structure that can store and manage information about customers, products, orders, payments, deliveries and suppliers.

### The ERD was created based on the requirements provided in the assignment.

## The entities I identified were:

Customer
Address
Product
Category
Supplier
Order
OrderItem
Payment
Delivery
I identified the attributes

## After identifying the entities, I looked at the information that needs to be stored for each one.

### For example, the Customer entity needs to store:

Customer ID
Full Name
Email
Phone Number
Registration Date

### The Product entity needs to store:

Product ID
Product Name
Description
Price
Stock Quantity
Category
Supplier

## I followed the requirements in the case study when identifying the information for each entity.

### I identified a Primary Key (PK) for each entity.

A Primary Key is used to uniquely identify a record.

### For example:

Customer → CustomerID
Product → ProductID
Order → OrderID
Payment → PaymentID
Delivery → DeliveryID

The other entities were also given unique IDs.

## I identified the Foreign Keys

I then looked at how the entities connect to each other.

### Foreign Keys (FKs) were added to connect the related entities.

For example:

Address uses CustomerID to connect to Customer.
Order uses CustomerID to connect to Customer.
Product uses CategoryID to connect to Category.
Product uses SupplierID to connect to Supplier.
Payment uses OrderID to connect to Order.
Delivery uses OrderID and AddressID to connect to Order and Address.

## I identified the relationships

### For example:

Customer → Order

A customer can place many orders, but each order belongs to one customer.

Therefore, the relationship is:

1 (One-to-Many)

Another example is:

Order → Payment

Each order must have one payment and each payment belongs to one order.

Therefore, the relationship is:

1:1 (One-to-One)

I created the ERD

After identifying the entities, attributes, keys and relationships, I put everything together into an ERD.

The diagram shows:

Entities
Primary Keys
Foreign Keys
Relationships
Cardinalities

### The ERD was designed using draw.io.

## Tools Used
### draw.io – Used to create the ERD diagram.
### GitHub – Used to store and submit the project and documentation.

# What I Learned

Through this assignment, I learned how to:

Identify entities from business requirements.
Identify Primary Keys and Foreign Keys.
Identify one-to-one relationships.
Identify one-to-many relationships.
Use an ERD to visually represent a database structure.
Document and submit a database design project using GitHub.

# Conclusion

The ERD provides a structured design for the WitleShop Online Retail System.

The process started by identifying the entities. I then identified the Primary Keys and Foreign Keys, determined the relationships between the entities, and added the appropriate cardinalities.

The final ERD represents the database structure required by the WitleShop case study.
