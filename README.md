# .NETCore-API-Dapper
 .NETCore-API-Dapper
Create Restful Api with Dapper
----
About Extension Methods

Dapper extends the IDbConnection interface with these multiple methods:

Execute – an extension method that we use to execute a command one or multiple times and return the number of affected rows

Query – with this extension method we can execute a query and map the result

QueryFirst –  it executes a query and maps the first result

QueryFirstOrDefault – we use this method to execute a query and map the first result, or a default value if the sequence contains no elements

QuerySingle – an extension method that can execute a query and map the result.  It throws an exception if there is not exactly one element in the sequence

QuerySingleOrDefault – executes a query and maps the result, or a default value if the sequence is empty. It throws an exception if there is more than one element in the sequence

QueryMultiple – an extension method that executes multiple queries within the same command and map results

----
