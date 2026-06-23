# Basics of Database Modeling - Notes

Here are my notes on the topic of database modeling.

## Review On Identifying Entities

Entities are tables in the database where data is stored. They are very similar to classes in OOP. They fall into four categories: people, which represents data about real people such as vendors, customers, employees, managers, etc; events, which are things that happen, such as sales, deliveries, enrollments, etc; localtions, which are places like cities, addresses, stores, etc; and last but not least, things. They can be any type of object such as clothes, cars or even furniture.

![alt text](../images/image.png)

## Identifying Relationships

### Relationships

Relationships between entities tells us how two different tables relate to one another. How many customers are connected to just one sale? How many products can be connected to how many shops?

### Cardinality 

Cardinality refers to the numerical relationship between rows in one table and rows in another table. It basically tells how many instances of an entity relate to how many instances of another one.

### Types Of Relationships

There are four types of relationships. They are: one-to-one, one-to-many, many-to-one, and many-to-many. And they are represented as: 1:1, 1:N, M:1, and M:N. When 'many' is placed on the left, it's represented with 'M', and when placed on the right, it's represented with 'N'.

### Mandatory Relationships

Some entities can have instances independently from others, like a customer entity for example. Customers can exist without any sales or products related to them, however sales can only exist when related to a customer, vendor or a product depending on the business rules being applied.