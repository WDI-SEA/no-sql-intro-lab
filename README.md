# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

The term noSQL refers to "not only SQL". Referred to a non-realtional database. NoSQL databases store date differently than other tables. An example of another type of database is MySQL which is one of the most popular databases used today. 

2. What are some of the common arguments for using a non-relational versus a relational db?

A relational database stores data in tables and rows, known as records. Relational databases work by linking data from tables via unique identifiers called, keys. A non-relational database stores data using a storage method optimized for the specific data types stored in the database. Unlike relational databases, no keys are used.

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db?

One of the most used document based databases is MongoDB. MongoDB uses documents to store data. These documents then map to objects in programming languages such as Javascript.

Another characteristic of a document based database is the use of a flexible schema. A flexible schema meaning that not all documents in a collection need to have the same fields.

Document based databases require minimal maintenance making it possible to add an object and never have to look back.

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?

SQL databases store structured data and Mondo databases store unstructured data. Examples of unstructured data include, emails, text files, and social media. Structured data can come in many forms such as airline reservations, inventory control, and ATM activity.

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo.

MySQL stores data in the form of rows and columns. Thus displaying data in a structured manner. Mongodb stores data usually in the form of BSON documents.

BSON Example:

{"hello": "world"} →
\x16\x00\x00\x00           // total document size
\x02                       // 0x02 = type String
hello\x00                  // field name
\x06\x00\x00\x00world\x00  // field value
\x00                       // 0x00 = type EOO ('end of object')

6. What is an example situation where a Mongo database makes sense versus a non-relational db?

An example of when a Mongo database makes sense vs a non-relational db can be the use of a web application. Where the data that will be created using said application will not be structured or in other words, predictable or uniform. On the contrary, a non relational database like MySQL will be most useful or required when using a banking application.