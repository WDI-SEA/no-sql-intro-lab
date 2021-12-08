# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?

    > noSQL or 'non-SQL' databases are non-relational databases that store data in documents, as opposed to SQL which are more rigid relational databases which store data on tables.
    
    <br/>
    



2. What are some of the common arguments for using a non-relational versus a relational db?

    > non-relational db's can handle less structured, more modular data. They also tend to be easier to update and adapt with new features. 

     <br/> 

3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 

    >* stores data in field-value pair
    >* most often stored in formats like JSON,BSON, and XML
    >* A group of documents is called a Collection
    >* Document db's can satisfy all of the CRUD (Create, Read, Update, Delete) operations
    >* They have flexible schema that can differ from document to document
    >* Distributed, for horizontal scaling
    >* Can be queried though an API or query language 

    <br/>

4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?

    >Mongo automatically maintains replica sets of data, meaning that they are distributed across servers to prevent db downtime and good resilience. Mongos documents also use BSON,

    <br/>

5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 

    >* A SQL table would include parameters such as name, e-mail, location, >phone number all in seperate columns. Every user would have all of those >same columns attached to their data set even if they  are left empty. >Relations can be made to other tables using foreign keys that would need >to be included in the tables schema.
    
    <br>

    >* With Mongo, the document for a single user could vary from a document >for another user by any number of fields. With Mongo you can also further >embed an additional document within another. For instance an address >document could be embedded in the user document to include fields such as >"street adress", "city", "state", "zipcode". 

    <br/>


6. What is an example situation where a Mongo database makes sense versus a relational db?

    > IoT, or the Internet of Things, referring to all of those smart devices we now all have and love (i.e. voice controlled lights, fridges with screens, and other that other cool furutistic stuff). These devices need flexible and responsive data, and Mongo databases give them just that, they are also cheaper to run, and easier to scale with new features. 

