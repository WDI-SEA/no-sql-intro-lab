# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
The term noSQL means that the structure of your database is a lot more flexible in terms of structure of your data ("schema-less") and are also known and non-relational databases. This means that noSQL dbs are structured without tables and don't necessarily have the same traditional need for joins.
2. What are some of the common arguments for using a non-relational versus a relational db?
They can be more performant since related data is stored together and they offer more flexibility into the makeup of any particular data point.
3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db?
One of the most important characteristics of a document is that you can have embedded documents, meaning that you can nest data attributes within data attributes (up to 100 levels of nesting) but you can also do a more traditional tool, more closely, related to SQL by doing referencing from one document to another via an Id or other attribute. 
4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?
MongoDB automatically maintains replica sets, multiple copies of data that are distributed across servers, racks and data centers. Replica sets help prevent database downtime using native replication and automatic failover.
5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. A table in SQL is a collection in MongoDB while a document in MongoDB would be a data point or row in SQL. In terms of the interaction between your project and the database, they function similarly in that you do have to develop a schema and a model to tell the database the "structure" of your db.
6. What is an example situation where a Mongo database makes sense versus a non-relational db?
In very large scale applications where the data will be heterogeneous and it requires for it to be flexible.

