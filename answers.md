1. State and Explain the components of a DBMS (Database Management System):
A DBMS has the following core components:

Database Engine:
Responsible for storing, retrieving, and managing data. It provides mechanisms to read/write data to the database and ensures data consistency.

Database Schema:
Defines the logical structure of the database, such as tables, fields, and relationships. It acts as a blueprint for how data is organized.

Query Processor:
Interprets and executes database queries written in SQL. It ensures proper communication between the user and the database.

Transaction Manager:
Ensures data integrity and consistency by handling transactions. It follows the ACID (Atomicity, Consistency, Isolation, Durability) properties.

Data Manager:
Controls data storage and retrieval on physical storage devices. It optimizes data storage for performance and accessibility.

User Interface:
Provides tools or interfaces like command-line tools, GUIs, or APIs for users to interact with the database.


2. What is a relational database? Give 4 examples.
A relational database is a type of database that organizes data into tables (relations) with rows and columns. Relationships between tables are established using primary and foreign keys.

Examples:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server


3. State and Explain three classifications of SQL:
Data Definition Language (DDL):
Used to define and manage the structure of the database objects. Examples:

CREATE (to create tables, views, etc.)
ALTER (to modify existing structures)
DROP (to delete structures)
Data Manipulation Language (DML):
Used to retrieve and manipulate data in the database. Examples:

SELECT (to fetch data)
INSERT (to add data)
UPDATE (to modify data)
DELETE (to remove data)
Data Control Language (DCL):
Used to control access to data in the database. Examples:

GRANT (to give permissions)
REVOKE (to remove permissions)


4. What is the difference between a Primary Key and a Foreign Key?
Primary Key	Foreign Key
Uniquely identifies each record in a table.	Establishes a link between two tables.
Cannot contain duplicate or NULL values.	Can contain duplicate values and NULLs.
Defined in the same table where it is used.	References a primary key in another table.


5. What is an Entity-Relationship Diagram (ERD)?
An Entity-Relationship Diagram (ERD) is a visual representation of the database structure. It shows entities (tables), attributes (fields), and the relationships between them, helping to design and understand the logical framework of a database.


6. What are the advantages of relational databases?
Data Integrity: Enforces rules (e.g., primary and foreign keys) to maintain data consistency.
Scalability: Can handle large amounts of data efficiently.
Flexibility: Easily modify the schema without affecting existing data.
Data Security: Provides mechanisms for user authentication and access control.
Ease of Use: Uses SQL, a widely understood language, for managing data.


7. State four types of data types used to store data in tables:
Integer (INT, BIGINT, etc.): Stores whole numbers.
String (VARCHAR, CHAR, etc.): Stores text data.
Date/Time (DATE, DATETIME, etc.): Stores dates and times.
Decimal (FLOAT, DECIMAL, etc.): Stores numbers with decimals.


8. What is the purpose of a database management system (DBMS)?
The purpose of a DBMS is to:

Data Storage and Retrieval: Store and efficiently retrieve large amounts of data.
Data Management: Ensure data consistency, accuracy, and integrity.
Access Control: Restrict unauthorized access and provide multi-user access control.
Data Organization: Structure data logically to make it easily accessible and manageable.
Data Analysis: Provide tools for querying and analyzing data.