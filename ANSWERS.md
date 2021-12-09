# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
    When people use the term “NoSQL database,” they typically use it to refer to any non-relational database. Some say the term “NoSQL” stands for “non SQL” while others say it stands for “not only SQL.” Either way, most agree that NoSQL databases are databases that store data in a format other than relational tables.

2. What are some of the common arguments for using a non-relational versus a relational db?
    Flexibility of the schema
    Scaling technique
    Support for transactions    
    Reliance on data to object mapping

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
    Document databases store all information for a given object in a single instance in the database, and every stored object can be different from every other.

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?
    Mongo is maintained with documents while SQL is maintained through a table schema

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 
    
    for SQL
    DB "House" -> Table "Furniture", Table "Pets, Table "Humans"-> Each table has rows of attribute for each input

    for MongoDB
    DB "House"-> Folder "Furniture", Folder "Pets, Folder "Humans"-> Each folder contains documents w/ all of the attributes of each entry

6. What is an example situation where a Mongo database makes sense versus a non-relational db?
    a Mongo database makes sense when building an app in an agile environment and you constantly need to adjust your db for your needs. 