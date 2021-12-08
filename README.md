# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

* NoSQL = non-relational db, non SQL, or not only SQL
---
2. What are some of the common arguments for using a non-relational versus a relational db?

* Best for flexible data storate with little to no structure limitation
* Provide flexible data model, not confined to as structure, with the ability to easily store and combine data of any structure w/o needing to modify the schema
* Data and analysis can be more dynamic and allow for more variant inputs
---
3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 

* Document model: data is stored in documents instead of tables/graphs
* Flexible schema: not all documents in a collection need to have the same fields, but some document dbs support schema validation (option to require schema)
* Distributed & resilient: distribution allows for horizontal scaling and resiliency is provided through replication
* Querying through an API or query language: have an API or query language to execute the CRUD operations on the db; ability to query for documents based on unique field values or identifiers
---
4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?

* SQL data is stored in form of traditional 2 dimensional row-column structure, wheras Mongo data allows storage of any type of data
---
5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 

* A example of a users table in in SQL would have attributes of an id, name, email, and password, with the id being the unique identifier.
* In Mongo, the users collection would be _id, name, email, and password. But more fields could easily be inserted without having to already have those fields be set.
---
6. What is an example situation where a Mongo database makes sense versus a relational db?

* Best situations non-realational db are for data that's changing and there's a need for more flexibility, like Instagram or other social media platforms.