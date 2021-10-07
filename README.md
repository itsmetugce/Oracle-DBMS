Database: DBMS


 Content:

•	brief summary of what databases mean

•	discuss the concept of a data management system (DBMS)

•	explain a DBMS in more detail

•	SQL Statements

•	Comments within SQL statements


What´s a Database?

A database is a collection of data that is stored in an orderly manner. Companies or organizations such as hospitals, schools and universities use databases when working with multiple people. Organizations can use different types of databases to meet their unique business needs. 

The concept of a DBMS

There are different types of database users (DBMS), e.g.

•	Database administrator (DBA)

•	End user

•	System analyst

•	Application programmer

•	Database Designer


Types of database structures explained
A company should use the type of database that suits its requirements and needs. There are several types of database structures:

•	Hierarchical database: a hierarchical database follows a ranking or parent-child relationship to structure data. 

•	Network database: the network database is similar to the hierarchical database, but with some modifications. The network database allows the child record to connect to different parent records, enabling two-way relationships. 

•	Object-oriented database: In an object-oriented database, information is stored in an object-like manner. 

•	Relational database: a relational database is table-oriented, with each bit of data linked to every other bit of data. 

•	Non-relational or NoSQL database: A No-SQL database uses a variety of formats such as documents, charts, wide columns, etc., which provide great flexibility and scalability to a database design. 


Databases are broadly classified into two main types or categories, namely: relational or sequence databases . Non-relational or non-sequential databases or No SQL databases. An organization can use them individually or in combination depending on the type of data and functionality required.

Some examples of SQL databases are

•	Oracle

•	PostgreSQL

•	MySQL

•	SQLServer


Oracle in Detail

What Does Oracle Database (Oracle DB) Mean?
Oracle Database (Oracle DB) is a relational database management system (RDBMS) from Oracle Corporation. Originally developed in 1977 by Lawrence Ellison and other developers, Oracle DB is one of the most trusted and widely used relational database engines for storing, organizing and retrieving data by type while still maintaining relationships between the various types.

The system is built around a relational database framework in which data objects may be directly accessed by users (or an application front end) through structured query language (SQL). Oracle is a fully scalable relational database architecture and is often used by global enterprises which manage and process data across wide and local area networks. The Oracle database has its own network component to allow communications across networks.

Oracle DB is also known as Oracle RDBMS and, sometimes, simply as Oracle.

A key feature of Oracle is that its architecture is split between the logical and the physical. This structure means that for large-scale distributed computing, also known as grid computing, the data location is irrelevant and transparent to the user, allowing for a more modular physical structure that can be added to and altered without affecting the activity of the database, its data or users.

The sharing of resources in this way allows for very flexible data networks with capacity that can be adjusted up or down to suit demand, without degradation of service. It also allows for a robust system to be devised, as there is no single point at which a failure can bring down the database since the networked schema of the storage resources means that any failure would be local only.
The largest benefit of the Oracle DB is that it is more scalable than SQL, which can make it more cost-efficient in enterprise instances. This means that if an organization requires a large number of databases to store data, they can be configured dynamically and accessed quickly without any periods of downtime.

Other structural features that make Oracle popular include:

•	Efficient memory caching to ensure the optimal performance of very large databases

•	High-performance partitioning to divide larger data tables in multiple pieces

•	The presence of several methods for hot, cold and incremental backups and recoveries, including the powerful Recovery Manager tool (RMAN) 


SQL Statements

SQL statements are generally considered to be either Data Manipulation Language (DML) statements or Data Definition Language (DDL) statements.

DML statements modify database objects. INSERT, UPDATE and DELETE are examples of DML statements.

DDL statements modify the database schema. CREATE TABLE and DROP TABLE are examples of DDL statements.

Comments within SQL statements

A comment can appear between keywords, parameters, or punctuation marks in a statement. You can include a comment in a statement in two ways:

Begin the comment with a slash and an asterisk (/*). Proceed with the text of the comment. The text can span multiple lines. End the comment with an asterisk and a slash. (*/). You do not need to separate the opening and terminating characters from the text by a space or line break.

Begin the comment with two hyphens (--). Proceed with the text of the comment. The text cannot extend to a new line. End the comment with a line break.

SQL-Syntax
A SQL statement can have one comment that includes one or more statement level optimizer hints. SQL statements that support statement level optimizer hints are DELETE, INSERT, MERGE, SELECT, UPDATE, INSERT...SELECT, and CREATE TABLE...AS SELECT. The hint must follow the DELETE, INSERT, MERGE, SELECT, or UPDATE keyword. (A DELETE, INSERT, MERGE, SELECT, or UPDATE keyword is also known as a SQL-VERB) shows the proper placement of hints in a SQL statement.
You embed statement level optimizer hints in comment syntax. TimesTen supports hints in comments that span one line and in comments that span more than one line. If your comment that contains the hint spans one or more lines, use the comment syntax, /*+...*/. If your comment that contains the hint spans one line, use the comment syntax, --+.










