ms-sql-gold-grammar
===================

A T-SQL grammar for Gold Parser.

It is an extention of the original T-SQL grammar for Gold Parser by Arsène von Wyss. 
C.f. http://code.google.com/p/bsn-modulestore/source/browse/bsn.ModuleStore.Parser/Sql/ModuleStoreSQL.grm

This grammar parses a subset of SQL commands. It parses many of my productive SQL scripts, views and procedures as long as they do not contain 
* "weird" characters in strings
* (NOLOCK) 
* additional white space or comment in "FOR READ ONLY"  in cursor definitions.
* any COMPUTE BY statements

Check the .grm file for comments and the license which applies.
