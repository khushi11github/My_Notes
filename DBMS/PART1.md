##DBMS
🔴DBMS stands for Database Management System. 
It is software used to store, retrieve, update, and delete data in a database.
It provides features such as data security, data integrity, concurrency control,
and backup and recovery.
It acts as an interface between users or applications and the database, 
making data management easier and more efficient

[
##what is concurrency? 
means multiple transaction accessing or working on same dataset at the same time.
{ concurrency itself is not necessarily a problem. The problem occurs when concurrent transactions interfere with each other incorrectly}

A transaction is sequence of database operations such as reading, updating or deleting data.


###what is concurrency control?
is a mechanism used to manage the simultaneous execution of
the transactions by multiple users accessing the same database. 
it ensure data consistency and correctness by preventing problem that occur 
when transactions execute at same time



###concurrency control techniques 
1. Lock-Based Protocol 🔒
A transactions locks the data before accessing it so another ransaction cannot perform conflicting operations at same time.

2. Timestamp-Based Protocol ⏱️
Each transaction gets a unique timestamp. The database uses these timestamps to decide the order in which conflicting operations are allowed.
Example: An older transaction may be required to execute before a newer transaction.

3. Optimistic Concurrency Control ✅
Transactions proceed without locking data in advance. The database checks for conflicts before committing the changes.
Example: If two users edit the same record, the database checks whether their changes conflict before saving.
]




