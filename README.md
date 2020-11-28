###### Susan Lee 
###### Nov. 27, 2020 
###### IT Foundations of Database Management
###### Assignment07
###### https://github.com/SusanblUW/DBFoundations-Module07

## SQL Functions

### Introduction
In this paper I will discuss different types of SQL User Defined Functions (UDF) and similarities and differences between them.   I hope this can serve as helpful reference to future SQL developers so correct function can be utilized when working with SQL Database.  

### Unser Defined Functions
There are various SQL Server built-in functions that are extremely helpful to most users.  These built-in functions can be easily found in the web.  They can also be accessible through SQL Database by highlighting a function and pressing F1 on the keyboard.  Even though there are many built-in functions available, users can also create their own custom functions.  This known as User Defined Functions (UDFs).  The 3 different UDFs consists of Scalar, Inline, Multi-Statement Functions.  

### Scalar Function
The Scalar function returns a single value to the user.  The benefit of this function is that it can help users simplify their code.  "Instead of including the formula in every query, you can create a scalar function that encapsulates the formula and uses it in each query" (SQL Server Tutorial, (https://www.sqlservertutorial.net/sql-server-user-defined-functions/sql-server-scalar-functions/,2020).  Scalar function can have zero or more parameters.  

### Inline Function
Unlike Scalar function, Inline function returns a table of values.  Inline function can be used in conjunction with WHERE clause and can also be joined with other tables.  Since Inline function is treated as if it’s a table it can be useful when users want a list of values that meets the filtering criteria (parameter).  However, it’s worth noting that the same results can be achieved using the WHERE clause in a VIEW.  And since table functions are more complex and poses potential compatibility issues with some applications, usage of VIEWs may be more beneficial to the users.    

### Multi-Statement Function
Multi-Statement function is similar to Inline function.  However, unlike Inline function, in Multi-Statement function users must specify the structure of the table they need returned by designating column titles and data types.   

### Summary
In this paper I discussed what a User Defined Function is and the differences between Scalar, Inline, and Multi-Statement functions.  I hope this will help future SQL developers in understanding these different functions so that it can be used accurately when working on Relational Database.  
