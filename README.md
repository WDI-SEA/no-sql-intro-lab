# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?\
   NoSQL, also referred to as “not only SQL”, “non-SQL”, is an approach to database design that enables the storage and querying of data outside the traditional structures found in relational databases.
   
2. What are some of the common arguments for using a non-relational versus a relational db?\
   NoSQL tends to be a better option for modern applications that have more complex, constantly changing data sets, requiring a flexible data model that doesn’t need to be immediately defined, NoSQL databases can store and process data in real-time.
3. In this class we will be using the document style of non-relational databases. What are the  charecteristics of a document based db?\
   Document based db consists of Binary JavaScript Object Notation objects, Document databases provide fast queries, a structure well suited for handling big data, flexible indexing and a simplified method of maintaining the database. 
4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?\
   The major difference between MongoDB and SQL Databases is the way they handle data. In SQL databases, -data is stored in form of traditional 2 dimensional row-column structure while in MongoDB rich data document model is followed, which allows storage of any type of data.
   
5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. \
    a user in aa relational database will be given a fixed id created automatically by sql while in a -document no sql , Id would be created inside a collection as objects.

6. What is an example situation where a Mongo database makes sense versus a non-relational db?\
    In today's dynamic use cases and ever-changing applications, having a flexible data model is a boon. A flexible data model means that there is no predefined schema, and the document can hold any set of -values based on any key.
   for relational databases, it would make sensse if it used on a bank 

    

