# Interview-Questions-and-Ans
******************************************************************************************************************************
******************************************************************************************************************************
Core Java                                                                           ******************************************
******************************************************************************************************************************
******************************************************************************************************************************
Difference between ArrayList and LinkedList
ArrayList uses a dynamic array and provides fast random access (O(1)), but insertion and deletion are slow due to shifting elements.
LinkedList uses a doubly linked list and allows faster insertion and deletion, but random access is slow (O(n)).
*****

HashMap vs ConcurrentHashMap
HashMap → ❌ Not thread-safe | ❌ Not synchronized | ✅ Allows 1 null key + multiple null values.
ConcurrentHashMap → ✅ Thread-safe | ❌ Not fully synchronized (uses internal locking) | ❌ No null key, no null value.
*****

HashMap vs Hashtable
HashMap → ❌ Not thread-safe | ❌ Not synchronized | ✅ Allows 1 null key & multiple null values
Hashtable → ✅ Thread-safe | ✅ Fully synchronized | ❌ No null key, no null value
*****

Abstract Class vs Interface
Abstract class → Can have constructor, instance variables, and abstract + non-abstract methods; supports single inheritance.
Interface → No constructor, methods are abstract by default (Java 8: default/static allowed); supports multiple inheritance.
*****

Why String is immutable?
For security, caching, and thread-safety.

String vs StringBuilder
String is immutable; StringBuilder is mutable & faster.

StringBuilder vs StringBuffer
StringBuilder is not thread-safe; StringBuffer is thread-safe.

*****
Checked Exception
Checked at compile time and mandatory to handle (IOException, SQLException, FileNotFoundException).

Unchecked Exception
Occurs at runtime and not mandatory to handle (NullPointerException, ArithmeticException, ArrayIndexOutOfBoundsException).

finally block
Always executes whether exception occurs or not (resource cleanup like file/DB close).
*****

Multithreading

Thread vs Runnable
Thread extends class; Runnable implements interface.

synchronized keyword
Allows only one thread at a time to access a resource.

Deadlock
Threads waiting for each other forever.
*****





******************************************************************************************************************************
******************************************************************************************************************************
Java 8
******************************************************************************************************************************
******************************************************************************************************************************



******************************************************************************************************************************
******************************************************************************************************************************
Spring Boot
******************************************************************************************************************************
******************************************************************************************************************************





******************************************************************************************************************************
******************************************************************************************************************************
SQL
******************************************************************************************************************************
******************************************************************************************************************************
What is Indexing in SQL?
Indexing in SQL is a way to speed up data retrieval from a database table—just like an index in a book helps you quickly find a topic without reading every page.
Instead of scanning the whole table row by row, the database uses an index to jump directly to the required data.
*****

What is a primary key?
A column (or combination) that uniquely identifies each row and does not allow NULL.
*****

What is a foreign key?
A key that links one table to another table’s primary key.
*****

Difference between UNIQUE and PRIMARY KEY
UNIQUE allows one NULL
PRIMARY KEY does not allow NULL
*****

What is a JOIN in SQL?
A JOIN is used to combine rows from two or more tables based on a related column (usually a primary key and foreign key).
**
Types of joins
INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL JOIN
SELF JOIN
*****

What is Normalization in SQL?
Normalization is the process of organizing data in a database to reduce redundancy and improve data integrity by dividing data into smaller related tables.
*****



******************************************************************************************************************************
******************************************************************************************************************************
Microservices
******************************************************************************************************************************
******************************************************************************************************************************
