## Introduction to MongoDB

### What is MongoDB?

MongoDB is an open-source document-oriented database that is designed to store a large scale of data and also allows you to work with that data very efficiently. It is categorized under the NoSQL (Not only SQL or non SQL) database because the storage and retrieval of data in the MongoDB are not in the form of tables. MongoDB stores data in the form of documents.

Basically whenever you start mongoDb you start a mongoDB server on which you can create databases. let's say we have a database called 'ABC-infotech-db' for a company name called ABC infotech. Now ABC infotech can have data for many entities like Employees, positions, office Locations, etc.
So each entity can have its own collection (kind of a group of data for specific type of entity.) Each collection stores the data in the form of document in mongoDB. This document is just like json documents. Have a look at below image for better understanding.

![MongoDB structure(01-Introduction/images/MongoDB structure.png)](https://github.com/Akhil-Selukar/MongoDB/blob/master/01-Introduction/images/MongoDB%20structure.png)

From above diagram we can see that there are multiple databases running on a mongoDB server. Inside the database (ABC-infotech-db) there are multiple collections for individual entities. Inside each collection we have multiple documents. Documents are the places where the actual data is stored.

From above diagram we can see that the documents in Employee collection does not have consistant structure (schema). First document has 'lastConmapy', 'yrOfExperience', 'uanNumber' fields which are not there in second document, while second document have 'graduationYr' field which is not there in first document. So this is what schema less or NoSql behaviour of mongoDB.
