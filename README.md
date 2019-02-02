# mongo-doc
Straight forward documentation for MongoDB commands 

MongoDB is a cross-platform document-oriented database program.
It's provides high performance, high availability, and easy scalability.
Classified as a NoSQL database program, MongoDB uses JSON-like documents with schemata.
MongoDB is an open-source document database and leading NoSQL database.

Database,
Database is a physical container for collections. Each database gets its own set of files on the file system.

Collection
Collection is a group of MongoDB documents. It is the equivalent of an RDBMS table. A collection exists within a single database. Collections do not enforce a schema. Documents within a collection can have different fields. 

Document
A document is a set of key-value pairs. Documents have dynamic schema. Dynamic schema means that documents in the same collection do not need to have the same set of fields or structure, and common fields in a collection's documents may hold different types of data.

	RDBMS		MongoDB
	Database	Database
	Table		Collection
	Tuple/Row	Document
	Column		Field
	Table Join	Embedded Documents
	Primary Key	Primary Key


MongoDB Enterprise installation, 
https://docs.mongodb.com/manual/administration/install-enterprise/

MongoDB Community Edition installation, 
https://docs.mongodb.com/manual/administration/install-on-linux/

Documentation reference: 
https://docs.mongodb.com/manual/?_ga=2.16703094.1960102958.1549132509-1699402000.1532081772
https://www.tutorialspoint.com/mongodb
