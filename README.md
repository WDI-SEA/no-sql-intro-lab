# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
    * noSQL - aka Not only SQL. Non tabular databases, stores information differently. Types: document, key-value, wide-column, graph.

2. What are some of the common arguments for using a non-relational versus a relational db?
    * More scalable  
    * Better performance  
    * Flexibility  
    * Ease of use
    * Does not require join table

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
    * Does not use fixed rows and columns. 
    * Stores data in field: value pairs
    * Structured like JSON
    * Collection of documents are called a Collection
    * Flexible schema: does not require all documents to have same fields
    * Option to be locked down to have strict field: value pairs
    * Typically has an API or query language to execute CRUD operations
    * Distributed databases: Allows for horizontal scaling and data distribution

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?
    * Mongo does not need to have structured data like SQL does
    * Mongo saves this data in JSON format
    * Mongo does not require join tables

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 
    * SQL - rows and colums in a table.  Column has "type" of data, and row has actual data to associate with that column.
    * Mongo - field: value assocations of data.  Stored as JSON object in what's called a Document.  Multiple Documents within that collection, each storing an object type of information.  {name: "Jason", Age: 21, etc}

6. What is an example situation where a Mongo database makes sense versus a non-relational db?
    * Mongo would make more sense in a situation where rapid development is happening and a less strict type of data storage is needed.  For example, if a program/app adds a new feature that needs to store the data, the database does not need to be re-written to store new types of data.

