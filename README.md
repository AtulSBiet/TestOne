TestOne
==========
Restriction On DB name:
 MySql
1. Cannot contain “/”, “\”, “.”, or characters that are not permitted in file names.
2. Cannot end with space characters.
3. Max length is 64
4. Mysql and database name not allowed for db

 
 Goto following link for details: http://dev.mysql.com/doc/refman/5.0/en/identifiers.html

Mongo:
Database names can be any UTF-8 string, with the following restrictions:
• The empty string ("") is not a valid database name.
• A database name cannot contain any of these characters: ' ' (a single space), ., $, /, \, or \0 (the null character).
• Database names should be all lowercase.( Need verification)
• Database names are limited to a maximum of 64 bytes.

 Goto following link for details: http://docs.mongodb.org/manual/release-notes/2.2/


